<script>
    import Logo from "$lib/images/logo.svg";
</script> 

<header>
    <a href="/">
        <img src={Logo} alt="Logo" />
    </a>    
    <div class="header__nav">
        <a href="/search">Search</a>
        <a href="/watchlist">Watchlist</a>
        <a href="/login">Log In</a>
    </div>
</header>

<style>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100px;
        max-width: var(--column);
        padding: 0 var(--side);
        color: var(--accent);
    }

    img {
        height: 1rem;
    }

    .header__nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    a {
        text-decoration: none;
        color: inherit;
    }

    .header__nav a {
        margin-left: 1rem;
    }
</style>

