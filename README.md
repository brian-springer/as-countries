# as-countries
AppSmith Countries Demo
![](https://raw.githubusercontent.com/appsmithorg/appsmith/release/static/appsmith_logo_primary.png)

This app is built using Appsmith. Turn any datasource into an internal app in minutes. Appsmith lets you drag-and-drop components to build dashboards, write logic with JavaScript objects and connect to any API, database or GraphQL source.

![](https://raw.githubusercontent.com/appsmithorg/appsmith/release/static/images/integrations.png)

### Demo Setup Using the Rest Countries API

The repository now includes the JSON files required to load a simple Appsmith
application.  The app contains:

1. A REST API datasource configured at `https://restcountries.com`.
2. A query named **GetCountries** that calls `/v3.1/all` and runs on page load.
3. A page with a **Table** widget bound to `{{ GetCountries.data }}`.
4. A **List** widget that displays each country's flag and name using Image and
   Text widgets.

Importing this repository into Appsmith will create the demo automatically so you
can explore the API without any manual setup.


### [Github](https://github.com/appsmithorg/appsmith) • [Docs](https://docs.appsmith.com/?utm_source=github&utm_medium=social&utm_content=appsmith_docs&utm_campaign=null&utm_term=appsmith_docs) • [Community](https://community.appsmith.com/) • [Tutorials](https://github.com/appsmithorg/appsmith/tree/update/readme#tutorials) • [Youtube](https://www.youtube.com/appsmith) • [Discord](https://discord.gg/rBTTVJp)

##### You can visit the application using the below link

###### [![](https://assets.appsmith.com/git-sync/Buttons.svg) ](https://branch.appsmith.com/applications/682cc2b6ffd904675a8cb5a3/pages/682cc2b6ffd904675a8cb5a5) [![](https://assets.appsmith.com/git-sync/Buttons2.svg)](https://branch.appsmith.com/applications/682cc2b6ffd904675a8cb5a3/pages/682cc2b6ffd904675a8cb5a5/edit)
