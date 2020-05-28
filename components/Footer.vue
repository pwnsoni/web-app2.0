<template>
    <div>
        <p class="footer">
        Made with <font-awesome-icon :icon="['fas', 'heart']"/> by nuxt
        </p>
    </div>
</template>

<style>
.footer{
    color: #3b8070;
    text-align: center;
    font-size: calc(7.7px + (18 - 7.7) * ((100vw - 300px) / (1600 - 300)));
}
</style>