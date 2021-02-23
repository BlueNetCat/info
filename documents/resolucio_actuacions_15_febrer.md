# Resultats propostes del 15 de Febrer 2021
Es va obrir [un procés per enviar propostes a través d'un formulari](propostes_actuacions_15febrer.md) per a que els grups de la Xarxa enviessin propostes per dinamitzar i valoritzar les seves dades. El 15 de Febrer es van recollir les propostes rebudes, que estan resumides aquí. En aquest document s'expliquen les propostes i es justifica el procés de selecció i l'ordre d'execució. La informació de les propostes està resumida per simplificar el document. En cas de voler tenir tota la informació, poseu-vos en contacte amb gllorach (at) fbg.ub.edu.

## Propostes rebudes
| Acrònim        | Títol                       | Grup de recerca | Responsable      | 
| --------------- | ---------------           | ---------------  |  --------------- | 
| VISAP          | Servei d'Assessorament Pesquer | CSIC (ICATMAR)   | Jordi Ribera |
| OBSEA data     | OBSEA data                 | UPC4 (SARTI-MAR)   |  Joaquin del Rio |
| CLIMACAT       | Clima Marítim de Catalunya   | CSIC6 (Physical and technological oceanography) |Joaquim Ballabrera |
| MARCAT         | - | CSIC11 (BEC) |Jordi Isern |

## Descripció de les propostes
### VISAP
- Objectiu: Proporcionar una eina per conèixer l'estat de la pesca a Catalunya i poder-la gestionar.
- Necessita: Possibilitat de filtrar les dades segons diferents criteris (data o any, zona, port, modalitat de pesca, espècie, etc.), mostrar gràfiques, mostrar mapes (capes), descarregar dades.
- Dades pròpies: Dades del mostreig pesquer a la costa catalana.

### OBSEA data
- Objectiu: divulgació de l'estació, fer les dades disponibles al públic en general.
- Necessita: que les dades històriques siguin accessibles per tothom i que es puguin fer servir en un visualitzador.
- Dades pròpies: 3 tipus: series temporals de variables físiques, imatges submarines i underwater sound (csv, png, jpg, gif, video, audio). El tamany de dades és més gran d'1 TB.


### CLIMACAT
- Objectiu: representar els paràmetres climatològics més representatius del Mar Català al llarg de les estacions annuals.
- Necessita: organitzar les dades en un format estàndard, que les dades siguin accessibles per tothom., posar les dades en una base de dades, que es puguin fer servir en un visualitzador, visualitzar les dades, definir protocols comuns per a les dades.
- Dades pròpies: Dades històriques d'interés climàtic recopilades pels diferents grups de la xarxa marítima. Dades in-situ (obtingudes durant campanyes, sortides de camp, seguiments, ciència ciutadana i instruments automàtics ancorats i derivants) i remotes (radars costaners, telesensors i plataformes en satèl.lits). Tipus: geoJSON, KML o KMZ, xlsl (Excel), csv, netCDF, GIS. Més gran d'1 TB.

### MARCAT
Aquesta proposta és confidencial.

## Criteris de selecció
Els criteris de selecció estan definits en la secció ["Com es seleccionen els projectes?"](propostes_actuacions_15febrer.md#com-es-seleccionen-els-projectes) del document on s'explica com enviar propostes. En aquest apartat s'han donat punts a cada proposta, segons la informació que hem rebut. En cas de voler una explicació més extensa, podeu posar-vos en contacte amb gllorach (at) fbg.ub.edu. 

| Acrònim        | TRL i SRL  | Sinergies i col·laboració | Basats en explotació de dades pròpies | Dades obertes |  Accessibilitat i maduresa de dades | Ajuda tècnica | Associat a un projecte o contracte |
| :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
| VISAP          | &#x1F535; &#x1F535; | &#x1F535; &#x1F535; | &#x1F535; &#x1F535; &#x1F535;| &#x1F535; | &#x1F535; &#x1F535; | &#x1F535; &#x1F535; | &#x1F535; &#x1F535;&#x1F535; |
| OBSEA data     | &#x1F535; |   | &#x1F535; &#x1F535; &#x1F535; | &#x1F535; | &#x1F535; &#x1F535; &#x1F535; | &#x1F535; | &#x1F535; |
| CLIMACAT       | &#x1F535; | &#x1F535; &#x1F535;  | &#x1F535; | &#x1F535; |  &#x1F535; | &#x1F535; |  &#x1F535; |
| MARCAT         | &#x1F535; | &#x1F535; &#x1F535;  |  &#x1F535; | &#x1F535; |   &#x1F535; | &#x1F535; | |

## Ordre d'execució de les propostes i actuacions
La primera proposta que es farà serà VISAP. El visualitzador està basat en dades són pròpies que encara no s'han distribuït / publicat. Varis grup del CSIC estàn involucrats i el visualitzador forma part d'un projecte (ICATMAR). La segona proposta que es farà serà donar suport a la plataforma OBSEA per a que es puguin fer peticions a la BBDD de forma automàtica des del dashboard. La tercera proposta depèn més aviat de dades d'agències com METEOCAT i AEMET, tot i que les dades pròpies poden donar un valor afegit respecte altres visualitzadors. La quarta proposta és confidencial. En la cinquena proposta s'inclouran dades climatològiques a les dades de pesca, per poder relacionar l'estat del mar amb la pesca. Aquesta última actuació es beneficiarà dels serveis de la proposta CLIMACAT. L'ordre actual d'execució és aquest:

1. VISAP (fase 1, només dades de pesca). Actuació: es crearà un visualitzador de les dades de pesca. Aquest visualitzador rebrà les dades d'un web service. Es donarà suport a la creació d'aquest web service al personal tècnic de la proposta. 

1. OBSEA data. Actuació: es crearà un web service que faci peticions a la BBDD per consultar i descarregar dades històriques. Es donarà suport a la creació d'un menú per accedir a aquest web service des de la web de l'OBSEA.

1. CLIMACAT. Actuació: a definir.

1. MARCAT. Actuació: confidencial.

1. VISAP (fase 2, inclou dades climatològiques). Actuació: s'inclouran dades climàtiques al visualitzador.
 
