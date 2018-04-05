# ESCRiBA

### [ca]  El formen un conjunt d'algorismes per fer cal·ligrames: imatges generades tipogràficament


`ESCRiBA_cargol_lacarrega.ps`

Aquesta versió del codi deriva d'un experiment de gramàtica generativa (_%%UCarrion @BotCarrion_) i amb l'impuls de la plataforma d'**#ArtistesDelaRepública** ens afegim a l'acció proposada pel col·lectiu d'Artistes de la Garrotxa, que planteja fer interpretacions del quadre «La Càrrega» d'en *Ramon Casas i Carbó*.

L'obra generada duu el títol genèric «**la doble espiral de La Càrrega**»

Treballarem a partir d'una imatge cedida pel Museu Comarcal de la Garrotxa, que és on es troba exposada l'obra original.

N'hem generat tres resultats gràfics que, descrits per ordre de complexitat, són:

1. `laDobleEspiralDeLaCarrega.pdf`

![detall del cal·ligrama «la doble espiral de La Càrrega»](https://github.com/marcantonifemfum/ESCRiBA/blob/master/detallDobleEspiralDeLaCarrega.png)

   Cal·ligrama de gran complexitat, doncs posa al límit els recursos de la màquina i el visualitzador de PDF que l'obre (p.e. els que utilizen els navegadors d'Internet o l'*AdobeReader*). Desaconsellem obrir-lo en un dispositiu mòbil o dins un navegador. Degut a l'alta densitat de text, composat en una línia corba, les funcions de cerca de paraules d'aplicacions com l'*AdobeReader* es col·lapsen i deixen de funcionar.
 
   Tipografies utilitzades: *Cinta-Heavy Italic* (per l'espiral de les víctimes) i *WerdetScript Regular* (per l'espiral dels botxins), del tipògraf de Les Borges Blanques, [Josep Patau Bellart][12]
 
   Els textos, que fan la funció dels píxels d'imatge, van endreçats en dues espirals concèntriques (víctimes i botxins).

   **L'espiral de les víctimes**, es proveeix de continguts textuals (escrits només una vegada) dels recursos següents:
   
   La [Llista de Reparació Jurídica de Víctimes del Franquisme (1938-1980)][1] publicades per l'Arxiu Nacional de Catalunya, filtrades i generades via `llegeixCSVopenData_escriuArrays.ps` [vegeu el projecte faSantJaume][2] …i ordenades per dones/homes/persones jurídiques, té actualment més de seixanta-sis mil registres.
   
   El Llistat d'ens i persones represaliades per l'Estat Espanyol, entre 2015 i 2018 a Catalunya, per convocar i participar del dret democràtic de votar en el referèndum d'autodeterminació i creació de la República, l'1 d'octubre de 2017.
   
   S'ha fet un buidat manual dels més de 800 noms d'ens i persones de les següents fonts:
   * L'informe [El Minotaure del 78][3]
   * [Inventari de d'anys dels Servidors Públics de Catalunya][4]
   * L'informe [1-O. Llibertat d'informació a la corda fluixa][5]
   * [712 alcaldies investigades][6]
   
   **L'espiral dels botxins**, es proveeix de continguts textuals (repetits set vegades) dels recursos següents:
   
   Interlocutòries i resolucions de jutges i fiscals espanyols que han provocat els darrers empresonaments, exilis, multes, destitucions, tancaments de pàgines web, escorcolls, censures i repressió policial a la desobediència civil catalana:
   * [Nota de premsa de la Fiscalia de l'Audiència Nacional d'investigació dels CDRs][7] (abril 2018)
   * [Interlocutòria del jutge Llarena, de presó incondicional als Consellers Dolors Bassa, Jordi Turull, Raül Romeva, Josep Rull i la presidenta del Parlament, Carme Forcadell][8] (23 de març de 2018)
   * [Interlocutòria del jutge Llarena, de retirada de l'Euroordre contra el President de la Generalitat][10] (22 de gener de 2018)
   * [Querella del Fiscal General de l'Estat, José Manuel Maza, contra tot el Govern de la Generalitat][9] (30 d'octubre de 2017)
   * [Requeriment del Fiscal General de l'Estat, José Manuel Maza, contra els 712 alcaldes col·laboradors del Referèndum d'Autodeterminació de l'1 d'octubre de 2017][11] (13 de setembre de 2017)


2. `lEspiralDeLaCarrega_victimes1936-2018.pdf`

![detall del cal·ligrama escrit amb les víctimes 1936-2018]()

   Cal·ligrama construït exclusivament amb els recursos textuals de les víctimes, descrits anteriorment a `laDobleEspiralDeLaCarrega.pdf`, escrits només una vegada. Menys complex, pot obrir-se en un dispositiu mòbil i no fa un ús tant intensiu dels recursos del visualitzador de PDF. Per exemple, l'*AdobeReader* ja permet fer-hi cerques textuals sense col·lapsar.

3. `lEspiralDeLaCarrega_victimes2015-2018.pdf`

![detall del cal·ligrama escrit amb les víctimes 2015-2018]()

   Cal·ligrama construït amb els recursos textuals de les darreres víctimes 2015-2018, descrits anteriorment a `laDobleEspiralDeLaCarrega.pdf`, escrits només una vegada. Molt lleuger i operatiu.

[1]: http://anc.gencat.cat/ca/detall/noticia/La-llista-de-reparacio-juridica-de-victimes-del-franquisme-en-dades-obertes
[2]: https://github.com/marcantonifemfum/faSantJaume
[3]: http://cup.cat/sites/default/files/el_minotaure_del_78_revisat_alta_mod.pdf
[4]: https://www.servidorscat.cat/persones-afectades
[5]: https://www.media.cat/wp-content/uploads/2017/12/Informe_1-O_CAT.pdf
[6]: http://www.municipisindependencia.cat/wp-content/uploads/2017/09/Llistat_ajuntaments_decret6setembre_1209AMI.16.00.pdf
[7]: http://beteve.cat/wp-content/uploads/2018/04/Nota-premsa-fiscalia-Audiencia-Nacional.pdf
[8]: http://www.lavanguardia.com/politica/20180323/441870715986/auto-juez-llarena-carcel-turull-rull-romeva-bassa-forcadell.html
[9]: https://www.scribd.com/document/362996220/Querella-del-Fiscal-General-del-Estado-contra-Puigdemont-Junqueras-y-el-resto-de-consellers-cesados
[10]: http://www.poderjudicial.es/stfls/TRIBUNAL%20SUPREMO/DOCUMENTOS%20DE%20INTER%C3%89S/TS%20Penal%20auto%2022%20enero%202018.pdf
[11]: https://www.elnacional.cat/uploads/s1/25/24/44/6/FGE.-13.09.2017.pdf
[12]: http://www.tipopepel.com
