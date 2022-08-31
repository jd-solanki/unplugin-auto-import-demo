<script setup>
// const avatar1 = dynamicImgImport('@/assets/images/avatars/avatar-1.png')
</script>

<template>
    <!-- <img :src="avatar1" alt="avatar"> -->
    <img :src="dynamicImgImport('@/assets/images/avatars/avatar-1.png')" alt="avatar" />
    <!-- <img :src="dynamicImgImport('@/assets/images/avatars/avatar-2.png')" alt="avatar" /> -->
</template>
