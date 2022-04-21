<script>
    export let content="Learn more";
    export let href="#";
</script>

<a {href}>{content}</a>

<style>
a{
    color: var(--color-accent);
    text-transform: uppercase;
    text-decoration: none;
    font-size: 2rem;
    font-weight: bold;
}
a::after{
    content: '-->';
    margin-left: 5px;
    transition: margin 0.15s;
}

a:hover::after{
    margin-left: 10px;

}

@media screen and (min-width: 1024px) {
    a{
        font-size: 1.5rem;
    }
}
</style>
