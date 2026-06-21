<div align="center">
  <img src="public/icon.png" alt="Second Brain Logo" width="120" />
  <h1>Second Brain 🧠</h1>
  <p><strong>Votre assistant d'entretien invisible propulsé par l'IA</strong></p>

  [English](README.md) | [Português](README.pt.md) | [Español](README.es.md) | [Français](README.fr.md) | [Italiano](README.it.md)
</div>

<br/>

**Second Brain** est un assistant de bureau 100% gratuit et invisible conçu pour aider les professionnels du monde entier à exceller dans leurs entretiens d'embauche. Il s'exécute silenciellement en arrière-plan, écoute l'entretien et génère des suggestions de réponses à la première personne, basées sur votre propre CV et la description du poste.

Propulsé par l'inférence ultra-rapide Llama-3 de [Groq](https://groq.com) et le modèle Whisper-large-v3, l'ensemble du processus — de la capture vocale à la suggestion intelligente — se déroule en quelques millisecondes.

## ✨ Fonctionnalités

- **Transcription Vocale en Temps Réel** : Utilise Whisper-v3 via l'API Groq pour transcrire la parole de l'intervieweur avec une précision et une rapidité extrêmes.
- **Suggestions Contextuelles** : Analyse la conversation en cours, votre CV et la description du poste pour suggérer les meilleures réponses possibles.
- **Support Multilingue** : Interface et moteur d'IA 100% localisés pour l'Anglais, le Portugais, l'Espagnol, le Français et l'Italien.
- **Mode Invisible** : Construit avec Electron, il peut être minimisé pour ne pas vous déranger pendant que vous vous concentrez sur votre appel vidéo.
- **La Confidentialité Avant Tout** : Votre CV, l'offre d'emploi et vos clés API sont stockés exclusivement dans la mémoire locale (`localStorage`) de votre propre ordinateur.

## 🚀 Guide Rapide (Téléchargement)

1. **Téléchargez l'Installateur :**
   Obtenez le dernier `Second Brain Setup .exe` depuis notre page [Releases](../../releases).
   
2. **Créez une Clé API Groq Gratuite :**
   Allez sur [console.groq.com](https://console.groq.com/keys) et générez une clé API gratuite. Elle est indispensable pour faire fonctionner le moteur IA à haute vitesse.

3. **Installez et Configurez :**
   - Ouvrez l'application.
   - Collez votre Clé API.
   - Collez votre CV et la Description du Poste.
   - Sélectionnez votre langue.
   - Cliquez sur **Commencer l'Entretien** et c'est parti !

## 🛠️ Développement (Pour les Développeurs)

Si vous souhaitez compiler le code source ou contribuer :

### Prérequis
- Node.js 18+
- npm ou yarn

### Installation

```bash
git clone https://github.com/2brain/second-brain.git
cd second-brain

# Installez les dépendances
npm install

# Lancez le serveur de développement
npm run dev
```

### Compiler pour la Production (Installateur)

```bash
# Compiler et générer l'installateur Electron
npm run dist
```
L'installateur `.exe` sera généré dans le dossier `dist-installers`.

## 🤝 Soutenez le Projet

Second Brain est open-source et gratuit pour la communauté. Si cet outil vous a aidé à obtenir un emploi ou à réussir un entretien, pensez à nous offrir un café !

<a href="https://www.buymeacoffee.com/2brain" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 40px !important;width: 145px !important;" ></a>

## ❓ FAQ (Foire Aux Questions)

**1. Est-ce vraiment 100% gratuit ?**
Oui ! L'application est open-source et totalement gratuite. Il vous suffit de créer un compte gratuit sur Groq pour obtenir votre clé API, qui offre actuellement un forfait gratuit extrêmement généreux.

**2. Le recruteur peut-il voir ou entendre l'IA ?**
Non. Second Brain s'exécute comme une fenêtre indépendante sur votre écran. Il n'injecte pas d'audio dans votre microphone et ne partage pas votre écran. Il est totalement invisible pour le recruteur.

**3. Mes données sont-elles en sécurité ? Sauvegardez-vous mon CV ?**
Votre confidentialité est notre priorité absolue. Nous n'avons pas de base de données. Votre clé API, votre CV et la description du poste sont sauvegardés strictement dans le `localStorage` de votre propre ordinateur. Rien n'est envoyé à nos serveurs (car nous n'en avons pas !).

**4. Pourquoi l'IA met-elle du temps à répondre ?**
L'IA attend que le recruteur termine un raisonnement complet avant de générer une réponse. Elle analyse le contexte par intervalles de 7 secondes pour s'assurer de bien comprendre la question avant de vous fournir le script.

**5. Cela fonctionne-t-il sur Mac ou Linux ?**
Actuellement, les versions automatisées (Releases) fournissent un programme d'installation `.exe` pour Windows. Cependant, comme il s'agit d'une application Electron, vous pouvez facilement cloner ce dépôt et exécuter `npm run dist` pour compiler pour macOS ou Linux.

---

## 📝 Licence

Distribué sous une Licence Non Commerciale. Vous êtes libre d'utiliser et d'étudier le logiciel, mais **la vente ou la distribution commerciale est strictement interdite**. Voir le fichier `LICENSE` pour plus d'informations.
