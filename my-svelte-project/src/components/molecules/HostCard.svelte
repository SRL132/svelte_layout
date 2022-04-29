<article class="container">
    <div class="container-div">
        <img class="top-image" src="" alt="Image"/>
    <h3 class="host-title">Super easy to use</h3>
<p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam obcaecati vel ad unde est illo at. Labore excepturi officia dolores!
</p>
<a class="link" href="#">learn more</a>
</div>
<img class="image" src="" alt="Graph">
    
</article>


<style>

    .container{
        background-color: red;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    
    }

    .container-div{
        background-color: green;
    }

    .host-title{
        color: #1b0760;
        text-align: left;
    }

    .description{
        color: #918ca4;
        text-align: left;
    }

    .link{
        color: #ff3400;
        text-decoration: underline;
        text-decoration: none;
        text-transform: uppercase;
        font-size: 2rem;
        font-weight: bold;
        text-align: left;
    }

    .link::after {
    content: "-->";
    margin-left: 5px;
    transition: margin 0.15s;
}
    .top-image{
        text-align: left;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    @media (max-width: 768px) {
        .container{
            grid-template-columns: repeat(1, 1fr);
        }
    }
    .image{}
    /*https://youtu.be/9zBsdzdE4sM*/
</style>