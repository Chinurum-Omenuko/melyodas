<script>
	import LinkedIn from './LinkIcons/LinkedIn.svelte';
	import Tiktok from './LinkIcons/Tiktok.svelte';
	import Youtube from './LinkIcons/Youtube.svelte';
</script>

<header>
	<section id="logo">
		<h2>Logo</h2>
	</section>
	<nav>
		<li><a href="#">Home</a></li>
		<li><a href="#">Content</a></li>
		<li><a href="#">About</a></li>
		<li><a href="#">Contact</a></li>
	</nav>
	<section id="links">
		<li><a href="tiktok.com"><Tiktok /></a></li>
		<li><a href="youtube.com"><Youtube /></a></li>
		<li><a href="linkedin.com"><LinkedIn /></a></li>
	</section>
</header>

<style>
    header{
        display: flex;
        flex-direction: row;
        width: 100%;
        height: 5rem;
        background-color: rgb(24, 24, 24);
        justify-content: space-around;
        align-items: center;
    }

    #logo{
        width: calc(100% / 3);
        text-align: center;
    }


    nav {
        display: flex;
        justify-content: space-around;
        flex-direction: row;
        width: calc(100% / 3);
        text-align: center;
    }

    #links{
        display: flex;
        flex-direction: row;
        width: calc(100% / 3);
        justify-content: center;
    }

    #links li{
        margin: 0 2.5%;
    }

    li{
        list-style: none;
    }

    a, h2{
        text-decoration: none;
        color: whitesmoke;
    }
    
</style>