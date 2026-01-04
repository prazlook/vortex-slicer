# 🌪️ Vortex Slicer - machin qu'on m'oblige à rédiger 💔
**De Zéro à ta Première Impression : Le Guide Officiel pour l'Imprimante Core R-Theta**

Bienvenue, Pilote. Ce guide va t'aider à configurer l'environnement Vortex Slicer sur ta bécane. Allez, bouge-toi le cul !
---

## 🛠️ Étape 1 : Configuration de l'Environnement

  Vortex Slicer tourne sous Python via Jupyter Notebook. Ça permet de visualiser en temps réel tes trajectoires 4 axes.
  
  ### 1. Installer Python & Jupyter
  Si tu ne l'as pas encore, la méthode la plus simple est via Anaconda ou directement via pip :
  ```bash
  pip install notebook
  ```
  ### 2. Installer les Dépendances
  Vortex a besoin de bibliothèques mathématiques et graphiques spécifiques pour gérer le 4ème axe :
  ```bash
  pip install numpy matplotlib scipy shiny
  ```
## 🚀 Étape 2 : Installation du Slicer
  ### 1. Navigue vers ton dossier préféré (pas C:\Users\Toi\documents\achats\leten par pitié, trouve-t-en un autre) avec cette commande : 
  ```bash
  cd <TON\RÉPERTOIRE\PRÉFÉRÉ>
  ```
  ### 2. Clone ce dépôt avec cette commande : 
  ```bash
  git clone https://github.com/prazlook/vortex-slicer.git
  ```
  ### 3. Dans ton terminal<sup>(1)</sup>, va dans le dossier et tape :
   ```bash
   python -m notebook
   ```
  (1) : Si tu ne sais pas ce que c'est qu'un terminal, je veux pas être méprisant ou quoi, on travaille ici dans un climat de bienveillance, mais retourne te br dans ta piaule. (Si tu es une fille, retourne faire tes trucs, je suis un mec, je sais pas comment ça se passe.) Si tu veux quand même tenter le coup (espèce de p'tite tête brûlée😉), tape "powershell" dans le champ de recherche Windows et appuie sur Entrée.
  ### 4. Ton navigateur va s'ouvrir. Clique sur Vortex_Slicer_Main.ipynb.
  <img width="1219" height="820" alt="image" src="https://github.com/user-attachments/assets/0a2692e0-40a3-427a-87f0-363c2e471cb7" />

## Étape 3 : Le Travail par Cellule
  ### 1. 
  Le slicer est composé de cellules. Navigue vers cette cellule :
  <img width="1911" height="909" alt="image" src="https://github.com/user-attachments/assets/6aacc275-6580-4913-a06a-f3343d4e4ef3" />
  
  ### 2. 
  Remplace la variable "model_name" par le nom du modèle que tu vas utiliser. Le nom ne doit contenir que des caractères alphanumériques. Pose pas de questions<img width="23" height="24" alt="image" src="https://github.com/user-attachments/assets/54be90a8-1680-4417-850a-827bb96ff192" />

  <img width="1187" height="463" alt="image" src="https://github.com/user-attachments/assets/df6d86ad-195b-42f6-8c2f-8dd6fbb862b1" />

  ### 4. 
  Place ton fichier STL dans le dossier input_models. À moins que tu ne possèdes une RTX 5090, tu ferais mieux de garder ton maillage sous la barre des 10 000 Ko, à moins, bien sûr, que tu n'apprécies l'odeur d'un GPU grillé ou que tu aies envie d'oeufs au plat aujourd'hui. Dans ce cas, injecte lui un maillage de 1 To. (N'essayez pas çà à la maison, les enfants.)<img width="685" height="392" alt="image" src="https://github.com/user-attachments/assets/3ec2b435-fbde-478e-86e8-84d09635f81e" />

  ### 5. 
  Cliquez n'importe où dans la cellule pour la sélectionner.
  <img width="43,5" height="71" alt="image" src="https://github.com/user-attachments/assets/8e4cdfe3-946e-4387-8bc2-b9f1cdc02a74" />
  (*Cette photo est putain d'inutile, mais puisque les peUtits bébés ont beUsoin d'une peUtite photo pour chaque étape, tiens.)
  
  ### 6. 
  je ne commente même pas<img width="465" height="126" alt="image" src="https://github.com/user-attachments/assets/d0cfa122-5bfe-4738-ba83-240bd3fd475e" />
  
  ### 7. 
  Pour les déb...utants, NE passez PAS à la prochaine étape pendant que le kernel est en exécution (petite, trop petite astérisque) (Toute réclamation ultérieure émanant d’individus n’ayant pas respecté les protocoles susmentionnés se verra opposée une fin de recevoir absolue. En d’autres termes : Si t’as pas écouté, viens pas me casser les couilles.)
  
  <img width="370" height="199" alt="image" src="https://github.com/user-attachments/assets/96897303-01a6-45d6-8f3b-adbd45de236b" />

  ### 8. Suivi de la Progression
  Une barre de progression ~moche~ et un pourcentage de progression vont apparaître. ~C'est fait pour les cons comme moi qui ne peuvent pas attendre et croient tout de suite que ça a planté quand ça travaille et que ça ne fait rien.~

  <img width="1185" height="72" alt="image" src="https://github.com/user-attachments/assets/5d58a3a4-e458-4e94-97c2-699871f04623" />

  ### 9. Exécution du 


## Étape 4 : Maintenance et Connectivité (Usage Avancé)
  
  ### 4.1. Recommandations de Code
  **Note de sécurité :** N'essaie pas de modifier le code du slicer si tu ne sais pas ce que tu fais. Encore moins avec Gemini. Avec les droits admin Notebook, j'ai failli griller mon CPU avec une erreur de cette IA qui a pété mes limiteurs de puisssance.

  ### 4.2. ~Conneries sans nom~ Entretien de la Connectique et du Matériel
  
  **Si un connecteur ne rentre pas du premier coup :** ne force pas comme un sourd. Ce n'est pas une question de préliminaires, c'est juste que tu essaies probablement d'insérer un câble USB-A dans un port USB-C. Sois digne, un peu.
  
  #### Garde bien en tête que :
  
  -Le matériel ne consent à rien, même s'il est réceptif.
    
  -Les courts-circuits ne sont pas ce que tu penses. Ton ordinateur n'en prend pas plus de plaisir.
  
  -Non, un GPU qui souffle ou un watercooling qui fuit n'est PAS une envie soudaine de toi.
  
  -Si tu as envie de ton PC parce qu'il te montre son port USB, éteins l'écran, sors de chez toi et essaie de parler à un être humain (genre une jolie meuf ou un beau mec que tu croises dans la rue)
