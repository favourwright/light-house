<template>
  <Header />
  <slot></slot>
  <BottomNav />
</template>

<script setup>
import Header from '@/components/Header'
import BottomNav from '@/components/BottomNav'
</script>