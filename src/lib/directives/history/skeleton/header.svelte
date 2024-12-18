<script lang="ts">
	import { Skeleton } from "$lib/components/ui/skeleton/index.js";
</script>

<header class="flex flex-row justify-between items-center p-6">
	<Skeleton class="h-[30px] w-[100px]" />

	<div class="flex flex-row items-center gap-4">
		<Skeleton class="h-[20px] w-[100px]" />
		<Skeleton class="h-[40px] w-[40px] rounded-md" />
	</div>
</header>
