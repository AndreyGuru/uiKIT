<template>
	<div>
		<button
			class="current-projects-new-projects-button"
			@click="$router.push('/add-project')"
		></button>
	</div>
</template>
<script>
export default {
	props: ['customName'],
}
</script>
<style>
.globalBtn {
	border-radius: 6px;
	font-size: 14px;
	font-weight: var(--font-w-regular);
	line-height: 20px;
	letter-spacing: 0;
	padding: 12px 16px;
	text-align: left;
	border: 1px solid rgba(232, 233, 234, 1);
	background-color: #0071da;
}
</style>
