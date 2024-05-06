<nav>
    <div id="items">
        <ul>
            <li class="title"><a href="/">Home</a></li>
            <li class="title"><a href="#tech">Tech</a></li>
            <li class="title"><a href="#projects">Projects</a></li>
            <li class="title"><a href="https://dev.to/tisleo">Blog</a></li>
        </ul>
    </div>

    <div id="icons">
        <ul>
            <li>
                <a title="Visit my GitHub!" href="https://github.com/TisLeo"
                    ><i class="fa-brands fa-github" /></a
                >
            </li>
        </ul>
    </div>
</nav>

<style>
    nav {
        list-style-type: none;
        background-color: black;
        display: flex;
        justify-content: space-between;
        top: 0;
        left: 0;
        width: 100%;
        position: sticky;
        align-items: center;
        height: 4rem;
        box-shadow: 0 4px 4px -2px rgba(255, 255, 255, 0.2);
        transition: 0.2s ease-in-out;
    }

    a {
        display: block;
        color: white;
        text-decoration: none;
        width: 100%;
        height: 100%;
    }

    li {
        display: inline-block;
    }

    #items {
        margin-left: 15%;
    }

    #icons {
        margin-right: 15%;
    }

    #icons a {
        padding: 0.8rem;
    }

    #items a {
        padding: 1rem;
    }

    a:hover {
        color: var(--color-accent);
        transition: 0.2s ease-in-out;
    }

    @media only screen and (max-width: 640px) {
        nav {
            position: fixed;
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            align-items: center;
            top: 0;
            left: 0;
            width: 100vw;
            height: 6rem;
        }

        #items,
        #icons {
            margin: 0;
        }

        #icons a {
            padding: 0.4em;
        }

        #items a {
            padding: 0.4em;
        }
    }
</style>
