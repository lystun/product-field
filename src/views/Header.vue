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
                    <a class="nav-link" href="#attend">Why attend?</a>
                    <a class="nav-link" href="#speakers">Speakers</a>
                    <a class="nav-link" href="#schedule">Schedule</a>
                    <a class="nav-link" href="#join">Join</a>
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

        padding: 1.2rem 0rem;
        background: #000;
        border: 0;
        
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

    
    @media screen and (max-width: 576px) {
        
        .navbar {

            padding: 1.2rem 1rem;
            
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
    }
       
    @media screen and (min-width: 576px) and (max-width: 767px){}
    @media screen and (min-width: 768px) and (max-width: 992px){}
    @media screen and (min-width: 992px) and (max-width: 1200px){}
</style>