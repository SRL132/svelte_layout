<script>

  let active=false;

  function handleToggle () {
    console.log(active);
		active = !active;
	}

</script>



<nav class="navbar">
  <div>
    <h1 class="brand-title">LOGO</h1>
  </div>
  <a class="toggle-button" href="#" on:click="{()=>handleToggle()}">
  <span class="bar"></span>
  <span class="bar"></span>
  <span class="bar"></span>
  </a>
  
  {#if active}
  <div class="navbar-links">
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/">About</a></li>
      <li><a href="/">Contact</a></li>
    </ul>

  </div>
  {/if}

</nav>

<style>


  .navbar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    color: white;
  }
  
  .brand-title{
    font-size: 1.5rem;
    margin: .5rem;
  }
  
  .navbar-links ul{
    margin:0;
    padding:0;
    display:flex;
  
  
  }
  .navbar-links li{
    list-style: none;
  
  }
  
  .navbar-links li a {
    text-decoration: none;
    color: white;
    padding:1rem;
    display: block;
  
  }
  
  .navbar-links li:hover{
    background-color: #555;
  
  
  }
  
  .toggle-button{
    position:absolute;
    top:1rem;
    right:1rem;
    display: none;
    flex-direction: column;
    justify-content: space-between;
    width: 30px;
    height: 21px;
  
  }
  
  .toggle-button .bar{
    height: 3px;
    width: 100%;
    background-color: white;
    border-radius: 10px;
  }
  
  @media screen and (max-width: 400px) {
    .navbar{
      flex-direction: column;
      align-items: flex-start;
    }
    .navbar-links{
      display: flex;
      width: 100%;
    }
  
    .navbar-links.active{
      display: flex;
    }
  
    .navbar-links ul{
      width: 100%;
      flex-direction: column;
    }
  
    .navbar-links li{
      text-align: center;
    }
    .navbar-links li a{
      padding: .5rem 1rem;
    }
    .toggle-button{
      display: flex;
    }
  }
  
  </style>


