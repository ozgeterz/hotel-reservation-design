<template>
    <div id="app">
      <div class="fill-screen">
        <div
          v-for="card in cards"
          class="img"
          :key="card.id"
          :style="{ display: active_card.id != card.id ? 'none' : '' }"
        >
          <img class="art" :src="card.art" />
        </div>
        <div class="dots">
          <span
            :class="{ dot: true, active: dot.id == active_slide }"
            v-for="dot in cards"
            :key="dot"
            @click="this.activate(dot.id)"
          >
          </span>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    created() {
      console.log("here");
      if (this.auto_animate) {
        this.interval = setInterval(() => {
          this.active_slide =
            this.active_slide == this.cards.length
              ? 1
              : (this.active_slide + 1) % (this.cards.length + 1);
        }, 5000);
      }
    },
    data() {
      return {
        auto_animate: true,
        cards: [
          {
            art:
              "https://media-cdn.tripadvisor.com/media/photo-s/16/1a/ea/54/hotel-presidente-4s.jpg",
            id: 1
          },
          {
            art:
              "https://ucdn.tatilbudur.net/Otel/960x475/ayayorgi-hotel-by-t_312987.jpg",
            id: 2
          },
          {
            art:
              "https://ucdn.tatilbudur.net/Otel/960x475/amon-hotels-belek-16_421454.jpg",
            id: 3
          },
          {
            art:
              "https://ucdn.tatilbudur.net/Otel/960x475/selcukhan-hotel_422508.jpg",
            id: 4
          },
        
        ],
        active_slide: 1
      };
    },
    methods: {
      activate(id) {
        this.active_slide = id;
      }
    },
    computed: {
      active_card: function () {
        return this.cards.filter((card) => card.id == this.active_slide)[0];
      }
    }
  };
  </script>
  
  <!-- Use preprocessors via the lang attribute! e.g. <style lang="scss"> -->
  <style>
 
  .fill-screen {
    position: relative;
  }
  .dots {
    position: absolute;
    bottom: 15px;
    left: 50%;
    padding: 10px;
    background: #777777aa;
    border-radius: 25px;
  }
  .dot.active {
    width: 20px;
    background: lightgray;
    border-radius: 8px;
  }
  
  .dot {
    width: 8px;
    height: 8px;
    background: lightgray;
    display: inline-block;
    margin: 0 4px;
    border-radius: 8px;
    transition: width 0.1s ease-in;
    box-shadow: 1px 1px 9px 2px grey;
    cursor: pointer;
    
  }
  .art {
    width: 100%;
    height: 60vh;
   
    transition: opacity 0.001s ease;
   
  }
  </style>
  