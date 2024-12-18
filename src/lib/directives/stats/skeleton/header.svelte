<script lang="ts">
	import { Skeleton } from "$lib/components/ui/skeleton/index.js";
</script>

<header class="flex flex-row justify-between items-center">
	<Skeleton class="h-[30px] w-[200px]" />

	<div class="flex flex-row items-center gap-4">
		<Skeleton class="h-[40px] w-[100px]" />
		<Skeleton class="h-[40px] w-[150px]" />
		<Skeleton class="h-[40px] w-[40px] rounded-full" />
	</div>
</header>
