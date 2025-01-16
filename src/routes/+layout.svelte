<svelte:head>
	<link rel="stylesheet" href="/main.css" />
	<meta
		name="description"
		content="Dan is just this guy, you know?"
	/>
	<meta property="og:type" content="website" />
	<meta
		property="og:image"
		content=""
	/>
	<meta
		property="og:description"
		content="Dan is just this guy, you know?"
	/>
</svelte:head>

<div id="header">
	<div id="logo">
		Header
	</div>
</div>

<div id="content">
	<slot />
</div>

<div id="footer">
	<em>This site is Open Source.</em> Want to make an improvement?
	<a href="https://github.com/slifty/resume/">Open a PR</a>.
</div>

<style>
</style>
