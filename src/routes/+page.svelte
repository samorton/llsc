<script>
	import Counter from './Counter.svelte';
	import fb1 from '$lib/images/sailing_club/Facebook Banner v1.jpg';
	import fb2 from '$lib/images/sailing_club/Facebook Banner v2.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Clwb Hwylio Y Llanfairfechan / Llanfairfechan Sailing Club" />
</svelte:head>

<section>
	<h1>
		<span class="welcome">
			<picture>
				<img src={fb2} alt="Welcome" />
			</picture>
		</span>
    <br />
        to Clwb Hwylio Y Llanfairfechan
	</h1>

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
	}

	/*.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}*/
</style>
