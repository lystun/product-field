<template>
    <nav class="navbar navbar-expand-lg">
        <div class="container mx-auto">
            <a class="navbar-brand" href="#">
                <img src="../assets/logo.png" alt="Ennovate Lab" class="img-fluid">
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ml-auto">
                    <a class="nav-link active" aria-current="page" href="#">Why attend?</a>
                    <a class="nav-link" href="#">Speaker</a>
                    <a class="nav-link" href="#">Schedule</a>
                    <a class="nav-link" href="#">Join</a>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>
    export default {

    }
</script>

<style lang="scss">
  
    .navbar {

        // padding: 1.2rem 10rem;
        padding: 1.2rem 0rem;
        background: #000;
        
        &-brand {
            img {
                width: 10rem;
            }
        }

        &-nav {

            .nav-link{
                color: #fff;

                &:hover {
                    color: #FFc83d;
                }
            }
        }
    }
</style>