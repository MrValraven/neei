<template>
  <button id="btnScrollToTop" aria-label="Scroll to top">
    <i class="fa fa-arrow-up" aria-hidden="true"></i>
  </button>
</template>

<script lang="js">
export default {
  name: "ScrollToTopButton",
};
</script>

<style lang="scss">
#btnScrollToTop {
  position: fixed;
  right: 10px;
  bottom: 10px;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  color: white;
  background: darken($color: #1935a1, $amount: 10%);
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.25);
  outline: none;
  opacity: 1;
  cursor: pointer;
  transition: 0.5s;
  z-index: 10;

  i {
    transition: all 0.1s ease-in;
  }

  &:hover i {
    font-size: 1.2rem;
  }
}
</style>
