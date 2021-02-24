<template>
  <ul class="icons-in-circle">
    <li>
      <fa :icon="['fab', 'vk']" />
    </li>
    <li>
      <fa :icon="['fab', 'facebook-f']" />
    </li>
    <li>
      <fa :icon="['fab', 'instagram']" />
    </li>
    <li>
      <fa :icon="['fab', 'odnoklassniki']" />
    </li>
  </ul>
</template>
<style scoped lang="scss">
ul {
  list-style: none;
  display: flex;
  flex-direction: row;
  width: 200px;
  justify-content: space-evenly;
  align-items: center;
}
.icons-in-circle > li > svg {
  background: #b5beca;
  width: 20px;
  height: 20px;
  padding: 3px;
  border-radius: 50%;
}
</style>