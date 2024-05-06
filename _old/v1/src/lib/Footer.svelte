<footer>
    <img src="https://i.imgur.com/dm1SddH.png" alt="TisLeo Logo" />
    <p>© TisLeo 2023</p>
    <br />
    <div id="items">
        <ul>
            <li class="title"><a href="/">Home</a></li>
            <li class="title"><a href="#tech">Tech</a></li>
            <li class="title"><a href="#projects">Projects</a></li>
            <li class="title"><a href="https://dev.to/tisleo">Blog</a></li>
        </ul>
    </div>
</footer>

<style>
    footer {
        background-color: black;
        height: 12rem;
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin: 2.5rem 0 0 0;
    }

    img {
        border: 2px solid var(--color-light-grey);
        border-radius: 50px;
        height: 4em;
        width: 4em;
    }

    p {
        color: var(--color-light-grey);
    }

    #items li:not(:last-child),
    #items li:not(:first-child) {
        padding: 0 0.5em 0 0.5em;
    }

    a {
        display: block;
        color: white;
        text-decoration: none;
        width: 100%;
        height: 100%;
    }

    a:hover {
        color: var(--color-accent);
        transition: 0.2s ease-in-out;
    }

    li {
        display: inline-block;
    }
</style>
