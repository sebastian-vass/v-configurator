<script setup lang="ts">
import { Label } from 'radix-vue'
</script>

<template>
  <div class="flex flex-wrap items-center gap-[15px] px-5">
    <Label
      class="text-[15px] font-semibold leading-[35px]"
      for="firstName"
    > Enter API key</Label>
    <input
      id="api-key"
      class="bg-blackA5 shadow-blackA9 inline-flex h-[35px] w-[320px] appearance-none items-center justify-center rounded-[4px] px-[10px] text-[15px] leading-none shadow-[0_0_0_1px] outline-none focus:shadow-[0_0_0_2px_black] selection:color-white selection:bg-blackA9"
      type="text"
      value="aaabbbccc-1234-abcd-5678-eee222ccc"
    >
  </div>
</template>
