<nav class="navbar">
    <ul class="nav-container">
        <li class="nav push"><a href="/">Logo</a></li>
        <li class="nav"><a href="/">Home</a></li>
        <li class="nav"><a href="/notes">Notes</a></li>
        <li class="nav"><a href="/Search">Search</a></li>
    </ul>
</nav>

<style>
    .navbar {
        /* flex-grow:0;
        flex-shrink: auto; */
        background:rgb(73, 57, 113);
        padding: 12px;
    }
    .navbar ul {
        display:flex;
        gap:16px;
        justify-content: space-around;
    }


    .nav-container {
        list-style: none;
    }
    .nav {
        font-size: 1.5rem;
    }

    /* .nav.push {
        margin-right: auto;
    } */
    .nav a {
        text-decoration: none;
        color:white;
    }
    a:hover {
        color:orange
    }
</style>