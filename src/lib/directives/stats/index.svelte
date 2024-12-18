<script lang="ts">
	import * as Card from "$lib/components/ui/card/index.js";

	import Skeleton from "./skeleton/index.svelte";
</script>

<Card.Root class="w-2/3 h-full z-50">
	<Card.Content class="flex h-full flex-1 flex-col">
		<Skeleton />
	</Card.Content>
</Card.Root>
