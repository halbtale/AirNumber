<template>
    <div class="page-layout">
        <AppLogo></AppLogo>
        <AppQr></AppQr>
        <AppButton @click="$router.push({path:'/edit-contact'})">Edit Contact info</AppButton>
    </div>
</template>

<style lang="scss">
.page-layout {
    background-color: #FCFCFC;
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100%;
    width: 100%;
    padding: 1rem;
    display: grid;
    justify-content: center;
    align-content: flex-start;
}
</style>