# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ✔️
- les composants enfants et les _props_ qu'on leur passe ✔️
- le déclenchement d'instructions en fonction des actions de l'utilisateur ❌ / ✔️ (à pofiner)
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ❌ / ✔️ (à pofiner)
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant 
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

 const [ingred, setIngred] = useState([]); // création d'un state

  const getIngred = () => {
    axios
      .get(`${process.env.REACT_APP_API_URL}/api/ingredients/liste/${id}`)   // récupération des données du back dans "ingred" via setIgred
      .then((response) => setIngred(response.data));
  };


  ingred.map((Dishe) => (
            <div key={Dishe} className="mapping">
              <div className="describe-dishe">                                   // affichage des données avec un map
                <div className="title">{Dishe.name}</div>
                <img
                  alt={Dishe.name}
                  src={`${process.env.REACT_APP_API_URL}/${Dishe.image}`} 
                />
                <div className="lien-page-ingredient">
                  <Link to={`/dishes/${Dishe.id}`} className="buttonLink">
                    + Détails
                  </Link>
                </div>
              </div>
            </div>

  

### Utilisation dans un projet ❌ / ✔️

[lien github](https://github.com/animmaa/plat-japonais-front)

Description : site perso en react

### Utilisation en production si applicable❌ / ✔️

[lien du projet](https://platjap.lebris-davy.fr/)

Description : site perso en react

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien : https://fr.reactjs.org/docs/getting-started.html
- description : documentation de react pas toujours a jour mais fonctionnel, sinon recherche sur google

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
