<template>
	<ContentRenderer :value="page"/>
</template>

<script lang="ts" setup>
const {page} = useContent();
</script>