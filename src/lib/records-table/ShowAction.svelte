<script lang="ts">
    import icon from "./icons/plus.svg?raw";
    import { Link } from "$lib/link";
    export let href: string;
</script>

<Link {href} class="show" title="visualizar registro">
    {@html icon}
</Link>