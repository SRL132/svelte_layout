
<section class="block block--dark block--skewed-left hero">
    <div class="container grid grid--1x2">
        <header class="block__header hero__content">
            <h1 class="block__heading">Cloud Hosting for Pros</h1>
            <p class="hero__tagline">Deploy your websites in less than 60 seconds.</p>
            <a href=# class="btn btn--accent btn--stretched">Get Started</a>
        </header>
       
          <img class="hero__image" src="../images/banner.png" alt="" />
   
    </div>
</section>
<style>



.block {
  --padding-vertical: 5rem;
  padding: var(--padding-vertical) 2rem;
}

.block--dark {
  background: #000;
  color: #7b858b;
}
.block--dark h1
{
  color: #fff;
}
.block--skewed-left {
  padding-bottom: calc(var(--padding-vertical) + 4rem);
  clip-path: polygon(0% 0%, 100% 0%, 100% 95%, 0% 100%);
}
    .block__heading {
        font-size: 2.5rem;
        font-weight: 700;
        margin-bottom: 1rem;
    }
    .block__header {
  text-align: center;
  margin-bottom: 4rem;
}
    .container {
  max-width: 1140px;
  margin: 0 auto;
}
.grid {
  display: grid;
}

.btn {
  border-radius: 40px;
  border: 0;
  cursor: pointer;
  font-size: 1.8rem;
  font-weight: 600;
  margin: 1rem 0;
  outline: 0;
  padding: 2rem 4vw;
  text-align: center;
  text-transform: uppercase;
  white-space: nowrap;
}

@media screen and (min-width: 768px) {
  .grid--1x2 {
    grid-template-columns: repeat(2, 1fr);
  }
  .hero__content {
    text-align: left;
    align-self: center;
  }
}


    .hero__tagline {
  font-size: 2rem;
  color: #b9c3cf;
  letter-spacing: 1px;
  margin: 2rem 0 5rem;
}

.btn--accent {
  background: var(--color-accent);
  color: #fff;
}

.btn--accent:hover {
  background: #ec3000;
}

.btn--stretched {
  padding-left: 6rem;
  padding-right: 6rem;
}

@media screen and (min-width: 1024px) {
  .hero {
    padding-top: 0;
  }
}
</style>