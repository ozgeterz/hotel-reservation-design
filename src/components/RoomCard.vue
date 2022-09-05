<template>
  <div class="card-group">
    <div class="card">
      <img
        class="card-img"
        src="../image/otel-odasi-04.jpg"
        alt="Card image cap"
      />
      <div class="card-body">
        <h3 class="card-title">Standart Oda</h3>
        <div class="card-content-info">
          <button class="card-content-buton">Erken Rezervasyon İndirimi</button>
          <button class="card-content-buton">Ücretsiz İptal</button>
          <button class="card-content-buton">Her Şey Dahil</button>
        </div>
        <div class="card-features">
          <div class="card-features-row">
            <div class="card-features-column">
              <img src="../image/check-circle.svg" />
              <p>Banyo</p>
            </div>
            <div class="card-features-column">
              <img src="../image/check-circle.svg" />
              <p>İnternet</p>
            </div>
            <div class="card-features-column">
              <img src="../image/check-circle.svg" />
              <p>Havlu</p>
            </div>
          </div>
          <div class="card-features-price">₺ 1.500</div>
        </div>
        <div class="card-info">
          <div class="card-info-box">
            <p>İki gece için toplam tutardır.</p>
            <a class="card-info-box-button" href="#popup1">Detaylar</a>
          </div>
          <button class="card-info-room">Odanı Ayır &#10230;</button>
        </div>
      </div>
    </div>
    <div class="card">
      <img
        class="card-img"
        src="../image/dime-otel-odasi-c6d3.jpg"
        alt="Card image cap"
      />
      <div class="card-body">
        <h3 class="card-title">İki Balkonlu Oda(Delux)</h3>
        <div class="card-content-info">
          <button class="card-content-buton">Erken Rezervasyon İndirimi</button>
          <button class="card-content-buton">Ücretsiz İptal</button>
          <button class="card-content-buton">Her Şey Dahil</button>
        </div>
        <div class="card-features">
          <div class="card-features-row">
            <div class="card-features-column">
              <img src="../image/check-circle.svg" />
              <p>Banyo</p>
            </div>
            <div class="card-features-column">
              <img src="../image/check-circle.svg" />
              <p>İnternet</p>
            </div>
            <div class="card-features-column">
              <img src="../image/check-circle.svg" />
              <p>Havlu</p>
            </div>
          </div>
          <div class="card-features-price">₺ 1.500</div>
        </div>
        <div class="card-info">
          <div class="card-info-box">
            <p>İki gece için toplam tutardır.</p>
            <a class="card-info-box-button" href="#popup1">Detaylar</a>
          </div>
          <button class="card-info-room">Odanı Ayır &#10230;</button>
        </div>
      </div>
    </div>
    <div id="popup1" class="modal">
      <div class="modal-popup">
        <img src="../image/pop-up1.jpg" class="modal-img" />
        <a class="modal-close" href="#">&times;</a>
        <div class="modal-content">
          <h2 class="modal-content-title">Standart Oda</h2>
          <p1 class="modal-content-commen">
            The purpose of lorem ipsum is to create a natural looking block of
            text(sentence,paragraph,page,etc.) that doesn't distract from the
            layout. A practice not without controversy, laying out pages with
            meaningless fillet text can be.
          </p1>
          <div class="modal-content-info">
            <button class="modal-content-buton">
              Erken Rezervasyon İndirimi
            </button>
            <button class="modal-content-buton">Her Şey Dahil</button>
            <button class="modal-content-buton">Ücretsiz İptal</button>
          </div>
          <div class="modal-content-features">
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Sauna</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Market</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Hamam</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Bar</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Masaj</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Açık Restoran</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Spa Merkezi</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Kapalı Restoran</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Otelde Otopark</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Tv Salonu</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Engelli Odaları</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Araç Kiralama</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../image/check.svg" class="check" />
              <p>Havaalanı</p>
            </div>
          </div>
          <div class="modal-content-price">
            <div class="modal-content-price-info">
              <h1 class="modal-content-price-tl">₺ 1.500</h1>
              <h5>22 gece için toplam tutardır.</h5>
            </div>

            <button class="modal-content-price-button">
              Odanı Ayır &#10230;
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RoomInfo",
};
</script>

<style lang="scss" scoped>
@import "../assets/color.scss";

.card {
  display: flex;
  margin-top: 20px;
  border: 2px solid $color-40;
  &-title {
    font: normal normal bold 20px Montserrat;
  }
  &-content {
    &-info {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
    }
    &-buton {
     
      color: $butoncolor2;
      background: $butonbackground3;
      border: none;
      font-weight: bold;
    }
  }
  &-img {
    max-width: 38%;
   
  }
  &-info {
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-top: 2px solid $color-30;
    gap: 60px;
    &-box {
      &-button {
        color: $color-secondary;
        text-decoration: none;
        
        font-weight: bold;
      }
    }
    &-room {
      border: none;
      border-radius: 8px;
      padding: 1em 2.1em 1em;
      font-weight: bold;
    
      background-color: $color-secondary;
      color: $color-white;
      cursor: pointer;
    }
  }
  &-body {
    padding-inline-start: 2%;
  }
  &-features {
    display: flex;
    justify-content: space-between;
    &-column {
      display: flex;
      
    }
    &-price {
      font-weight: bold;
      font-size: 2em;
      margin-top: 90px;
      color: $color-secondary;
    }
  }
}
.modal {
  position: fixed;
  display: flex;
  align-items: center;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(0, 0, 0, 0.5);
  transition: opacity 500ms;
  visibility: hidden;
  opacity: 0;
  padding-left: 27%;
  &:target {
    visibility: visible;
    opacity: 1;
  }
  &-img {
    width: 100%;
    height: 45%;
  }
  &-popup {
    width: 70%;
    height: 97%;
    background: $color-white;
    border-radius: 5px;
    position: relative;
    transition: all 5s ease-in-out;
  }
  &-close {
    position: absolute;
    transition: all 200ms;
    font-size: 40px;
    font-weight: bold;
    text-decoration: none;
    color: $butoncolor2;
  }
  &-content {
    margin-left: 20px;
    margin-right: 20px;

    &-info {
      display: flex;
      gap: 5px;
    }

    &-buton {
      color: $butoncolor2;
      background: $butonbackground3;
      border: none;
      font-weight: bold;
      margin-top:10px;
    }
    &-features {
      font-size: 1vw;
      font-weight: 500;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      margin-top: 15px;
      &-column {
        display: flex;
        margin-top: -20px;
      }
    }
    &-price {
      display: flex;
      border-top: 2px solid $color-30;
      align-items: center;
      justify-content: space-between;
      &-tl {
        color: $color-secondary;
      }
      &-info {
        font-size: 1vw;
      }
      &-button {
        background-color: $color-secondary;
        color: $color-white;
        border: none;
        border-radius: 8px;
        padding: 1em 2.1em 1em;
        font-size: 1vw;
        cursor: pointer;
      }
    }
  }
}
@media screen and (max-width: 767px) {
  .card-img {
    display: none;
  }
}
@media screen and (max-width: 1023px) {
  .modal-content-features {
    display: none;
  }
}
@media screen and (max-width: 1023px) {
  .modal-content-info {
    display: none;
  }
}
</style>
