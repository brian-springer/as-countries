# as-countries
AppSmith Countries Demo
![](https://raw.githubusercontent.com/appsmithorg/appsmith/release/static/appsmith_logo_primary.png)

This app is built using Appsmith. Turn any datasource into an internal app in minutes. Appsmith lets you drag-and-drop components to build dashboards, write logic with JavaScript objects and connect to any API, database or GraphQL source.

![](https://raw.githubusercontent.com/appsmithorg/appsmith/release/static/images/integrations.png)

### Demo Setup Using the Rest Countries API

Follow these steps to create a simple countries demo inside Appsmith:

1. Create a new API datasource inside Appsmith and name it **GetCountries**.
   - Method: `GET`
   - URL: `https://restcountries.com/v3.1/all`

2. Drag a **Table** widget onto the canvas and set its *Table Data* property to:
   ```{{ GetCountries.data }}```

3. For a more visual list, use a **List** widget. Inside the list:
   - Add an **Image** widget with the *Image* property set to `{{ currentItem.flags.png }}`.
   - Add a **Text** widget and set its *Text* property to `{{ currentItem.name.common }}`.
   - Display fields like capital or region using additional Text widgets.

4. Run **GetCountries** on page load so the widget populates automatically.

These steps will let you explore the Rest Countries API quickly with minimal setup.


### [Github](https://github.com/appsmithorg/appsmith) • [Docs](https://docs.appsmith.com/?utm_source=github&utm_medium=social&utm_content=appsmith_docs&utm_campaign=null&utm_term=appsmith_docs) • [Community](https://community.appsmith.com/) • [Tutorials](https://github.com/appsmithorg/appsmith/tree/update/readme#tutorials) • [Youtube](https://www.youtube.com/appsmith) • [Discord](https://discord.gg/rBTTVJp)

##### You can visit the application using the below link

###### [![](https://assets.appsmith.com/git-sync/Buttons.svg) ](https://branch.appsmith.com/applications/682cc2b6ffd904675a8cb5a3/pages/682cc2b6ffd904675a8cb5a5) [![](https://assets.appsmith.com/git-sync/Buttons2.svg)](https://branch.appsmith.com/applications/682cc2b6ffd904675a8cb5a3/pages/682cc2b6ffd904675a8cb5a5/edit)
