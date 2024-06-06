```
       _           _           _           _            _         _     _                 _            _         _       
      /\ \        /\ \        /\ \        /\ \     _   / /\      /\ \  /\_\              /\ \         /\ \      /\ \     
     /  \ \____  /  \ \      /  \ \      /  \ \   /\_\/ /  \     \_\ \/ / /         _   /  \ \____    \ \ \    /  \ \    
    / /\ \_____\/ /\ \ \    / /\ \ \    / /\ \ \_/ / / / /\ \__  /\__ \ \ \__      /\_\/ /\ \_____\   /\ \_\  / /\ \ \   
   / / /\/___  / / /\ \_\  / / /\ \ \  / / /\ \___/ / / /\ \___\/ /_ \ \ \___\    / / / / /\/___  /  / /\/_/ / / /\ \ \  
  / / /   / / / /_/_ \/_/ / / /  \ \_\/ / /  \/____/\ \ \ \/___/ / /\ \ \__  /   / / / / /   / / /  / / /   / / /  \ \_\ 
 / / /   / / / /____/\   / / /   / / / / /    / / /  \ \ \    / / /  \/_/ / /   / / / / /   / / /  / / /   / / /   / / / 
/ / /   / / / /\____\/  / / /   / / / / /    / / _    \ \ \  / / /     / / /   / / / / /   / / /  / / /   / / /   / / /  
\ \ \__/ / / / /______ / / /___/ / / / /    / / /_/\__/ / / / / /     / / /___/ / /\ \ \__/ / ___/ / /__ / / /___/ / /   
 \ \___\/ / / /_______/ / /____\/ / / /    / / /\ \/___/ / /_/ /     / / /____\/ /  \ \___\/ /\__\/_/___/ / /____\/ /    
  \/_____/\/__________\/_________/\/_/     \/_/  \_____\/  \_\/      \/_________/    \/_____/\/_________\/_________/     
                                                                                                                         


```
> [!NOTE]
> Vue JS:

- Créer un dossier où le site web sera stocké.

- Installer Node.JS à l'adresse [https://nodejs.org/en/download/prebuilt-installer](url).

- Ouvrir le dossier du site web dans Visual Studio Code.

- Ouvrir le terminal et tapez : ```npm -v```
  <p>- La version devrait s'afficher, sinon réinstaller Node.js.</p>
<p/>
<p/>	
- Tapez ```npm install -g npm``` pour installer NPM.

- Installer Vue CLI : ```npm install -g @vue/cli``` 		<sub>// Cela permettra de créer le site web.</sub>


Créer le projet : ```vue ui```			<sub>// Ouvre une interface dans le navigateur</sub>

En cas d'erreur, exécuter : ```Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force```


- Sur l'interface `localhost:8000`
	- Allez sur "Créer".
	- Vérifiez d'être dans le bon dossier, puis créez un nouveau projet.
	- Gestionnaire de paquets : npm.
 	- Options additionnelles => ne rien toucher.
  	- Dépôt Git => oui.

	- Sélectionnez un preset : Default (Vue 3).
 
    Et voilà !!

- Retournez sur Visual Studio et le site web apparaîtra.
- Accédez au projet en écrivant dans le terminal : ```cd nom_du_projet```


> [!TIP]
> Pour lancer le serveur local : ```npm run serve``` 
>	- Rendez-vous à l'adresse indiquée dans le terminal via un navigateur (de préférence Chrome) : 

```
App running at: 
- Local: http://localhost:8080/ <-- celle-ci
- Network: indisponible

```

>[!TIP]
> Pour builder le site : ```npm run build```.


	























		




