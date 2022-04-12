<script>
	import Projects from './Project.svelte';
</script>

<div class="grid h-screen place-items-center">
	<h1 class="text-6xl">Portfolio</h1>
	<span class="grid-rows-3">
		<Projects
			name="Bob"
			image="image yeah"
			description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eu dolor velit. Nunc eu sollicitudin elit, ut venenatis eros. Morbi leo tortor, faucibus ut ligula sit amet, consectetur ornare orci. Suspendisse iaculis, diam in pharetra consectetur, justo urna porta lectus, eu rutrum ex nisi eu diam. Maecenas non rutrum leo, eget egestas nunc. Curabitur ultrices nunc id nisl scelerisque, eu sodales lacus scelerisque. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
		/>
		<Projects
			name="John"
			image="image yeah"
			description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eu dolor velit. Nunc eu sollicitudin elit, ut venenatis eros. Morbi leo tortor, faucibus ut ligula sit amet, consectetur ornare orci. Suspendisse iaculis, diam in pharetra consectetur, justo urna porta lectus, eu rutrum ex nisi eu diam. Maecenas non rutrum leo, eget egestas nunc. Curabitur ultrices nunc id nisl scelerisque, eu sodales lacus scelerisque. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
		/>
	</span>
</div>
