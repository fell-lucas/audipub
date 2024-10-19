<script>
	import Input from "$lib/components/ui/input/input.svelte";
	import Label from "$lib/components/ui/label/label.svelte";
	import * as m from "$lib/paraglide/messages.js";
</script>

<div class="grid w-full max-w-sm items-center gap-1.5">
	<Label for="picture">{m.upload_ebook()}</Label>
	<Input id="picture" type="file" />
</div>
