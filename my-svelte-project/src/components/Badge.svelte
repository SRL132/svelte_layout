<script>
    export let content="10% Off";
</script>

<span class="badge badge--primary">{content}</span>

<style>
    .badge{
        border-radius: 20px;
        font-size: 2rem;
        font-weight: bold;
        padding: 0.5rem 2rem;
        white-space: nowrap;
    }

    .badge--primary{
        background: var(--color-primary);
        color: #fff;
    }

    .badge--secondary{
        background: var(--color-secondary);
        color: #fff;
    }

    .badge--small{
        font-size: 1.6rem;

    }

    @media screen and (min-width: 1024px){
        .badge{
            font-size: 1.5rem;
        }
    }
</style>