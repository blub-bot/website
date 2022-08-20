<script>
	import '../app.css';

	import Desc from '../components/Desc.svelte';
	import Navbar from '../components/Navbar.svelte';
	import Blub from '../components/Blub.svelte';
</script>

<svelte:head>
	<title>blub. discord bot : coming soon</title>
</svelte:head>

<!--Header-->
<h1 id="header">blub<span style="letter-spacing:0;">.</span></h1>

<!--Coming Soon Text-->
<h3 id="coming-soon">coming soon.</h3>

<!--What is blub-->
<h1 id="what-is">what is blub?</h1>

<!--Description-->
<Desc />

<!--"Navbar"-->
<Navbar />

<Blub />

<style>
	#header {
		top: 0;
		margin: 0;

		font-size: clamp(5rem, 13vw, 16rem);
		line-height: 265px;
		letter-spacing: clamp(3rem, 15vw, 20rem);
	}

	#coming-soon {
		font-size: clamp(3rem, 7vw, 8rem);
		margin: 0;
	}

	#what-is {
		font-size: clamp(2rem, 5vw, 4rem);
		text-decoration: underline;
	}
</style>
