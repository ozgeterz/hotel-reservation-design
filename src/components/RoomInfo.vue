<template>
  <div class="card-group">
    <div class="card">
      <img class="card-img" src="../İmage/oda1.jpg" alt="Card image cap" />
      <div class="card-body">
        <h3 class="card-title">Standart Oda</h3>
        <div class="card-features-column">
          <img src="../İmage/check-circle.svg" />
          <p>Banyo</p>
        </div>
        <div class="card-features-column">
          <img src="../İmage/check-circle.svg" />
          <p>İnternet</p>
        </div>
        <div class="card-features-column">
          <img src="../İmage/check-circle.svg" />
          <p>Havlu</p>
        </div>
        <div class="card-info">
          <div class="card-info-box">
            <h5>İki gece için toplam tutardır.</h5>
            <a class="card-info-box-button" href="#popup1">Detaylar</a>
          </div>
          <button class="card-info-room">Odanı Ayır</button>
        </div>
      </div>
    </div>
    <div class="card">
      <img class="card-img" src="../İmage/oda2.jpg" alt="Card image cap" />
      <div class="card-body">
        <h3 class="card-title">İki Balkonlu Oda(Delux)</h3>
        <div class="card-features-column">
          <img src="../İmage/check-circle.svg" />
          <p>Banyo</p>
        </div>
        <div class="card-features-column">
          <img src="../İmage/check-circle.svg" />
          <p>İnternet</p>
        </div>
        <div class="card-features-column">
          <img src="../İmage/check-circle.svg" />
          <p>Havlu</p>
        </div>

        <div class="card-info">
          <div class="card-info-box">
            <h5>İki gece için toplam tutardır.</h5>
            <a class="card-info-box-button" href="#popup1">Detaylar</a>
          </div>
          <button class="card-info-room">Odanı Ayır</button>
        </div>
      </div>
    </div>
    <div id="popup1" class="modal">
      <div class="modal-popup">
        <img src="../İmage/oda1.jpg" class="modal-img" />
        <a class="modal-close" href="#">&times;</a>
        <div class="modal-content">
          <h2>Standart Oda</h2>
          <h5>
            The purpose of lorem ipsum is to create a natural looking block of
            text(sentence,paragraph,page,etc.) that doesn't distract from the
            layout. A practice not without controversy, laying out pages with
            meaningless fillet text can be.
          </h5>
          <div class="modal-content-info">
            <button class="modal-content-buton">
              Erken Rezervasyon İndirimi
            </button>
            <button class="modal-content-buton">Her Şey Dahil</button>
            <button class="modal-content-buton">Ücretsiz İptal</button>
          </div>
          <div class="modal-content-features">
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Sauna</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Market</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Hamam</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Bar</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Masaj</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Açık Restoran</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Spa Merkezi</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Kapalı Restoran</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Otelde Otopark</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Tv Salonu</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Engelli Odaları</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Araç Kiralama</p>
            </div>
            <div class="modal-content-features-column">
              <img src="../İmage/check.svg" />
              <p>Havaalanı</p>
            </div>
          </div>
          <div class="modal-content-price">
            <div class="modal-content-price-info">
              <h1>1500TL</h1>
              <h5>22 gece için toplam tutardır.</h5>
            </div>

            <button class="modal-content-price-button">Odanı Ayır</button>
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
  border: 2px solid $bordercolor1;
  display: flex;
  margin-top: 20px;
  height: 40vh;

  &-img {
    width: 250px;
  }
  &-info {
    border-top: 2px solid $bordercolor2;
    display: flex;
    gap: 200px;
    align-items: center;
    &-box {
      &-button {
      }
      &-button:hover {
      }
    }

    &-room {
      align-items: center;
      background-color: $butonbackground2;
      color: $maincolor;
      border: none;
      border-radius: 8px;
      padding: 16px 40px;
      cursor: pointer;
    }
  }
  &-body {
    padding-inline-start: 2%;
  }
  &-features-column {
    display: flex;
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
  background: rgba(0, 0, 0, 0.7);
  transition: opacity 500ms;
  visibility: hidden;
  opacity: 0;
  padding-left: 22%;
  &:target {
    visibility: visible;
    opacity: 1;
  }
  &-img {
    width: 100%;
    height: 300px;
  }
  &-popup {
    max-width: 60%;
    height: 100vh;
    background: #fff;
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
    &-info {
      display: flex;

      gap: 10px;
    }
    &-buton {
      color: $butoncolor2;
      background: $butonbackground3;
      border: none;
      font-weight: bold;
    }
    &-features {
      font-size: 13px;
      font-weight: bold;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      &-column {
        display: flex;
      }
    }
    &-price {
      display: flex;
      border-top: 2px solid $bordercolor2;
      gap: 200px;
      align-items: center;
      justify-content: space-evenly;
      &-info {
      }
      &-button {
        align-items: center;
        background-color: $butonbackground2;
        color: $maincolor;
        border: none;
        border-radius: 8px;
        padding: 16px 40px;
        cursor: pointer;
      }
    }
  }
}
</style>
