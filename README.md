# Lunar-Landing
Partint de la base que vares fer, he anat fent modificacions fins arribar al resultat que es pot veure. No he tingut massa temps per fer segons quines coses ja que modificar les imatges i trobar la manera de col·locar tot al seu lloc m'ha duit massa temps. No m'ha quedat clar com fer que els _sprites_ siguin més petits i es puguin adaptar al boto de _pause_ ( he intentat tot el que deien als tutorials). I tampoc tenc del tot clar com **superposar una imatge** damunt l'altre sense posar que siguin fixes( si no ho faig així es desquadra tot). 
He creat tres documents HTML:
* El document del joc.
* El document amb la informació sobre els controls. 
* El document amb la informació bàsica del joc.

Tots els documents tenen enllaços als menús que duen d'un document al altre.
Tambe hi han tres documents CSS: 
* Un document _css_ on hi ha l'apartat estetic del menu i el panell de control del joc.
* Un document _css_ on hi ha l'imatge de fons de pantalla del lloc i on hi han establertes les mides i posicions de les imatges.
* Un document _css_ per donar forma als arxius _controles y sobre el juego_ 


Primerament vaig crear quatre **contenidors**  `<div>`, un per el panell de control, un altre per el menú i dos mes per les imatges _.png_.
Al contenidor del panell de control vaig afegir quatre contenidors `<div>` més. Els contenidors estan anomenats amb les dades essencials per pilotar la nau. Ho he fet així  perquè crec que es la millor manera per a un futur afegir uns comptadors amb javascript(o crec que es això que s'utilitza per restar vides o posar la velocitat...) . Al document _css_ he utilitzat un **flexbox** per situar aquests contenidors  `<div>` al marge esquerra de la pàgina. Només he deixat els requadres interiors del _flexbox_ ja que així em pareixia més bonic estèticament.

Per fer el menú, simplement  vaig crear una llista i li vaig donar forma amb el _css_. Cal dir que vaig tenir molts de problemes a l'hora de situar el menú a la dreta i que es quedes al seu lloc al tornar petita la pàgina. Ho vaig poder arreglar posant el “comando” **_float_** al _css_ en ves de assignar-li una posició manualment. Com em sortia el menú molt aferrat al marge de la dreta vaig haver d'afegir un marge al css. Vaig utilitzar un botó per l'opció **pause** i volia posar un _sprite_
però la imatge sortia molt gran i no la podia reduir al document _css_ (encara no se perquè). Com ja no em quedava temps per fer-ho ho he deixat per més endavant. 

El següent pas va  ser posar els links de les imatges als altres dos contenidors. Vaig haver de situar el contenidor on hi havia la nau a dalt del tot, res més acabar la capçalera  i el  `<div>` amb la imatge de la lluna en png. abaix del tot ja que si no em sortia la lluna a dalt del tot. Amb el document _css_ vaig reduir les imatges i col·locar-les on volia. **Hi ha un problema amb la lluna. Quan estic descarregant alguna cosa amb el navegador i surt la descarrega abaix la lluna es desplaça cap adalt.** _Se que es perquè està  en posició fixa però si la pos en posició estàtica tot es desquadra. Agrairia que em diguessis com posar-ho bé._

Finalment vaig afegir el fons de pantalla al _css_ i crear dos htmls bàsics amb la informació sobre els controls. 
