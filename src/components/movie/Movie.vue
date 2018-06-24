<template>
    <div>
        <common-header>Header</common-header>
        <div>content</div>
        <common-footer>Footer</common-footer>
    </div>
</template>

<script>
    import CommonHeader from '@/components/common/Header'
    import CommonFooter from '@/components/common/Footer'
    export default {
        components: {
            CommonHeader,
            CommonFooter
        }
    }
</script>

<style scoped>

</style>
