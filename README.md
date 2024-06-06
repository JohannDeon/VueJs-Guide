
 ____________________________________________________________________________________________________________________________
|         _           _           _           _            _         _     _                 _            _         _        |
|        /\ \        /\ \        /\ \        /\ \     _   / /\      /\ \  /\_\              /\ \         /\ \      /\ \      |
|       /  \ \____  /  \ \      /  \ \      /  \ \   /\_\/ /  \     \_\ \/ / /         _   /  \ \____    \ \ \    /  \ \     |
|      / /\ \_____\/ /\ \ \    / /\ \ \    / /\ \ \_/ / / / /\ \__  /\__ \ \ \__      /\_\/ /\ \_____\   /\ \_\  / /\ \ \    |
|     / / /\/___  / / /\ \_\  / / /\ \ \  / / /\ \___/ / / /\ \___\/ /_ \ \ \___\    / / / / /\/___  /  / /\/_/ / / /\ \ \   |
|    / / /   / / / /_/_ \/_/ / / /  \ \_\/ / /  \/____/\ \ \ \/___/ / /\ \ \__  /   / / / / /   / / /  / / /   / / /  \ \_\  |
|   / / /   / / / /____/\   / / /   / / / / /    / / /  \ \ \    / / /  \/_/ / /   / / / / /   / / /  / / /   / / /   / / /  |
|  / / /   / / / /\____\/  / / /   / / / / /    / / _    \ \ \  / / /     / / /   / / / / /   / / /  / / /   / / /   / / /   |
|  \ \ \__/ / / / /______ / / /___/ / / / /    / / /_/\__/ / / / / /     / / /___/ / /\ \ \__/ / ___/ / /__ / / /___/ / /    |
|   \ \___\/ / / /_______/ / /____\/ / / /    / / /\ \/___/ / /_/ /     / / /____\/ /  \ \___\/ /\__\/_/___/ / /____\/ /     |
|    \/_____/\/__________\/_________/\/_/     \/_/  \_____\/  \_\/      \/_________/    \/_____/\/_________\/_________/      |
|                                                                                                                            | 
|____________________________________________________________________________________________________________________________|



Vue JS:

- Créer un dossier où le site web sera stocké.

- Installer Node.JS à l'adresse https://nodejs.org/en/download/prebuilt-installer.

- Ouvrir le dossier du site web dans Visual Studio Code.

- Ouvrir le terminal et tapez : npm -v
 	-La version devrait s'afficher, sinon réinstaller Node.js.

- Tapez npm install -g npm pour installer NPM.

- Installer Vue CLI : npm install -g @vue/cli 		// Cela permettra de créer le site web.


Créer le projet : vue ui			// Ouvre une interface dans le navigateur

En cas d'erreur, exécuter : Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force


- Sur l'interface localhost:8000
	- Allez sur "Créer".
	- Vérifiez d'être dans le bon dossier, puis créez un nouveau projet.
	- Gestionnaire de paquets : npm. Options additionnelles => ne rien toucher. Dépôt Git => oui.

	- Sélectionnez un preset : Default (Vue 3). Et voilà !!

- Retournez sur Visual Studio et le site web apparaîtra.
- Accédez au projet en écrivant dans le terminal : cd nom_du_projet


Tips:

/!\ Pour lancer le serveur local : npm run serve 
	- Rendez-vous à l'adresse indiquée dans le terminal via un navigateur (de préférence Chrome) : 
		
		App running at: 
			- Local: http://localhost:8080/ <-- celle-ci
			- Network: indisponible

/!\ Pour builder le site : npm run build.


	























		





