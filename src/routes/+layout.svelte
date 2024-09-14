<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
	<a href="/contact">Contact</a>
</nav>

<style>
    nav {
        display: flex;
        justify-content: space-evenly;
        background-color: black;
        font-family: 'Courier New', Courier, monospace;
    }
    a {
        color: white;
    }
    a:hover {
        cursor: pointer; /* Change cursor to pointer on hover */
    }
</style>

<slot></slot>