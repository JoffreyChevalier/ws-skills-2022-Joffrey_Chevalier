# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ✔️

```javascript
function Exemple() {
  const [open, setOpen] = useState(false);

  const handleOpen = () => setOpen(!open);

  return (
    <div>
      <Button type='button' onClick={handleOpen}>
        Open it !
      </Button>
    </div>
  );
}
```

- les composants enfants et les _props_ qu'on leur passe ✔️

```javascript
function Exemple({ name }) {
  return (
    <div>
      <h1>Bonjour {name}</h1>
    </div>
  );
}
```

- le déclenchement d'instructions en fonction des actions de l'utilisateur ❌ / ✔️
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ❌ / ✔️
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

### Utilisation dans un projet ❌ / ✔️

[lien github](https://github.com/JoffreyChevalier/wilder)

Description : Projet fil rouge Alternance

### Utilisation en production si applicable❌ / ✔️

[lien du projet](https://github.com/JoffreyChevalier/Knock-Knock)

Description : Projet 3 de la formation Dev web 5 mois

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- https://api.daily.dev/devcards/e8980e938a4e4e50b92aa7dc13f872b0.png?r=r13
- Utilisation journaliere de l'extension Chrome daily.dev qui permet d'acceder à fil d'actus Dev.

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

```

```
