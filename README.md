# GitHubRankingsSpain-badge

[![Python España](https://img.shields.io/badge/Python-Espa%C3%B1a-blue.svg?maxAge=31536000&logo=github&colorA=e60000&colorB=ffcc12&style=flat)](https://www.es.python.org)
[![Python Heroku](https://img.shields.io/badge/Python-Heroku-purple.svg?maxAge=31536000&logo=github&colorA=888e96&colorB=800080&style=flat)](https://www.heroku.com)
[![GitHub release](https://img.shields.io/github/release/RDCH106/GitHubRankingsSpain-badge.svg)](https://github.com/RDCH106/GitHubRankingsSpain-badge/releases)
[![GitHub](https://img.shields.io/github/license/RDCH106/GitHubRankingsSpain-badge.svg)](https://github.com/RDCH106/GitHubRankingsSpain-badge/blob/master/LICENSE)

🛡️ Insignias del ranking de desarrolladores españoles en GitHub

Actualmente en desarrollo... 🛠️

📯 Beta desplegada en: https://github-rankings-spain-badge.herokuapp.com


## Proyectos Realacionados

- [GitHubRankingsSpain-viewer](https://github.com/RDCH106/GitHubRankingsSpain-viewer)
- [GitHubRankingsSpain](https://github.com/iblancasa/GitHubRankingsSpain)


### Instalación

Puedes instalarlo desde el código fuente con:

``` 
$ git clone https://github.com/RDCH106/GitHubRankingsSpain-badge.git --recursive
$ cd GitHubRankingsSpain-badge/service
$ pip install -r requirements.txt
```


### API

#### Servicio de insignias

Formato de petición: `<host>:<port>/badge/<region_name>/<github_user>`

- `<host>`: IP o dominio de la máquina que aloja el servicio
- `<port>`: Puerto en el que se sirve el servicio
- `<region_name>`: Ver tabla de regiones para conseguir la insignia de la región deseada
- `<github_user>`: Usuario GitHub del que se quiere obtener la insignia

**Tabla de Regiones** :es:

| Región                   | region_name              |
|--------------------------|--------------------------|
| :es:**España**:es:       | spain                    |
| **Andalucía**            | andalucia                |
| Almería                  | almeria                  |
| Cádiz                    | cadiz                    |
| Córdoba                  | cordoba                  |
| Granda                   | granada                  |
| Huelva                   | huelva                   |
| Jaén                     | jaen                     |
| Málaga                   | malaga                   |
| Sevilla                  | sevilla                  |
| **Aragón**               | aragon                   |
| Huesca                   | huesca                   |
| Teruel                   | teruel                   |
| Zaragoza                 | zaragoza                 |
| **Asturias**             | asturias                 |
| **Cantabria**            | catanbria                |
| **Castilla y León**      | castillayleon            |
| Ávila                    | avila                    |
| Burgos                   | burgos                   |
| León                     | leon                     |
| Palencia                 | palencia                 |
| Salamanca                | salamanca                |
| Segovia                  | segovia                  |
| Soria                    | soria                    |
| Valladolid               | valladolid               |
| Zamora                   | zamora                   |
| **Castilla-La Mancha**   | mancha                   |
| Albacete                 | albacete                 |
| Ciudad Real              | ciudadreal               |
| Cuenca                   | cuenca                   |
| Guadalajara              | guadalajara              |
| Toledo                   | toledo                   |
| **Cataluña**             | catalonia                |
| Barcelona                | barcelona                |
| Gerona                   | girona                   |
| Lérida                   | lleida                   |
| Tarragona                | tarragona                |
| **Ceuta**                | ceuta                    |
| **Comunidad Valenciana** | cvalenciana              |
| Alicante                 | alicante                 |
| Castellón                | castellon                |
| Valencia                 | valencia                 |
| **Extremadura**          | extremadura              |
| Badajoz                  | badajoz                  |
| Cáceres                  | caceres                  |
| **Galicia**              | galicia                  |
| La Coruña                | coruna                   |
| Lugo                     | lugo                     |
| Orense                   | orense                   |
| Pontevedra               | pontevedra               |
| **Islas Baleares**       | baleares                 |
| **Islas Canarias**       | canarias                 |
| **La Rioja**             | rioja                    |
| **Madrid**               | madrid                   |
| **Melilla**              | melilla                  |
| **Murcia**               | murcia                   |
| **Navarra**              | navarra                  |
| **País Vasco**           | euskadi                  |
| Álava                    | alava                    |
| Vizcaya                  | vizcaya                  |
| Guipuzcoa                | guipuzcoa                |


### Ejemplo

[![Ranking GitHub España](https://github-rankings-spain-badge.herokuapp.com/badge/euskadi/RDCH106)](https://rawgit.com/RDCH106/GitHubRankingsSpain-viewer/master/ghrankings-viewer.html?region=euskadi/euskadi)

#### Código HTML
```html
<a href="https://rawgit.com/RDCH106/GitHubRankingsSpain-viewer/master/ghrankings-viewer.html" target="_blank">
  <img src="https://github-rankings-spain-badge.herokuapp.com/badge/euskadi/RDCH106" alt="Ranking GitHub España">
</a>
```

#### Código Markdown
``` markdown
[![Ranking GitHub España](https://github-rankings-spain-badge.herokuapp.com/badge/euskadi/RDCH106)](https://rawgit.com/RDCH106/GitHubRankingsSpain-viewer/master/ghrankings-viewer.html)
```
