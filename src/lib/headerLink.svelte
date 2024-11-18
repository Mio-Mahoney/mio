<script lang="ts">
    export let href: string;
</script>

<div>
    <a
        class="relative hover:after:w-full hover:after:right-0 after:content-[''] after:absolute after:bottom-0 after:left-1/2 after:h-[2px] after:bg-black after:transition-all after:duration-300 after:ease-in-out after:transform after:-translate-x-1/2 after:w-0"
        {href}><slot></slot></a
    >
</div>
