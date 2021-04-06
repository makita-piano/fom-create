<template>
  <div class="grid-center col-12" :class="{fadeIn: visible}">
    <slot v-show="visible"></slot>
  </div>
</template>

<style>
  .fadeIn {
    animation: fadeIn 3s;
  }
  @keyframes fadeIn {
    0% {
      opacity: .1;
    }
    20% {
      opacity: .1;
    }
    100% {
      opacity: 1;
    }
  }
</style>

<script>
  export default {
    data() {
      return {
        visible: false
      };
    },
    created() {
      if (process.client) {
        window.addEventListener("scroll", this.handleScroll);
      }
    },
    destroyed() {
      if (process.client) {
        window.removeEventListener("scroll", this.handleScroll);
      }
    },
    methods: {
      handleScroll() {
        if (!this.visible) {
          var top = this.$el.getBoundingClientRect().top;
          this.visible = top < window.innerHeight + 100;
        }
      }
    }
  }
</script>