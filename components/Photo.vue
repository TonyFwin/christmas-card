<template>
  <section class="pt-8 md:pt-16">
    <div class="container mx-auto relative">
      <div class="tape top-left"></div>
      <img
        class="shadow-lg rounded max-w-full h-auto align-middle border-none"
        src="~/assets/images/paddys-2.jpg"
        alt=""
      />
      <div class="tape bottom-right"></div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style>
.tape {
  background-color: hsla(0, 0%, 100%, 0.3);
  box-shadow: inset 0 0 1em 0.5em hsla(0, 0%, 100%, 0.1);
  height: 3em;
  position: absolute;
  transform: rotate(-27deg);
  width: 9em;
}
.tape.bottom-right {
  right: 0;
  bottom: 0em;
}
.tape:after,
.tape:before {
  background-size: 0.4em 0.4em;
  bottom: 0;
  content: '';
  position: absolute;
  top: 0;
  width: 0.2em;
}
.tape:after {
  background-image: linear-gradient(
      45deg,
      transparent 50%,
      hsla(0, 0%, 100%, 0.5) 50%
    ),
    linear-gradient(-45deg, transparent 50%, hsla(0, 0%, 100%, 0.3) 50%);
  background-position: 0 100%;
  left: -0.2em;
}
.tape:before {
  background-image: linear-gradient(
      135deg,
      transparent 50%,
      hsla(0, 0%, 100%, 0.5) 50%
    ),
    linear-gradient(-135deg, transparent 50%, hsla(0, 0%, 100%, 0.3) 50%);
  background-position: 100% 100%;
  right: -0.2em;
}
</style>
