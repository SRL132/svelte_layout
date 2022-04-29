<section class="container block-domain">
    <header class="block__header">
    <h2 class="domain-header">Starting at $9 per month</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti, exercitationem?</p>
</header>
<div class="input-group">
    <input placeholder="Enter domain name here" class="input" type="text"><button class="btn btn--accent btn--stretched">Search</button>
</div>
    <ul class="list block-domain__prices">
        <li><span class="badge badge--secondary">.com $9</span></li>
        <li>.sg $10/li</li>
        <li>.space $11</li>
        <li>.info $14</li>
        <li>.net $10</li>
        <li>.xyz $10</li>
    </ul>
</section>
<style>
.container{
    background-color: #FFFFFF;
}

    .domain-header{
        color:#1B0760;
    }

    p{
        color:#919AC4;
    }

    ul{
        display: flex;
        justify-content: space-between;
    }
    li{
        color:#1B4AA8;
        list-style: none;
    }

    .block-domain__prices {
  color: var(--color-headings);
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(2, 6rem);
  font-size: 2rem;
  font-weight: 600;
  justify-items: center;
  max-width: 700px;
  margin: 0 auto;
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

.btn--stretched {
  padding-left: 3rem;
  padding-right: 3rem;
}

.btn--accent {
  background: var(--color-accent);
  color: #fff;
}

.btn--accent:hover {
  background: #ec3000;
}
.input {
  border-radius: var(--border-radius);
  border: 1px solid var(--color-border);
  color: var(--color-headings);
  font-size: 2rem;
  outline: 0;
  padding: 1.5rem 3.5rem;
}
::placeholder {
  color: #cdcbd7;
}

.input-group {
  border: 1px solid var(--color-border);
  border-radius: var(--border-radius);
  display: flex;
}

.input-group .input {
  border: 0;
  flex-grow: 1;
  padding: 1.5rem 2rem;
  width: 0;
}

.input-group .btn {
  margin: 4px;
}
.block-domain .input-group {
  box-shadow: 0 0 30px 20px #e6ebee;
  border: 0;
  margin: 4rem auto;
  max-width: 670px;
}

.badge {
  border-radius: 20px;
  font-size: 2rem;
  font-weight: 600;
  padding: 0.5rem 2rem;
  white-space: nowrap;
}
.badge--secondary {
  background: var(--color-secondary);
  color: #fff;
}

@media screen and (min-width:1024px){
    .input{
        font-size: 1.5rem;
    }
}

@media screen and (min-width: 768px) {
  .block-domain__prices {
    grid-template-columns: repeat(auto-fit, minmax(10rem, 1fr));
  }
}
</style>