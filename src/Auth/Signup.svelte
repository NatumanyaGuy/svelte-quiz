<script>
//import store data
import {loggedIn} from "../stores.js";

function logIn(){
loggedIn.set(true)
}

</script>

SignUp 

<button on:click="{logIn}">SignUp</button>