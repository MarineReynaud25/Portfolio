<template>
    <div>
        
        <div class="navbar-container">
            
           <ul id="ul1">
                <li><a href="#home">Home</a></li>
               <li><a href="#aboutme">About Me</a></li>
               <li><a href="#projets">Projets</a></li>
               <li><a href="#contact">Contact</a></li>
           </ul>
           
       </div>

    <div id="home">

    

        <nav>
            <h1>
                <span class="material-symbols-outlined">
                    filter_drama
                </span>
                Marine Reynaud
            </h1>

            <ul>
                <li>reynaud.marine@icloud.com
                    <span class="material-symbols-outlined">
                        call_made
                        </span>
                </li>
            </ul>
        </nav>

        

        <header>
                <div class="header-left">
                    <small>
                        <span class="material-symbols-outlined">
                            home_pin
                        </span>
                    Paris, France</small>

                    <h1> Bonjour, <br />Je suis Marine Reynaud</h1>

                    <p>Je suis étudiant en Technologie Créative au Centre d'Innovation De Vinci et je fais partie du groupe "Apprentissage Humain". Je suis passionné par la science, les nouvelles technologies, le design et les êtres humains. Au cours de mes études, j'ai remarqué que la technologie pouvait être intimidante et sembler difficile à comprendre. En raison de mon intérêt pour l'art et le dessin, mon ambition est d'apporter un aspect visuel aux projets technologiques afin d'inviter les utilisateurs à découvrir les capacités de n'importe quelle plateforme. Ma contribution consiste à programmer des visualisations artistiques basées sur le système de la plateforme et à ajouter des informations interactives, utiles et captivantes pour la plateforme. 
                    </p>

                    <div class="links">
                        <a href="mailto:marine.reynaud@edu.devinci.fr">Email 
                            <span class="material-symbols-outlined">
                            call_made
                            </span>
                        </a>

                        <a href="https://www.linkedin.com/in/marine-reynaud-b2b100204/">LinkedIn 
                            <span class="material-symbols-outlined">
                            call_made
                            </span>
                        </a>

                        <a href="https://i.pinimg.com/originals/be/45/50/be45501ad5ad2ba4e403360d4d9119ce.png">Curriculum
                            <span class="material-symbols-outlined">
                            call_made
                            </span>
                        </a>
                    </div>

                </div>
                <div class="header-right">
                    <img src="../assets/moi.jpg" alt="c'est moi"/>
                </div>
        
            </header>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>

    


    nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-left: 280px;
    padding-top: 100px;
    /*margin-top: 100px;*/
    margin-right: 280px;


    }

    nav ul{
        display: flex;
        align-items: center;
        flex-wrap: wrap;
        list-style-type: none;
        font-weight: 500;
    }

    nav ul li{
        margin-left: 40px;
        font-size: 15px;
        cursor: pointer;
        position: relative;
        right: 30px;
    }

    nav ul li span{
        position: absolute;
        top: -5px;
        right: -25px;
    }

    .navbar-container {
        position: fixed;
        display: flex;
        margin-left: 1190px;
        margin-right: 280px; /* Marge à droite pour l'espacement */
        margin-top: 0px;
        padding: 20px;
        
    }
    .navbar-container #ul1 {
        list-style: none;
        padding: 0;
    }

    .navbar-container #ul1 li {
        display: inline;
        margin-left: 20px; /* Espacement entre les éléments de navigation */
    }

    .navbar-container #ul1 li a {
        text-decoration: none;
        color: black;
        transition: color 0.3s; 
    }

    .navbar-container #ul1 li a:hover {
    color: green; /* Changez la couleur de la police lors du survol */
    }

    header {
    margin-left: 280px;
    margin-right: 200px;
    margin-top: 80px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    }

    header .header-left {
        flex: 6;
        margin-right: 50px;

    }

    header .header-left small{
        font-weight: bold;
        display: flex;
        align-items: center;
    }

    header .header-left h1 {
        font-size: 50px; 
        font-weight: 400;
        margin-top: 15px;
    }

    header .header-left .links{
        margin-top: 80px;
    }

    header .header-left p{
        margin-right: 80px;

    }

    header .header-left .links a {
        text-decoration : none;
        color: inherit;
        position: relative;
        margin-right: 40px;
        font-weight: bold;
    }

    header .header-left .links a span {
        position: absolute;
        top: -5px;
        right: -28px;
    }

    header .header-left .links a:hover{
        color: green;
    }

    header .header-right {
        flex: 3;    
        
    }

    header .header-right img{
        width: 80%;
        margin-right: 100px;
        
    }


    @media only screen and (max-width: 768px){
        .navbar-container {
            display: block; /* Afficher les éléments en colonne */
            position: fixed; /* Annuler la position fixe */
            margin-left: 0; /* Annuler la marge à gauche */
            margin-right: 0; /* Annuler la marge à droite */
        }
        .navbar-container #ul1 li {
            display: block; /* Afficher les éléments en colonne */
            margin-left: 0; /* Annuler l'espacement horizontal */
            margin-bottom: 10px; /* Conserver l'espacement vertical */
        }
        
        header {
            flex-direction: column-reverse;
        }
        header .header-left {
            margin-right: 0;
        }

        header .header-right {
            margin-bottom: 40px;
        }
        header .header-right img{
            width: 250px;
        }
    }
</style>