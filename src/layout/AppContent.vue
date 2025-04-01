<script>
export default {
  components: {},
  data() {
    return {};
  },
};
</script>

<template>
  <main>
    <section class="h-100">
      <div class="container py-5 h-100 text-center">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2876.5472019067033!2d10.25347247467986!3d43.86521293869491!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12d5a1fee6eb70bf%3A0xead5fbd411a8a695!2sVia%20Paolo%20Savi%2C%209%2C%2055049%20Viareggio%20LU!5e0!3m2!1sit!2sit!4v1743501909392!5m2!1sit!2sit"
          width="600"
          height="300"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
        ></iframe>
        <p>Via Paolo Savi, 9 55049 Viareggio (LU)</p>
        <p><font-awesome-icon :icon="['fas', 'phone']" /> 0584 176 0555</p>
        <p><font-awesome-icon :icon="['fas', 'mobile']" /> +39 393 414 7420</p>
        <p>
          <font-awesome-icon :icon="['fas', 'envelope']" />
          <a href="mailto:info@bosun.it"> info@bosun.it</a>
        </p>
      </div>
    </section>
  </main>
</template>

<style>
p {
  margin-bottom: 4px;
}
</style>
