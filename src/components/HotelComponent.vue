<template>
  <div class="turna">
    <div class="turna-map">
      <h4 class="turna-map-transport">Otele Ulaşım</h4>
      <p class="turna-map-info">
        Antalya Şehir Merkezi, Sakıp Sabancı Bulvarı, Çimen Sokak,Antalya,
        Turkey, 07050
      </p>
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
            <p1 class="turna-hotel-location-name">Antalya,Merkez</p1>
          </div>
        </div>
        <button class="turna-hotel-rezerv">Rezervasyon yap</button>
      </div>
      <ImageSlider />
      <p1 class="turna-hotel-commen">
        The purpose of lorem ipsum is to create a natural looking block of
        text(sentence,paragraph,page,etc.) that doesn't distract from the
        layout. A practice not without controversy,laying out pages with
        meaningless filler text can be.
      </p1>
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
@import "../assets/font.scss";

.turna {
  display: flex;
  gap: 25px;
  &-map {
    width: 305px;
    height: 190px;
    &-transport {
      color: $color-dark;
      font-size: 19px;
      margin-bottom: 10px;
    }
    &-info {
      margin-bottom: 15px;
      color: $color-70;
    }
    &-buton {
      border-radius: 8px;
      border: 1px solid $color-secondary;
      width: 305px;
      height: 56px;
      font-weight: bold;
      margin-top: 16px;
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
    &-star {
      margin-right: -10px;
    }
    &-img {
      width: 100%;
    }
    &-info {
      display: flex;
      gap: 16px;
    }
    &-location {
      display: flex;
      margin-top: -10px;
      margin-bottom: 24px;

      &-name {
        font-size: 17px;
        color: $color-dark;
      }
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
      border-radius: 6px;
      padding: 1em 1.6em 1em;
      margin-bottom: 22px;
      margin-top: 19px;
      font-size: 18px;
      background-color: $color-secondary;
      color: $color-white;
      cursor: pointer;
    }
    &-commen {
      font-size: 20px;
      text-align: left;
      color: $color-dark;
    }
  }
  &-features {
    border-top: 1px solid $color-30;
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
