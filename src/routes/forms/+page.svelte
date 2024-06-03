<script>
import { page } from '$app/stores';
	import { onMount } from 'svelte';
</script>

<svelte:head>
	<title>Forms</title>
	<meta name="description" content="Links to club forms" />
</svelte:head>

<div class="text-column">
	<h1>Forms we're currently using at the club: </h1>

	<ul>
		<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
			<a href="https://docs.google.com/spreadsheets/d/13REvPHGyDX5uEplTYiylPOpo-E4ihlXmkQB8qEqBhCI/edit?resourcekey#gid=79133655">Current boat bookings</a>
		</li>

		<li aria-current={$page.url.pathname === 'https://forms.gle/G2mtoWffu2HaHv5P7' ? 'page' : undefined}>
		<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSfAA4ddIz9ByFTDdgnPnIHHSW5gomu9quSDmQ7iM1ooMlzNZA/viewform?embedded=true" width="640" height="1248" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
		</li>
	</ul>
</div>
