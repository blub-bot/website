<script>
	let buttons = [
		{ name: 'roadmap', link: 'https://trello.com/b/bay8Yavw/blub-bot-roadmap' },
		{ name: 'github', link: 'https://github.com/blub-bot' },
		{ name: 'discord', link: 'https://discord.gg/FA8EhxjA9Z' }
	];
</script>

<ul>
	{#each buttons as button}
		<li><a href={button.link}><u>{button.name}</u></a></li>
	{/each}
</ul>

<style>
	ul {
		position: relative;

		color: #fff;
		padding: 10px;
		margin: 0;

		list-style-type: none;
	}

	li {
		text-align: center;
		display: inline;
		padding: 10px;
	}

	li a {
		color: #1e6783;
		text-decoration: none;

		font-size: clamp(2rem, 4vw, 3rem);
	}
</style>
