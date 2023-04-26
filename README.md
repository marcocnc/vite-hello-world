Vite Hello World
===
Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell’installazione come visti a lezione.
Create e utilizzate un componente `AppTitle`, il quale contiene un titolo che recita “La mia prima app con Vite!”

## Procedimento
1. Creare la cartella con le NPM e cancellare il contenuto del file App.vue;
2. Aprire la console con CTRL + J e digitare npm install per avere il node_modules;
3. Creare un nuovo file vue nella cartella components (AppTitle);
4. Nel file AppTitle creeremo una proprietà name che avrà come stringa il nome del file, e una proprietà title che avrà la stringa che vedremo nel DOM;
5. Aggiungeremo un tag h1 nel template e gli daremo uno stile nello style (a cui aggiungeremo scoped in modo tale da non dover necessariamente creare delle classi);
6. Ora nel file App si fa l'import di AppTitle;
7. Nell'export default si crea un components, che è un oggetto che conterrà una proprietà che sarà proprio il nome del file;
8. Infine, si crea nel template un self-close tag che avrà il nome della proprietà nel components, che corrisponde alla stringa creata nell'altro file