<script setup lang="ts">
import { Analytics } from '@vercel/analytics/nuxt';

useHead({
  htmlAttrs: {
    lang: 'en', // 你的页面语言是en
  },
  title: '壁纸样机生成器 - 手机、平板、电脑样机模板工具',
  meta: [
    { charset: 'UTF-8' },
    { name: 'viewport', content: 'width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no' },
    { name: 'keywords', content: '壁纸样机、iPhone样机模板、iPad样机模板、Mac样机模板、小红书壁纸号、抖音壁纸号、壁纸模板工具、覆盖多平台' },
    { name: 'description', content: '一键生成 iPhone、iPad、Mac 锁屏和桌面壁纸样机模板的实用工具，可以通过该工具将壁纸套上 iPhone、iPad、Mac 锁屏/桌面样机模板，节省生成效果图的时间，简单易用，自定义设计壁纸样机模板。' },
  ],
  link: [
    { rel: 'icon', href: '/favicon.ico' }
  ]
})
</script>

<template>
  <Analytics />
  <NuxtLayout>
    <NuxtLoadingIndicator />
    <NuxtPage />
  </NuxtLayout>
</template>
