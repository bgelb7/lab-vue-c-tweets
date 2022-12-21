<script>
export default {
    props: {
        Mytimestamp: String,
    }
}

</script>

<template>

    <span class="timestamp">{{ Mytimestamp }}</span>

</template>

<style scope>
.timestamp {
    color: #536471;
    font-size: 1.1rem;
}

.timestamp::before {
    content: "·";
    padding-right: 0.3em;
    font-size: 1.1rem;
    font-weight: 600;
}
</style>