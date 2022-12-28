
<template>
    <div class="footer-wrapper">
        <div class="footer-section">
            <img src="../../public/logo.png" alt="logo">
        </div>
        <div class="footer-section">
            <h3>Reach Out</h3>
            <p>Email: nicostar26@yahoo.com</p>
            <p>Text: 910-691-9309</p>
        </div>
        <div class="footer-section">
            <h3>Socials</h3>
        </div>

    </div>

</template>


<style scoped>
h3 {
    color: #ac8c3c
}

.footer-wrapper {
    display: flex;
    width: 100%;
    justify-content: space-evenly;
    padding: 1rem;
    color: white;
}

.footer-section {
    width: 33%;
    padding: 1rem;
    text-align: center;
}

.footer-section img {
    height: 8rem;
    width: auto;
}
</style>