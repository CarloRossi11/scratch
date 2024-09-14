<div class="header">
    <h1>PhooD</h1>
    <p>scratch - made - experiences</p>
</div>
<div class="body">
    <div class="buttons">
        <a href="/private-dining" class="btn btn1">Private Dining</a>
        <a href="/classes" class="btn btn2">Classes</a>
        <a href="/catering" class="btn btn3">Catering</a>
    </div>
</div>

<style>
    :global(body) {
        font-family: 'Courier New', Courier, monospace;
    }

    .header, .body {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .header {
        padding-top: 3%;
        padding-bottom: 3%;
    }

    h1 {
        font-size: 3rem;
    }

    .buttons {
        display: flex;
        width: 100%;
        height: 250px;
        background-color: black;
        flex-direction: row;
        justify-content: space-evenly;
    }

    .btn {
        width: calc(25% - 10px); /* Adjusts each button to take up 1/3 of the container width, accounting for 10px total margin */
        margin: 5px; /* Adds a small margin around each button */
        box-sizing: border-box; /* Ensures padding and border are included in the width calculation */
        display: flex;
        justify-content: center;
        align-items: center;
        padding: 10px 20px;
        border-radius: 25px;
        background-color: white;
        color: black;
        border: none;
        cursor: pointer;
        font-family: 'Courier New', Courier, monospace;
        transition: background 0.5s ease, transform 0.5s ease; /* Smooth transition for background and zoom */
        overflow: hidden; /* Prevents any overflow from the scaling effect */
        position: relative; /* Needed for proper scaling effect */
    }

    .btn:hover {
        transform: scale(1.1); /* Zoom effect */
        color: transparent; /* Makes the button text invisible on hover */
        cursor: pointer; /* Change cursor to pointer on hover */
    }

    .btn1:hover {
        background: url('/private.jpg') no-repeat center center;
        background-size: cover;
    }

    .btn2:hover {
        background: url('/classes.jpg') no-repeat center center;
        background-size: cover;
        cursor: pointer; /* Change cursor to pointer on hover */
    }

    .btn3:hover {
        background: url('/cater.jpg') no-repeat center center;
        background-size: cover;
    }

    .btn:hover::before {
        position: absolute;
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        color: black; /* Text color */
    }

    a {
        color: white;
    }
    a:hover {
        cursor: pointer; /* Change cursor to pointer on hover */
    }
</style>

<slot></slot>