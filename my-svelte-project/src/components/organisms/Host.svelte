<script>import HostCard from "../molecules/HostCard.svelte";
import HostCardReversed from "../molecules/HostCardReversed.svelte";
</script>
<section>
    <header class="block--header">
        <h2>Host on the Cloud to Keep Growing</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed, voluptatem.</p>
    </header>
<HostCard/>
<HostCardReversed/>
</section>

<style>
    .block--header {
        text-align: center;
        margin-bottom: 4rem;
    }
    h2 {
    font-size: 4rem;
    color: #1b0760;
    margin-bottom: 1rem;
    line-height: 1.1;
    font-family: Inter, Arial, Helvetica, sans-serif;
}
p{
    font-family: Inter, Arial, Helvetica, sans-serif;
    font-size: 1.7rem;
    line-height: 1.5;
    color: #918ca4;
    font-weight: 100;
}
</style>