<template>
    <div>
        <section id="contact">
                <h2 id="titre"> Contactez moi en remplissant ce questionnaire</h2>
                <form id="addContact">
                    Nom: <input class="input" type="text" id="Nom">
                    Prenom: <input class="input" type="text" id="Prenom">
                    Email: <input class="input" type="text" id="Email">
                    Sujet: <input class="input" type="text" id="Sujet">
                    Description: <input class="input" type="text" id="Description">
                    <button type ="button" id="projectButton" @click="AddContact">Envoyer le formulaire</button>
                </form>
                <ul id="projectlist"></ul>

            </section>
    

        <footer>
            <h3>
                <span class="material-symbols-outlined">
                    filter_drama
                </span>
                Marine Reynaud
            </h3>
            <p>&copy; Marine Reynaud 2023</p>
        </footer>
    </div>
</template>

<script>
export default {
    name: "formContact",
    methods: {
        AddContact(){
            var nom = document.getElementById("Nom").value;
            var prenom = document.getElementById("Prenom").value;
            var email = document.getElementById("Email").value;
            var sujet = document.getElementById("Sujet").value;
            var desc = document.getElementById("Description").value;
            var list = document.getElementById("projectlist");

            list.innerHTML = "";

            var listElement = document.createElement("li");
            listElement.innerHTML = nom + " " + prenom + " " + email + " " + sujet + " " + desc;
            console.log(listElement);
            list.appendChild(listElement);

            // Réinitialise le formulaire
            document.getElementById("Nom").value = "";
            document.getElementById("Prenom").value = "";
            document.getElementById("Email").value = "";
            document.getElementById("Sujet").value = "";
            document.getElementById("Description").value = "";
        
        }
    }
};
</script>

<style>

#titre {
    margin-left: 280px;
    margin-top:200px;
}

    #addContact{
    display: flex;
    flex-direction: column; /* Aligne les éléments en colonne */
    margin-left: 280px;
    margin-top:50px;
}

.input {
    font-family:Arial;
    padding: 10px;
    border: 1px ridge #000;
    border-color: green;
    max-width: 200px;
    max-height: 10px;
    margin-bottom: 20px;
}

#projectButton{
    background-color: green;
    max-width: 218px;
    max-height: 40px;
    
}

footer {
    margin-top: 100px;
    margin-left: 230px;
    
    padding: 50px;
    
}

footer p {
    font-size: 15px;
}
</style>
