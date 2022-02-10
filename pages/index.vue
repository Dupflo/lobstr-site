<template>
  <main>
    <Header />
    <BaseTitle>Hello Word</BaseTitle>
    <p>
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet delectus
      fuga aliquid, accusantium laboriosam, doloribus dolore illum, deserunt
      ipsam quisquam ad vel laborum ab facere non eligendi! Vel, quia alias.
      Blanditiis, explicabo id cumque iste nesciunt, rem eius, laudantium ex
      neque aut et molestiae dolor dicta deserunt deleniti!
    </p>
    <BaseButton>Hello</BaseButton>
    <Footer />
  </main>
</template>

<script>
import Footer from "../components/Footer.vue";
export default {
  components: { Footer },
  name: "IndexPage",
};
</script>
