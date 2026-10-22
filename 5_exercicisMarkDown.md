## Exercici 5
**a) Quina de les dues opcions és més ràpida d'escriure i més fàcil de llegir per a un humà quan s'obre el fitxer en un editor de text pla sense cap visor?**
L'Opció B (Markdown) és molt més ràpida i còmoda tant d'escriure com de llegir. Com que fa servir símbols molt simples (com els guions i els claudàtors) que imiten una llista feta a mà, s'entén a primera vista en el bloc de notes sense que molestin tantes etiquetes d'obertura i tancament com passa a l'XML.

**b) Si l'Opció B és tan simple, per quina raó un sistema informàtic o una base de dades preferiria rebre/processar la informació en format XML (Opció A) quan s'envien dades entre servidors?**
Perquè Markdown només dóna format visual al text, mentre que XML estructura les dades amb etiquetes i atributs clars. Així el servidor sap exactament quin camp és cada dada per guardar-la sense errors.

## Exercici 6
**Per què creus que Markdown és l'estàndard dels README.md a GitHub?**
Perquè és un arxiu de text pla que pesa poc, funciona perfecte amb el control de versions de GitHub el transforma sol en una web neta (amb títols, llistes i codi) sense haver de picar codi HTML.
## Exercici 7
**Quins beneficis té per a tu com a desenvolupador/a trobar la documentació en un fitxer README.md ben estructurat directament a la portada del repositori en lloc d'un fitxer adjunt en PDF o un document XML?**
- **Estalvi de temps:** Es veu directament en entrar al repositori sense haver de descarregar cap PDF a l'ordinador per saber què fa la llibreria.
- **Facilitat per provar el codi:** Pots copiar les comandes d'instal·lació o els exemples de codi amb un sol clic des dels blocs de codi, cosa que en un PDF sol donar problemes de format i en un XML seria molt incòmode de llegir.
- **Sempre actualitzat:** Com que és un fitxer de text dins del projecte, els programadors l'actualitzen a la vegada que pugen canvis al codi.

## Exercici 8
**Raona quin format (XML o Markdown) utilitzaries en cadascun d'aquests dos casos reals de DAM/DAW:**
- **Cas 1 (Apunts o guia d'instal·lació per als companys):** Faria servir **Markdown**, perquè l'objectiu és que altres persones ho llegeixin fàcilment. En pocs minuts pots posar títols, llistes de passos i blocs de codi que queden molt clars visualment.
- **Cas 2 (Fitxer de configuració per a una aplicació):** Faria servir **XML**, perquè qui ha de llegir el fitxer és un programa i no una persona. Amb XML podem separar cada dada dels usuaris dins de la seva etiqueta corresponent perquè l'aplicació ho llegeixi de forma exacta i estructurada.
