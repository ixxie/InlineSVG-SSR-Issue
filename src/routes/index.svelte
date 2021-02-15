<script>
    import InlineSVG from 'svelte-inline-svg'
</script>

<svelte:head>
	<title>InlineSVG SSR Issue</title>
</svelte:head>

<h1>Great failure!</h1>

<figure>
	<InlineSVG src='../test.svg'/>
	<figcaption>Behold - error!</figcaption>
</figure>