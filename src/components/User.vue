<script>
export default {
    props: {
        UserInfo: Object,
    }
}
</script>


<template>
    <span class="user">
        <span class="name">{{ UserInfo.name }}</span>
        <span class="handle">{{ UserInfo.handle }}</span>
    </span>
</template>