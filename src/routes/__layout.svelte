<script>import {onMount} from 'svelte';import {goto} from '$app/navigation';onMount(()=>{window.goto=goto;})</script>
<slot/>