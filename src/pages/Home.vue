<template>
    <section>
        <div class="container text-white" id="profile">
            <h1 class="mt-3 prof" style="color: #C6C7C8;">Profile</h1>
            <hr style=" color: white;">

            <div class="mt-5">
                <div class="row">
                    <div class="col">
                        <img src="/grad 2.jpg" alt="image of me" style="width: 30rem; border-radius: 50px">
                    </div>
                    <div class="col type">
                        <p style="color: #C6C7C8; font-size: 20px; margin-bottom: 0">Hi my Name is,</p>
                        <p style="color: #FFFF88; font-size: 30px; margin-top: 0" class="fw-bold">Jian June F. Vito</p>
                        <h3 href="" class="typewrite" data-period="1000"
                            data-type='[ "Hi, Im Jian.", "I am a Computer Engineer.", "I Love to Code.", "I Love to Develop.", "I Love Vue." ]'>
                        </h3>
                        <p style="color: #C6C7C8; font-size: 20px; margin-top: 50px" class="fw-bold">Hey there, I'm Jian – a
                            budding programmer on a mission to transform innovative ideas into robust, functional code.</p>
                        <a href="#about-me">
                            <button class="bn53">Learn More</button>
                        </a>


                    </div>
                </div>
            </div>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>

        </div>
    </section>
</template>

<script setup>

</script>

<style scoped>
.prof {
    margin-top: 100px !important;
}

@media screen and (max-width: 750px) {
    .type {
        margin-top: 20px;
        margin-left: auto;
        margin-right: auto;
    }
}

.bn53 {
    background-color: #FFFF88;
    padding: 7px;
    width: 200px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    animation: bn53bounce 2s infinite;
    cursor: pointer;
}

@keyframes bn53bounce {

    5%,
    50% {
        transform: scale(1);
    }

    10% {
        transform: scale(1);
    }

    15% {
        transform: scale(1);
    }

    20% {
        transform: scale(1) rotate(-5deg);
    }

    25% {
        transform: scale(1) rotate(5deg);
    }

    30% {
        transform: scale(1) rotate(-3deg);
    }

    35% {
        transform: scale(1) rotate(2deg);
    }

    40% {
        transform: scale(1) rotate(0);
    }
}
</style>