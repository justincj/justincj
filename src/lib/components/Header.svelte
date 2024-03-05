<nav class="navbar">
    <ul class="nav-container">
        <li class="nav push"><a href="/">Logo</a></li>
        <li class="nav"><a href="/home">Home</a></li>
        <li class="nav"><a href="/notes">Notes</a></li>
        <li class="nav"><a href="/Search">Search</a></li>
    </ul>
</nav>

<style>
    .navbar {
        flex-grow:0;
        flex-shrink: auto;
    }
    .navbar ul {
        display:flex;
        gap:16px;
    }

    .nav-container {
        list-style: none;
        background:lightblue
    }
    .nav {
        font-size: 1.8rem;
    }

    .nav.push {
        margin-right: auto;
    }
    .nav a {
        text-decoration: none;
        color:black;
    }
    a:hover {
        color:orange
    }
</style>