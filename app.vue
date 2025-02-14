<template>
  <div class="flex flex-row justify-start items-stretch">
    <UVerticalNavigation :links="links" class="w-1/3"/>
    <NuxtLayout>
      <NuxtPage class="flex-grow"/>
    </NuxtLayout>
  </div>
</template>
<script lang="ts" setup>
const links = [
  {
    label: '言语分析',
    icon: 'i-heroicons-home',
    to: '/speech_analyse'
  },
  {
    label: '判断推理',
    icon: 'i-heroicons-home',
    to: '/judgment_research'
  },
  {
    label: '数量资料分析',
    icon: 'i-heroicons-home',
    to: '/data_analyse'
  },
  {
    label: '申论',
    icon: 'i-heroicons-home',
    to: '/essay'
  },
];
</script>
