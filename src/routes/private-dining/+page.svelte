<script>
    // let fontClass = 'font-default';
</script>

<div class="body">
    <div class="header">
        <h1>Private Dining</h1>
        <p>Impress your friends and family without all the hassle. Shane will come out to you, or host you and your friends to a delectible dining experience.</p>
    </div>

    <div class="iframe-container">
        <iframe src="/Menu _July 24.pdf" width="100%" height="100%" title="Menu for July 24"></iframe>
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