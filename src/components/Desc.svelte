<script>

    let feats = [
        "leaderboards, ",
        "games, ",
        "and more!"
    ]

</script>

<p>
    blub. will be a Discord bot that is made to help
    engage members of your Discord by
    offering things such as 
    {#each feats as feat}
        {feat}
    {/each}
</p>

<style>

    p {
        margin-top: 1rem;
        margin-bottom: 1rem;
        padding-left: 5rem;
        padding-right: 5rem;

        font-size: clamp(1.4rem, 2.4vw, 2.5rem);
    }

</style>