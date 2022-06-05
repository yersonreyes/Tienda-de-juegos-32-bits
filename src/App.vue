<template>
  <div>
    <header class="mb-4"></header>

    <main>
      <div class="container">
        <transition mode="out-in" name="fade">
          <router-view />
        </transition>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  components: {},
}
</script>

<style lang="scss"></style>
