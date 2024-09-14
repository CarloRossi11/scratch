<script>
    // let fontClass = 'font-default';
</script>

<div class="body">
    <div class="header">
        <h1>Classes</h1>
        <p>Want to learn the art of cooking without having to go to culinary shcool? Look no further!</p>
    </div>

    <div class="iframe-container">
        <iframe src="/Cooking Classes.pdf" width="100%" height="100%" title="Cooking Classes"></iframe>
    </div>
</div>

<style>
    .body {
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        flex-direction: column;
        height: 100vh; /* Ensure the body takes up the full viewport height */
    }
    .header {
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .iframe-container {
        width: 80%; /* Adjust as needed */
        height: 80vh; /* Adjust as needed */
        display: flex;
        justify-content: center;
        align-items: center;
    }
    iframe {
        width: 100%;
        height: 100%;
        border: none; /* Remove border for a cleaner look */
    }
</style>