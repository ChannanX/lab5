<template>
  <div id="carouselExampleIndicators" class="carousel slide mt-5">
    <div class="carousel-indicators " style="height: rem;" >
      <button
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide-to="0"
        class="active"
        aria-current="true"
        aria-label="Slide 1"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide-to="1"
        aria-label="Slide 2"
      ></button>
      <button
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide-to="2"
        aria-label="Slide 3"
      ></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <Card class="mx-auto"
          ><template #pic
            ><img
              src="https://c4.wallpaperflare.com/wallpaper/53/21/243/angel-angelic-ascension-belief-wallpaper-preview.jpg"
              class="card-img-top"
              alt="..."
            />
          </template>
        </Card>
      </div>
      <div class="carousel-item">
        <Card class="mx-auto"
          ><template #pic
            ><img
              src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQMg1ViaRmwVc2A9D0ayLDzFqu46YGxLR0AXO0PyXJoBp9Ssvicf58xc5t3wb-n4YRys2I&usqp=CAU"
              class="card-img-top"
              alt="..."
            />
          </template>
        </Card>
      </div>
      <div class="carousel-item">
        <Card class="mx-auto"
          ><template #pic
            ><img
              src="https://wallpapertag.com/wallpaper/middle/2/f/4/511669-top-wallpaper-for-desktop-full-screen-1920x1080-for-android.jpg"
              class="card-img-top"
              alt="..."
            />
          </template>
        </Card>
      </div>
    </div>
    <button
      class="carousel-control-prev "
      type="button"
      data-bs-target="#carouselExampleIndicators"
      data-bs-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button
      class="carousel-control-next "
      type="button"
      data-bs-target="#carouselExampleIndicators"
      data-bs-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
</template>
<script setup>
import Card from "./card.vue";
</script>

