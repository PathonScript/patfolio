<script>
	let age;
	setInterval(() => {
		let time =
			(new Date().valueOf() - new Date(1206837420000).valueOf()) / (1000 * 60 * 60 * 24 * 365.25); // milliseconds per year
		age = time.toString().substring(0, 12);
	}, 25);
</script>

<div class="flex items-center justify-center w-full h-screen flex-col bg-slate-400">
	<h1 class="text-7xl">Pat</h1>
	<h3 class="text-2xl">March 30th 2008</h3>
	<h4 class="text-2xl sm:text-4xl">
		<span class="text-blue-900">{age}</span>
		years old
	</h4>
</div>
