<template>
  <div>
    <h1 style="text-align: center;">
      Vue-Fabric-Wrapper
      <Badge :text="$__VERSION__" type="tip" vertical="middle" />
    </h1>
    <p style="text-align: center;">A Fabric Wrapper for the Vue Framework</p>
    <div class="box">
      <ClientOnly>
        <StickMan />
      </ClientOnly>
    </div>
    <div class="box">
      <router-link class="button" to="/guide/">Get started</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero"
};
</script>

<style>
.h1 {
  font-size: 48px;
  text-align: center;
}
.box {
  padding: 30px 0;
  display: flex;
  justify-content: center;
  flex: 1 0 auto;
}

.button {
  font-size: 24px;
  border: 2px solid #42b983;
  color: #42b983;
  border-radius: 5px;
  padding: 10px 15px;
}
</style>