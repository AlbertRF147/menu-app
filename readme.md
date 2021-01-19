# MENU APP

Aquesta idea neix de la actual necessitat que tenen molts negocis de la restrauracio actualment (i en un futur) de digitalitzar els seus menus.

No solsament digitalitzar els seus menus sino tambe de:

- Creacio i personalitzacio de e-menus
- Constant gestio i manteniment dels mateixos
- Hosting dels mateixos sense complicacions
- Accessibilitat als mateixos mitjançant codis QR
- Access instantani als menus en locals on la convertura d'internet es molt pobre


#### Problematica

1. Moltes apps disponibles actualment nomes permeten pujar imatges de menus
2. Son cares
3. No disposen d'un UI intuitiu i facil de manejar
4. No allotjen els menus de forma eficient i rapida
5. Degut a l'ultim punt, no serveixen els menus de forma rapida i en condicions de cobertura precaries

#### Solucio

- Desenvolupar una aplicacio web (possiblitat de migrar a android facilment e.g. Cordova)
- Utilitzar una base de dades noSQL per maximizar velocitat i simplicitat
- Utillitzar una llibreria com React per al front-end
- Utilitzar una framework com ara Tailwind per agilitzar tot el CSS
- Utilitzar NodeJS i express per al back-end
- Utilitzar llibreries com ara Gatsby o Next a l'hora de servir els menus (estatics) i aixi maximizar els temps de carrega
- Crear un dashboard on els usuaris puguin crear menus i plats de forma rapida i sencilla

#### En Resum

La meva idea es crear una web app que permeti crear menus digitals de forma sencilla, intuitiva, i molt rapida. La prioritat es no complicar-se gens al principi i intentar tindre alguna cosa llesta en el menor temps possible. Obviament necessitem que sigui escalable per poguer afegir-hi mes funcionalitat en un futur.




Em sembla de puta mare (perdon por el retraso, he anat moltíssim liat aquestes setmanes). 

Hi ha alguns punts que em deixen inquiet perquè no sé com els avordariem. Amb Gatsby/Next podem crear un frontal sense problema, que tiri d'un CMS (tipo Netlify-CMS (propi), Strapi, o d'un ja fet, DatoCMS, Contentful, etc) on els restaurants puguin afegirr els seus menus. 

Vaig vomitant el que em passa pel cap i em corregeixes el que creguis, que ara mateix tinc el cervell fet papilla:

És a dir, a nivell pràctic, tindriem client-only routes on els restaurants entrarien al seu dashboard i anirien ficant plats, descripció, categoria (postre, primer, segon, beguda, etc) i preu. Un cop es guardés a la base de dades, això hauria de tirar una mena de webhook cap al frontal per tornar a buildejar les pàgines (aixo es el que li vec punts dèbils), ja que son estàtiques. I bueno, tema funcionalicats de la web no seran gaire complexes (sliders per aqui, fotos pepines, testimonials, etc). Pel tema de poca connexió, Gatsby te algun plugin per servir contingut offline, fent servir web servers (imagino que next també ho deu tenir). 

Quan vulguis ho anem movent o ho parlem amb més calma.

Cuidat tio
