<script>
	import Contact from '$lib/Contact.svelte';
import Navbar from '$lib/Navbar.svelte';
	import Rudi from '$lib/Rudi.svelte';
import '../app.css';
	let { children } = $props();
</script>
<Navbar/>
{@render children()}
<Rudi/>
<Contact/>