<template>
  <div>
    <img src="@/assets/images/bgmain.png" alt="" />
    <swiper
      :slidesPerView="1"
      :loop="true"
      :pagination="{
        clickable: true,
      }"
      :navigation="true"
      :modules="modules"
      class="mySwiper"
    >
      <swiper-slide class="parenti" v-for="(item, i) in 4" :key="i">
        <img :src="`https://picsum.photos/1900/400?random=${i}`" alt="" />
        <div class="gradient">
                <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam, consequuntur ut labore excepturi harum nesciunt similique quaerat cupiditate corrupti praesentium est provident libero quidem accusantium eligendi voluptas voluptatem ipsa cum.</h1>
        </div>
        salom {{ i }}
      </swiper-slide>
    </swiper>
  </div>
</template>

<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
import "swiper/css/pagination";
import "swiper/css/navigation";
import { Pagination, Navigation } from "swiper/modules";

export default {
  data() {
    return {
      modules: [Pagination, Navigation],
    };
  },
  components: {
    Swiper,
    SwiperSlide,
  },
};
</script>

<style scoped>
.mySwiper {
  width: 100%;
  height: 300px;
}
</style>