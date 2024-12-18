<script lang="ts">
	import * as Card from "$lib/components/ui/card/index.js";

	import Skeleton from "./skeleton/index.svelte";
</script>

<Card.Root class="w-1/4 h-full z-50">
	<Card.Content class="h-full p-0 overflow-scroll [&::-webkit-scrollbar]:hidden [-ms-overflow-style:none] [scrollbar-width:none]">
		<Skeleton />
	</Card.Content>
</Card.Root>