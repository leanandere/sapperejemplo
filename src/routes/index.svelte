<script>
	import sadlion from 'images/lionsad.jpg';
</script>

<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Ejemplo de Proyecto Sapper</title>
</svelte:head>

<h1>Sapper ejemplo</h1>

<figure>
	<img alt="Sad Lion" src="{sadlion}">
	<figcaption>Diviertete con Sapper </figcaption>
</figure>

<p><strong> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sed quas, dicta quaerat dolor quasi quibusdam rerum ullam aliquid sapiente incidunt aperiam nulla impedit labore ipsa perspiciatis ratione assumenda eligendi eum.</strong></p>
