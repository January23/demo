<template>
  <div>{{x.name}}</div>
</template>

<script lang="ts" setup>
import { User} from '../entity/type';

const x:User = {name:'xxxx', age:1}

</script>

<style lang="scss" scoped>
</style>