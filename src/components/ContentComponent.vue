<template>
  <section v-for="(list, index) in lists" :key="index">
    <div class="container">
      <div class="row pb-4">
        <div class="col-md-12 mb-4">
          <div class="border-top-fade-black-2-2px"></div>
        </div>
        <div class="col-lg-4">
          <div class="wrapper">
            <p class="fs-5 text-fade-black-1">{{ list.title }}</p>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="wrapper d-flex flex-column justify-content-between h-100">
            <p class="fs-5">{{ list.content }}</p>
            <div class="link mb-3 mb-lg-0">
              <a class="fs-5 border-bottom-fade-black-1-2px" :href="list.link">
                Lorem, ipsum dolor.
              </a>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="wrapper">
            <figure class="m-0">
              <img class="w-100 h-image-400px grayscale" :src="list.image" :alt="`image-${index}`" />
            </figure>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContentComponent",
  data() {
    return {
      lists: [
        {
          title: "Lorem, ipsum dolor",
          content:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis hic rerum nesciunt assumenda accusamus dignissimos numquam minus, accusantium, ea sit autem inventore delectus ut similique officia. Fugit voluptatum",
          image: require("@/assets/source/image/img-1.jpg"),
          link: "#",
        },
        {
          title: "Lorem, ipsum dolor",
          content:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis hic rerum nesciunt assumenda accusamus dignissimos numquam minus, accusantium, ea sit autem inventore delectus ut similique officia. Fugit voluptatum",
          image: require("@/assets/source/image/img-2.jpg"),
          link: "#",
        },
        {
          title: "Lorem, ipsum dolor",
          content:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis hic rerum nesciunt assumenda accusamus dignissimos numquam minus, accusantium, ea sit autem inventore delectus ut similique officia. Fugit voluptatum",
          image: require("@/assets/source/image/img-3.jpg"),
          link: "#",
        },
        {
          title: "Lorem, ipsum dolor",
          content:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis hic rerum nesciunt assumenda accusamus dignissimos numquam minus, accusantium, ea sit autem inventore delectus ut similique officia. Fugit voluptatum",
          image: require("@/assets/source/image/img-4.jpg"),
          link: "#",
        },
        {
          title: "Lorem, ipsum dolor",
          content:
            "Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis hic rerum nesciunt assumenda accusamus dignissimos numquam minus, accusantium, ea sit autem inventore delectus ut similique officia. Fugit voluptatum",
          image: require("@/assets/source/image/img-5.jpg"),
          link: "#",
        },
      ]
    }
  }
}
</script>