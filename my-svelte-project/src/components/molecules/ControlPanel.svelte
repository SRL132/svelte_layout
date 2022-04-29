<section class="panel-container">
    <h2>User-friendly Control Panel</h2>
    <div>
        <img src="images\banner.png" alt="Graph">
    </div>
    <div>
        <ul class="article-list">
            <li>
        <article class="media">
            <div class="media-body"><img class="media-image" src="" alt="icon"></div>
            <div>
            <h3 class="panel-title">
                Easy Start & Managed Updates
            </h3>
            <p class="panel-description">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam quisquam, ex nostrum vero voluptates dicta excepturi vel perspiciatis consequuntur ab.
            </p></div>
        </article>
    </li>
    <li>
        <article class="media">
            <div class="media-body"><img class="media-image" src="" alt="icon"></div>
            <div><h3 class="panel-title">
                Staging, GIT & WP-CLI
            </h3>
            <p class="panel-description">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam quisquam, ex nostrum vero voluptates dicta excepturi vel perspiciatis consequuntur ab.
            </p></div>
            
        </article>
    </li>
    <li>
        <article class="media">
            <div class="media-body"><img class="media-image" src="" alt="icon"></div>
            <div>
            <h3 class="panel-title">
                Dynamic Caching & More
            </h3>
            <p class="panel-description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam quisquam, ex nostrum vero voluptates dicta excepturi vel perspiciatis consequuntur ab.</p>
        </div>
    </article>
    </li>
    </ul>
    </div>

    
</section>

<style>
.panel-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    background-color: black;
    color: white;
}

.panel-description{
    text-align: left;
    color: #7b858b;
    display: block;
    background-color: brown;
}

.panel-title{
    text-align: left;
    font-size: 2rem;
}

.article-list{
    list-style: none;
    background-color: #1b0760;
}

.media{
    display: grid;
    grid-template-columns: 1fr 9fr;
    margin-bottom: 4rem;
}

.media-image{
    margin-top: 1rem;
}

.media-body{
    margin: 0 2rem;
    display: block;
    text-align: center;
}
</style>