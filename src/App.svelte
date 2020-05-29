<script>
	import { Router, Route } from "svelte-routing";
	import Home from './views/Home.svelte';
	import Header from './components/Header.svelte';
	export let url = "";
</script>

<Router url="{url}">
	<Header />
    <Route path="/" component="{Home}" />
</Router>