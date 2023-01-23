<template>
    <div>
        <div>My Blog navigation bar here</div>
        <Nuxt />
    </div>
</template>

<script>
export default {
    layout: 'blog',
    // OR
    layout(context) {
        return 'blog'
    },
}
</script>