<template>
  <div class="turna">
    <div class="turna-map">
      <h3>Otele Ulaşım</h3>
      <p1>
        Antalya Şehir Merkezi, Sakıp Sabancı Bulvarı, Çimen Sokak,Antalya,
        Turkey, 07050
      </p1>
      <iframe
        class="turna-map-location"
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3191.1479517700386!2d30.672536199999993!3d36.886808699999996!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x14c390340cb47fb9%3A0x272477432af34686!2sMeltem%2C%20Sak%C4%B1p%20Sabanc%C4%B1%20Blv.%2C%2007030%20Muratpa%C5%9Fa%2FAntalya!5e0!3m2!1str!2str!4v1661869547301!5m2!1str!2str"
        style="border: 0"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
      ></iframe>
      <button class="turna-map-buton">Haritada Göster</button>
    </div>
    <div class="turna-hotel">
      <div class="turna-hotel-row">
        <div class="turna-hotel-column">
          <div class="turna-hotel-info">
            <h2 class="turna-hotel-name">Rixos Downtown Hotel (9.0)</h2>
            <img class="turna-hotel-star" src="../image/star (2).svg" />
            <img class="turna-hotel-star" src="../image/star (2).svg" />
            <img class="turna-hotel-star" src="../image/star (2).svg" />
          </div>
          <div class="turna-hotel-location">
            <img src="../image/map-pin (3).svg" />
            Antalya,Merkez
          </div>
        </div>
        <button class="turna-hotel-rezerv">Rezervasyon yap</button>
      </div>
      <ImageSlider />
      <div class="turna-hotel-commen">
        The purpose of lorem ipsum is to create a natural looking block of
        text(sentence,paragraph,page,etc.) that doesn't distract from the
        layout. A practice not without controversy,laying out pages with
        meaningless filler text can be.
      </div>
      <room-info />
      <div class="turna-features">
        <h2>Otel Özellikleri</h2>
        <div class="turna-features-card">
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Sauna</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Market</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Hamam</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Bar</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Masaj</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Açık Restoran</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Spa Merkezi</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Kapalı Restoran</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Otelde Otopark</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Tv Salonu</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Engelli Odaları</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Araç Kiralama</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Havaalanı</p>
          </div>
        </div>
      </div>
      <div class="turna-features">
        <h2>Otel Koşulları</h2>
        <div class="turna-features-card">
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Sauna</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Market</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Hamam</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Bar</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Masaj</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Açık Restoran</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Spa Merkezi</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Kapalı Restoran</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Otelde Otopark</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Tv Salonu</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Engelli Odaları</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Araç Kiralama</p>
          </div>
          <div class="turna-features-column">
            <img src="../image/check.svg" class="check" />
            <p>Havaalanı</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import RoomInfo from "./RoomCard.vue";
import ImageSlider from "./ImageSlider.vue";
export default {
  components: { RoomInfo, ImageSlider },
  name: "HotelComponent",
};
</script>
<style lang="scss" scoped>
@import "../assets/color.scss";
.turna {
  display: flex;
  text-align: start;
  padding-inline-start: 17%;
  gap: 25px;
  &-map {
    max-width: 280px;
    max-height: 180px;
    &-buton {
      border-radius: 8px;
      border: 1px solid $color-secondary;
      padding: 1em 8em 1em;
      font-weight: bold;
      margin-top: 10px;
      color: $color-secondary;
      background: $color-secondary-light;
      cursor: pointer;
    }
    &-location {
      width: 100%;
      height: 100%;
    }
  }
  &-hotel {
    &-img {
      width: 100%;
    }
    &-info {
      display: flex;
      justify-content: space-between;
      gap: 10px;
    }
    &-location {
      margin-top: -15px;
      margin-bottom: 15px;
      font-size: 18px;
    }
    &-column {
      display: flex;
      flex-direction: column;
    }
    &-row {
      display: flex;
      justify-content: space-between;
    }
    &-rezerv {
      border: none;
      border-radius: 8px;
      padding: 1em 1.6em 1em;
      margin-bottom: 14px;
      margin-top: 14px;
      font-size: 1vw;
      background-color: $color-secondary;
      color: $color-white;
      cursor: pointer;
    }
    &-commen {
      font-size: 1.3em;
      color: $color-dark;
    }
  }

  &-features {
    border-top: 2px solid $color-30;
    margin-top: 20px;
    font-size: 15px;
    font-weight: lighter;
    &-card {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
    }
    &-column {
      display: flex;
    }
  }
}
@media screen and (max-width: 1023px) {
  .check {
    display: none;
  }
}
@media screen and (max-width: 1023px) {
  .turna-map {
    display: none;
  }
}
@media screen and (max-width: 767px) {
  .turna-hotel-star {
    display: none;
  }
}
</style>
