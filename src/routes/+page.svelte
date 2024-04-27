<script lang="ts">
	import { Calendar } from '$lib/components/ui/calendar/index.js';
	import type { DateValue } from '@internationalized/date';

	let value: DateValue[] = [];
</script>

<Calendar multiple bind:value />
