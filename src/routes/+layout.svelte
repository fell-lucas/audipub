<script>
	import { ParaglideJS } from "@inlang/paraglide-sveltekit";
	import { i18n } from "$lib/i18n";

	import "../app.css";
</script>

<div class="flex h-full items-center justify-center">
	<ParaglideJS {i18n}>
		<slot></slot>
	</ParaglideJS>
</div>
