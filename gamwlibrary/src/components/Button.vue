<template>
    <button>Submit</button>
</template>

<style lang="scss">
    button {
        background: $main-button-color;
        color: $main-text-color;

        transition: 0.4s all ease-in-out;

        &:hover {
            background: $hover-button-color;
            color: $hover-text-color;
        }
    }
</style>