<template>
    <h3>插槽3再续</h3>
    <slot name="headerer" :msg="childMsg"></slot>
    <slot name="mainin" :job="jobMsg"></slot>
</template>

<script>
export default {
    name: 'slotszaixu',
    data() {
        return {
            childMsg:'hihihihi',
            jobMsg: '123456789hhhh'
        }
    }
}
</script>