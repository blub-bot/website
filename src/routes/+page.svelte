<script>
	import '../app.css';

	import Desc from '../components/Desc.svelte';
	import Navbar from '../components/Navbar.svelte';
</script>

<svelte:head>
	<title>blub. discord bot : coming soon</title>
</svelte:head>


<!--For galaxy fold because icky-->
<h3 id="not-avail">not available</h3>

<!--Header-->
<div class="header" style="margin-top: 0;">
	<img src="/images/blub.png" alt="blub" style="width:25rem; padding:0;">
	<h1 id="header">blub<span style="letter-spacing:0;">.</span></h1>
</div>

<!--Coming Soon Text-->
<h3 id="coming-soon">coming soon.</h3>

<!--What is blub-->
<h1 id="what-is">what is blub?</h1>

<!--Description-->
<Desc />

<!--"Navbar"-->
<Navbar />

<style>
	#header {
		top: 0;
		margin: auto;
		margin-inline: auto;
		width: 100%;

		font-size: clamp(4rem, 13vw, 16rem);
		line-height: 265px;
		letter-spacing: clamp(3rem, 15vw, 20rem);
	}

	#coming-soon, #not-avail {
		font-size: clamp(3rem, 7vw, 8rem);
		margin: auto;
		margin-inline: auto;
	}

	#what-is {
		font-size: clamp(2rem, 5vw, 4rem);
		text-decoration: underline;
	}

	#not-avail {
		visibility: hidden;
	}

	@media only screen and (max-width: 340px) {

		#not-avail {
			visibility: visible;
		}

	}
</style>
