<template>
  <Menu mode="horizontal" theme="dark">

    <router-link to="/">

      <MenuItem name="1">

        <Icon type="md-home"></Icon>主页

      </MenuItem>

    </router-link>

    <router-link to="/">

      <MenuItem name="2">

        <Icon type="ios-videocam"></Icon>电影

      </MenuItem>

    </router-link>

    <router-link to="/">

      <MenuItem name="2">

        <Icon type="ios-document"></Icon>影评

      </MenuItem>

    </router-link>

  </Menu>

</template>

<script>
    export default {
        name: "IndexHeader"
    }
</script>

<style scoped>

</style>
