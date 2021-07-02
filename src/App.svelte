<script>
	//import pages
	import Start from './Auth/Start.svelte'
	import Signup from './Auth/Signup.svelte'
	import Home from './Pages/Home.svelte'
	//import store data
	import {loggedIn} from './stores.js'



</script>


{#if $loggedIn}
<Home/>

{:else}

<Signup/>
{/if}