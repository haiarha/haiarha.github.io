<template>
  <div id="default-layout" class="stretch-parent">
    <section class="section stretch-parent stretch-child">
      <div class="container stretch-child">
        <nuxt/>
      </div>
    </section>
    <footer class="footer">
      <div class="container">
        <p>
          <strong>Haiarha</strong> FrontEnd web developer.
        </p>
      </div>
    </footer>
  </div>
</template>

<style lang="scss" scoped>
#default-layout {
  min-height: 100%;
  height: 100%;
  overflow: auto;
}

.footer {
  flex-grow: 0;
}

.container {
  width: 100%;
}

.stretch-child {
  flex-grow: 1;
}

.stretch-parent {
  display: flex;
  flex-direction: column;
  justify-content: stretch;
}
</style>
