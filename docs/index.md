# Modelování budov pro 3D model Prahy

Účelem projektu je pilotní __modelování budov ve formátech BIM__ pro využití v objektovém [__3D modelu Prahy__](https://app.iprpraha.cz/apl/app/model3d/){target="_blank"} (spravovaném [IPR Praha](https://iprpraha.cz/)). Protože objektový 3D model Prahy má svá technická specifika, modelování (vlastnosti výsledných modelů) je tomu nutné přizpůsobit.

- Databáze objektů 3D modelu Prahy je vedena ve __formátu CityGML__. Tento formát rozlišuje mnoho sémantických kategorií objektů podobně jako formáty BIM. Jedním z požadavků na výsledné modely je proto __kompatibilita s hierarchií formátu CityGML__.
- Každý objekt je v 3D modelu Prahy veden ve __více stupních detailu__ – LOD1, LOD2 a LOD3. BIM modely proto musí obsahovat i odvozené varianty pro jednotlivé stupně detailu (více o LOD viz [Metodika modelování](./metodika.md)).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

