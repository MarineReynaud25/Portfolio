<template>
    <div id="aboutme">
    <div class="body">
        <h2 id="h2">About Me</h2>
        <section class="aboutme2">
        
        <p id="p">Je suis Marine, une passionnée de voyage, de sport et de chiens dans la vie. Mon quotidien est rythmé par la découverte de nouveaux horizons, la pratique assidue d'activités sportives, et l'amour sincère que je porte à nos amis à quatre pattes.</p>
                
        <div class="image-card">
            <div class="image-left"> 
                <img src="../assets/vacances2.jpg" alt="avocat" />
            </div>
            
            <div class="image-right"> 
                <h1>Les Voyages</h1>
                <p>Le monde est ma toile, et chaque voyage est une nouvelle page d'inspiration. Que ce soit à travers des escapades urbaines chargées d'histoire ou des explorations en pleine nature, je trouve une profonde satisfaction dans l'exploration de cultures diverses et de paysages époustouflants.
                </p>
            </div>
        </div>
        <div class="image-card">
            <div class="image-left"> 
                <img src="../assets/surf3.jpg" alt="avocat" />
            </div>
            
            <div class="image-right"> 
                <h1>Le Sport</h1>
                <p>Le sport est une autre facette essentielle de ma vie. La discipline, la persévérance et le dépassement de soi sont des valeurs que j'ai apprises grâce à mon engagement dans diverses disciplines sportives. Chaque séance d'entraînement est une opportunité de grandir, de renforcer mon corps et mon esprit, et de repousser mes limites.
                </p>
            </div>
        </div>
        <div class="image-card">
            <div class="image-left"> 
                <img src="../assets/chien3.jpg" alt="avocat" />
            </div>
            
            <div class="image-right"> 
                <h1>Mes Compagnons</h1>
                <p>Mais au-delà de tout, il y a mes compagnons à quatre pattes. Les chiens sont bien plus que des animaux de compagnie pour moi ; ce sont des membres à part entière de ma famille. Leur fidélité inébranlable, leur amour inconditionnel et leur joie de vivre constante illuminent mes journées et rappellent l'importance des petites choses dans la vie.
                </p>
            </div>
        </div>
    
    
</section>
    </div>

        
    </div>
</template>


<style>
   


#body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10vh;
    margin: 0;
}

#h2 {
    margin-left: 280px;
    margin-right: 280px;
    margin-top: 400px;
}

.aboutme2 #p{
    
    text-align: center;
    font-size: 1.2em; 
}

.aboutme2 {
    margin-left: 280px;
    margin-right: 280px;
    margin-top: 20px;
    position:relative;
    display:flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    
}

.aboutme2 h2 {
    margin-bottom: 70px;

}

.aboutme2 .image-card::after{
    content: "";
    display:block;
    clear: both;

}

.aboutme2 .image-card {
    display: flex;
    align-items: center;
    justify-content: center; /* Centrer horizontalement les éléments dans la section */
    margin-bottom: 60px;
    max-width: 600px;
    margin: 0 auto;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.3);
    margin-top: 20px;;
}


.aboutme2 .image-card .image-left {
    margin-top: 80px;
    margin-right: 0px; 
    order: 2; 
    
}

.aboutme2 .image-card .image-right {
    order: 1; 
}

.aboutme2 .image-card .image-left img {
    /*height: 200px;*/
   /* width: 400px;*/
   width: 200px;
    height: 200px;
    object-fit: cover;
    border-radius: 50%;
    float: left;
    shape-outside: margin-box;
    margin: 0 2px 5px 0;
}

.aboutme2 .image-card .image-left:hover img{
    transform: scale(1.1);
}


    @media only screen and (max-width:880px){
        .aboutme2 .image-card {
            flex-wrap: wrap;
        } 
    }

    @media only screen and (max-width: 621px){
        .aboutme2 .image-card .image-left img {
            width:100%;

        }

    }
</style>