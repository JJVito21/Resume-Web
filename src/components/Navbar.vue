<template>
    <div>
        <nav class="navbar navbar-expand-lg fixed-top">
            <div class="container">
                <img src="/portfolio1.png" alt="logo" style="width: 15rem; padding: 10px;">

                <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar"
                    aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar"
                    aria-labelledby="offcanvasNavbarLabel" style="background-color: #1F2833; width: 300px;">

                    <div class="offcanvas-header">
                        <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Offcanvas</h5>
                        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                    </div>

                    <div class="offcanvas-body">
                        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                            <li class="nav-item">
                                <a class="nav-link" aria-current="page" href="#" style="color: #C6C7C8;">Profile</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#about-me" style="color: #C6C7C8;">About Me</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#education" style="color: #C6C7C8;">Education</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#experience" style="color: #C6C7C8;">Experience</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#socials" style="color: #C6C7C8;">Socials</a>
                            </li>

                        </ul>

                    </div>

                </div>

            </div>
        </nav>
    </div>
</template>

<script setup>

</script>

<style scoped>
.navbar {
    background-color: #060606;
}
</style>