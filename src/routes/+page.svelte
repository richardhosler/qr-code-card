<div class="card">
    <img src="../src/images/image-qr-code.png" alt="qr-code" />
    <div class="large-text">
        Improve your front-end skills by building projects
    </div>
    <div class="small-text">
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
    </div>
</div>
<div class="attribution">
    Challenge by <a
        href="https://www.frontendmentor.io?ref=challenge"
        target="_blank"
        rel="noreferrer">Frontend Mentor</a
    >.<br /> Coded by
    <a href="https://www.github.com/richardhosler">Richard Hosler</a>
</div>

<style>
    .card {
        position: absolute;
        border-radius: 1.5rem;
        width: min-content;
        display: grid;
        padding: 1rem;
        gap: 1rem;
        top: 50%;
        left: 50%;
        transform: translateY(-50%) translateX(-50%);
        background-color: white;
    }
    .attribution {
        position: absolute;
        bottom: 5px;
        text-align: center;
        width: 99.5%;
    }
    img {
        border-radius: 0.75rem;
        max-width: 300px;
    }
    .large-text {
        font-size: 1.5rem;
        text-align: center;
        font-weight: 700;
        margin-top: 0.5rem;
        color: hsl(218, 44%, 22%);
    }
    .small-text {
        font-size: 1.05rem;
        text-align: center;
        font-weight: 400;
        margin: 0.1rem;
        color: hsl(220, 15%, 55%);
        margin-bottom: 1rem;
    }
</style>
