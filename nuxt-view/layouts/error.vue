<template>
    <div>
        <h1 v-if="error.statusCode === 404">Error: 404 Not Foundだよ</h1>
    </div>
</template>

<script>
export default {
    props: ['error']
}
</script>
