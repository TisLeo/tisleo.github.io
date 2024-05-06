<section>
    <h1 class="title">TisLeo</h1>
    <h2 class="title" style="color: white;">Welcome to my page!</h2>

    <br><br>

    <h3>Hi! My name is Leo. I'm a computer science student from the UK and I love to code small projects in my spare time. I mostly
        prefer backend, but sometimes I do frontend too (such as this website). Stick around for some cool projects!</h3>    
</section>

<style>
    section {
        margin-top: 4rem;
    }

    @media only screen and (max-width: 640px) {
        section {
            margin-top: 8rem;
        }
    }

    h1 {
        background: linear-gradient(45deg, #65efea, #387fc5, #2933be);
        background-size: 200% 200%;
        animation: gradient 4s ease infinite;
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        padding: 0 2em 0 2em;
    }

    @keyframes gradient {
        0% {
            background-position: 0% 50%;
        }
        50% {
            background-position: 100% 50%;
        }
        100% {
            background-position: 0% 50%;
        }
    }

    h2 {
        color: var(--color-accent)
    }

    h3 {
        text-align: center;
        font-weight: 400;
    }
</style>