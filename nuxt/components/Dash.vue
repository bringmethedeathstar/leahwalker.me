<script>
export default {
  props: ['rotate'],
};
</script>

<template>
  <svg
    class="stroke-current"
    :class="{ rotate }"
    xmlns="http://www.w3.org/2000/svg"
    width="52.5"
    height="33.4"
    viewBox="0 0 52.5 33.4"
  >
    <path
      class="sign-up-line sign-up-line--1"
      d="M6,18-2.3-.4"
      transform="translate(4.3 13.4)"
      style="stroke-linecap: round; stroke-miterlimit: 10; stroke-dashoffset: 0px;"
      fill="none"
      stroke-width="4"
    />
    <path
      class="sign-up-line sign-up-line--2"
      d="M22,16.1V-11.4"
      transform="translate(4.3 13.4)"
      style="stroke-linecap: round; stroke-miterlimit: 10; stroke-dashoffset: 0px;"
      fill="none"
      stroke-width="4"
    />
    <path
      class="sign-up-line sign-up-line--3"
      d="M37.9,18,46.2-1.4"
      transform="translate(4.3 13.4)"
      style="stroke-linecap: round; stroke-miterlimit: 10; stroke-dashoffset: 0px;"
      fill="none"
      stroke-width="4"
    />
  </svg>
</template>

<style scoped>
svg {
  width: 0.75em;
  height: 0.75em;
}
.rotate {
  transform: rotate(180deg);
}
</style>
