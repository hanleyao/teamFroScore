<template>

</template>

<script>
import adminSetting from "./model/admin-setting-model";
import VmUpload from "./model/upload-model";
import editInfo from "./model/admin-edit-model";

export default {
    inject: ["reload"],
    name: "dashboard",
    data() {
        this.pieSetting = {
            offsetY: 150,
            radius: 90,
            labelLine: {
                length: 8,
                smooth: false,
            },
        };
        return {

        };
    },
    methods: {

    components: {

    },
}}
;
</script>

<style scoped>

</style>
