<script lang="ts">
	import { Button } from '$lib/components/ui/button';
	import * as Avatar from '$lib/components/ui/avatar';
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<Button>Click me</Button>

<Avatar.Root>
	<Avatar.Fallback>CN</Avatar.Fallback>
</Avatar.Root>
