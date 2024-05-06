<script>
    import Card from './Card.svelte';

    const autoMinecartIcons = [
        { iconClass: "fab fa-github", href: "https://github.com/tisleo/AutoMinecart", title: "View on GitHub" },
        { iconClass: "fas fa-faucet", href: "https://www.spigotmc.org/resources/autominecart.101327/", title: "View on Spigot"},
        { iconClass: "fas fa-plane", href: "https://hangar.papermc.io/TisLeo/AutoMinecart", title: "View on Hangar"}
    ]

    const boredBotIcons = [
        { iconClass: "fab fa-github", href: "https://github.com/TisLeo/Bored-Bot", title:  "View on GitHub" },
        { iconClass: "fab fa-discord", href: "https://canary.discord.com/api/oauth2/authorize?client_id=959141306205081610&permissions=2147601472&scope=applications.commands%20bot", title: "Invite to Discord"}
    ]

    const mBBIcons = [
        { iconClass: "fab fa-github", href: "https://github.com/TisLeo/More-Beautiful-Buttons-Mod", title: "View on GitHub" },
        { iconClass: "fas fa-gavel", href: "https://www.curseforge.com/minecraft/mc-mods/more-beautiful-buttons-fabric", title: "View on CurseForge"},
    ]

    const jpadIcons = [
        { iconClass: "fab fa-github", href: "https://github.com/TisLeo/JPad", title: "View on GitHub"}
    ]

</script>

<section id="projects">
    <h2 class="title">Projects</h2>
    <p class="subtitle">The good stuff. More to come soon</p>

    <br>

    <div id="jpad">
        <Card
            title="⭐JPad⭐"
            description="A modern, lightweight and cross-platform text editor with built-in themes and syntax highlighting for 50+ languages. Currently in beta."
            src="https://imgur.com/fSu9U6t.png" alt="JPad logo"
            icons={jpadIcons}
            glow={true}
        />
    </div>

    <br>

    <div id="cards">
        <Card 
            title="Auto Minecart" 
            description="A useful Minecraft plugin that mimics Terraria minecarts." 
            src="https://i.imgur.com/7TjMOoF.png" alt="Auto Minecart plugin logo"
            icons={autoMinecartIcons}
        />
        <Card 
            title="Bored Bot" 
            description="A Discord bot written in Go to get something to do when you're bored!" 
            src="https://imgur.com/MQLha6s.png" alt="Bored bot logo"
            icons={boredBotIcons}
        />
        <Card 
            title="More Beautiful Buttons" 
            description="Over 200 vanilla Minecraft blocks craftable into buttons!" 
            src="https://i.imgur.com/OLLpMOh.png" 
            alt="Minecraft buttons"
            icons={mBBIcons}
        />    
    </div>
</section>

<style>
    #cards {
        gap: 2rem;
        display: flex;
        width: 100%;
        justify-content: space-evenly;
    }

    #jpad {
        width: 100%;
        justify-content: space-evenly;
    }

    @media only screen and (max-width: 640px) {
        #cards {
            gap: 2rem;
            display: flex;
            flex-direction: column;
            width: 100%;
            justify-content: space-evenly;
        }
    }
</style>