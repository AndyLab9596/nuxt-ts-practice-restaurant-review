<template>
    <div>
        <slot name="header"
        ></slot>
        <div>
            <img src="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png" />
        </div>
        <slot name="redirectEl" ></slot>
    </div>
</template>

<style scoped >
img {
    width: 10rem;
}
</style>