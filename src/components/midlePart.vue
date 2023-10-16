<template>
    <div id="projets">
        <section class="images">
            <h2>Projets</h2>
            <div class="image-card">
                <div class="image-left">
                    <a href="https://dvic.devinci.fr/projects/interactive-pool/project/sleep-mode"><img src="../assets/sleepmode.jpg" alt="avocat" /></a>
                </div>
            

                <div class="image-right">
                    <h1>The Interactive Pool</h1>
                    <p>l'Interactive Pool du DVIC est une plateforme éducative interactive utilisant la gamification pour enseigner les mathématiques et la physique. Mon projet consiste à créer un mode veille qui maintient la plateforme active en permanence, offrant ainsi des modes de jeu, artistique et ambiant. Ce mode veille vise à susciter la curiosité des utilisateurs et à accroître l'utilisation de la plateforme éducative.
                    </p>
                </div>
            </div>

            <div class="image-card">
                <div class="image-left">
                    <a href="https://www.kickstarter.com/projects/violetteanicet/keyvoila-grab-your-keys?ref=discovery&term=keyvoila"><img src="../assets/keyvoila.jpg" alt="avocat2" /></a>
                </div>
                <div class="image-right">
                    <h1>Keyvoila</h1>
                    <p>Ne touchez jamais plus le fond de votre sac ! KeyVoila est une manière élégante de retrouver instantanément vos clés et autres objets personnels en un clin d'œil. Cet accessoire élégant et moderne vous permet de changer de sac facilement grâce à cette chaîne stylée directement connectée à vos biens les plus précieux. De plus, KeyVoila est fabriqué à Paris, la capitale de la mode, pour un maximum de style !
                    </p>
                </div>
            </div>

            <div class="image-card">
                <div class="image-left">
                    <a href="https://media.istockphoto.com/id/1204481108/fr/vectoriel/logo-de-pizza-de-dessin-anim%C3%A9-dun-chef-de-service.jpg?s=612x612&w=0&k=20&c=9oevumRzKtQQSKWNbLCPfRfLMYSmZHNTKm2GJ4KzQ1Q="><img src="../assets/bague.jpg" alt="avocat3" /></a>
                </div>
                <div class="image-right">
                    <h1>The Ring</h1>
                    <p>"The Ring" est une collection de bagues connectées conçues pour offrir une solution innovante de sécurité personnelle. Ces bagues permettent d'envoyer des signaux d'alerte instantanés à d'autres utilisateurs portant également ces bagues en cas de situation potentiellement dangereuse. Cette technologie offre la possibilité d'avoir un impact en temps réel sur la situation, renforçant ainsi la sécurité et la tranquillité d'esprit des utilisateurs. Avec "The Ring", la protection personnelle devient plus efficace et collaborative.
                    </p>
                </div>
            </div>
        </section>
    </div>
</template>

<style>

    .images {
        margin-top: 400px;
        margin-left: 280px;
        margin-right: 280px;
    }
    .images h2{
        margin-bottom: 70px;
    }


    .images .image-card {
        display: flex;
        align-items: center;
        margin-bottom: 60px;
    }

    .images .image-card .image-left {
        margin-right: 40px;
        opacity: 1;
        transition: opacity 0.25s ease-in-out;
    }

    .images .image-card .image-left a{
        cursor: pointer;
    }


    .images .image-card .image-left:hover {
        opacity: 0.5;
    }


    .images .image-card .image-left img {
        height: 200px;
        width: 400px; 
    }

    @media only screen and (max-width:880px){
        .images .image-card {
            flex-wrap: wrap;
        } 
    }

    @media only screen and (max-width: 621px){
        .images .image-card .image-left img {
            width:100%;

        }
}
</style>