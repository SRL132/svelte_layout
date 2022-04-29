<article class="card-container">
    <div class="card-header">
        <h3 class="plan-name">Entry</h3>
        <span class="plan-price">$14</span>
        <span class="plan-billing-cycle">/month</span> 
        <span class="plan-discount">10% OFF</span>
        <span class="plan-description">Easy start on the cloud</span>
    </div>
    <div>
        <ul class="card-items">
            <li class="card-list">Unlimited Websites</li>
            <li class="card-list">Unlimited Bandwidth</li>
            <li class="card-list">100 GB SSD Storage</li>
            <li class="card-list">3 GB RAM</li>
            
        </ul>
        <button class="card-button">BUY NOW</button>
    </div>

</article>


<style>

    .card-items{
        list-style-image: url('tick.svg');
        padding-left: 3rem;
        list-style: none;
        display: block;
        margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    padding-inline-start: 40px;
    font-size: 2rem;
    line-height: 1.5;
    text-align: left;
    }

    .plan-description{
        font-size: 2rem;
    font-weight: 300;
    letter-spacing: 1px;
    display: block;
    }

    .plan-discount{
        background: #02cdf1;
        font-size: 1.6rem;
    padding: 0.5rem 1.5rem;
    border-radius: 20px;
    white-space: nowrap;
    }

    .plan-price{
        font-size: 5rem;
    }

    .plan-billing-cycle {
    font-size: 2rem;
    font-weight: 300;
    opacity: 0.8;
    margin-right: 1rem;
    }

    .plan-name{
        font-weight: 500;
        font-size: 2.4rem;
        line-height: 1.3;
        display: block;

    }
    .card-container{
        max-width: 500px;
        border-radius: 7px;
        box-shadow: 0 0 20px 10px #f3f3f3;
        overflow: hidden;
        margin: 0 auto;
        transition: transform 0.2s ease-out;
        margin-bottom: 30px;
    }
    .card-header {
        background-color: #02D9FF ;
        color: #FFFFFF;
        padding: 2rem 7%;
        display: block;
        text-align: left;
        
       
    }

    .card-button{
        background-color: #FFFFFF;
        border-radius: 40px;
        cursor: pointer;
        font-size: 1.8rem;
        font-weight: 600;
        margin: 1rem 0;
        outline: 0;
        padding: 2rem 4vw;
        text-align: center;
        text-transform: uppercase;
        white-space: nowrap;
        color:1b0760;
        border: 2px solid #1B0760;



    }

    .card-list{
        color: #1B0760;
    }

    .card-list::marker{
        unicode-bidi: isolate;
    font-variant-numeric: tabular-nums;
    text-transform: none;
    text-indent: 0px !important;
    text-align: start !important;
    text-align-last: start !important;
        
    }

    .card-grid{
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        grid-gap: 1rem;
        align-items: flex-start;
    }

/* 
zoom image
<div class=card card card-shadow">
    <div class="card-header card-image">
        <img/>
    </div>

.card-header .card-image{
    overflow:hidden;
}
.card-header .card-image>img{
    display:block;
    width:100%;
    aspect-ratio:16/9;
    object-fit:cover;
    max-height:200px;
    object-position:center;
    transition: 200ms transform ease-in-out;
}

.card:hover> .card-image>img{
    transform:scale(1.1);
}
*/
</style>