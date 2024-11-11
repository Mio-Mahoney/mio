<script lang="ts">
	import "../app.css";
	let { children } = $props();
	export const prerender = true;
	export const ssr = true;
	export const trailingSlash = "ignore";
</script>

{@render children()}
