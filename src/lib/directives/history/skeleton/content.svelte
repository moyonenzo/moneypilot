<script lang="ts">
	import { Skeleton } from "$lib/components/ui/skeleton/index.js";
</script>

<div class="flex flex-col gap-5 mt-1 pl-6 pr-6">
	<div class="flex flex-row justify-between items-center">
		<div class="flex flex-row gap-2 item-center">
			<Skeleton class="h-[20px] w-[40px]" />
			<Skeleton class="h-[20px] w-[100px]" />
		</div>
		<Skeleton class="h-[20px] w-[60px]" />
	</div>

	<div class="flex flex-row justify-between items-center">
		<div class="flex flex-row gap-2 item-center">
			<Skeleton class="h-[20px] w-[40px]" />
			<Skeleton class="h-[20px] w-[80px]" />
		</div>
		<Skeleton class="h-[20px] w-[60px]" />
	</div>

	<div class="flex flex-row justify-between items-center">
		<div class="flex flex-row gap-2 item-center">
			<Skeleton class="h-[20px] w-[40px]" />
			<Skeleton class="h-[20px] w-[140px]" />
		</div>
		<Skeleton class="h-[20px] w-[60px]" />
	</div>

	<div class="flex flex-row justify-between items-center">
		<div class="flex flex-row gap-2 item-center">
			<Skeleton class="h-[20px] w-[40px]" />
			<Skeleton class="h-[20px] w-[100px]" />
		</div>
		<Skeleton class="h-[20px] w-[60px]" />
	</div>
</div>
