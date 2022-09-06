<template>
  <div class="slider">
    <div
      v-for="card in cards"
      :key="card.id"
      :style="{ display: active_card.id != card.id ? 'none' : '' }"
    >
      <img class="slider-art" :src="card.img" />
    </div>
    <div class="slider-dots">
      <span
        :class="{ dot: true, active: dot.id == active_slide }"
        v-for="dot in cards"
        :key="dot"
        @click="this.activate(dot.id)"
      >
      </span>
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
          img: "https://ucdn.tatilbudur.net/Otel/960x475/selcukhan-hotel_422508.jpg",
          id: 1,
        },
        {
          img: "https://ucdn.tatilbudur.net/Otel/960x475/ayayorgi-hotel-by-t_312987.jpg",
          id: 2,
        },
        {
          img: "https://ucdn.tatilbudur.net/Otel/960x475/amon-hotels-belek-16_421454.jpg",
          id: 3,
        },
      ],
      active_slide: 1,
    };
  },
  methods: {
    activate(id) {
      this.active_slide = id;
    },
  },
  computed: {
    active_card: function () {
      return this.cards.filter((card) => card.id == this.active_slide)[0];
    },
  },
};
</script>

<!-- Use preprocessors via the lang attribute! e.g. <style lang="scss"> -->
<style lang="scss" scoped>
@import "../assets/color.scss";
.slider {
  position: relative;
  &-dots {
    position: absolute;
    bottom: 30px;
    left: 50%;
    padding: 5px;
    transform: translate(-50%);

  }
  &-art {
    width: 100%;
    max-height: 70vh;
    transition: opacity 0.001s ease;
    border-radius: 10px;
    margin-bottom: 20px;
  }
  .dot.active {
    width: 20px;
    background:$color-white;
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
}
</style>
