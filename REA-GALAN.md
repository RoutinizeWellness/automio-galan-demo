# REA de GALÁN (fonts públiques, 15/11/2026; ampliat 18/11/2026 amb estudi de producció)

Només informació pública i accessible sense compte.

## Qui són
- Galan Textile Machinery, S.L. (Terrassa, Francesc Oller 91). Fundada el 1940; tercera generació amb Xavier Galan de gerent. Màquines de filatura, retorçat i bobinat per a fibres naturals i sintètics: cordatge tècnic, xarxes de pesca, gespa artificial, automoció, mangueres, geotèxtils.
- Exporten arreu; membres d'amec i d'Eurocord. I+D propi amb patents (Galan Patent System). ISO 9001 (TÜV).
- El gerent declara (2024) que una de les àrees on innoven és el sistema ERP, "que va canviar la manera d'organitzar-nos": ja tenen ERP i cultura d'indústria 4.0.
- Gloria Sánchez Roldán: "Responsable de Compras" (LinkedIn). A la primera conversa va dir que a compres ho gestiona sola, amb poc volum i controlat; l'interès real és la part de producció entrellaçada amb compres. A la reunió del 19/11 hi haurà compres i producció.

Fonts: https://galan.es/sobre-galan/ · https://www.viaempresa.cat/es/empresa/galan-sl-la-reinvencion-de-la-industria-textil_13067_102.html · https://textilespanamericanos.com/textiles-panamericanos/2024/11/galan-vanguardista-espanola-de-maquinaria-textil/ · https://es.gowork.com/galan-textile-machinery-terrassa

## Gamas de màquina reals (galan.es, verificat 18/11/2026)
- REUNIDORAS-RETORCEDORAS DE ARO: PRX (PRX166/9 … PRX375/8), UNI 1X1 (modular, husos 100% independents), CR (CRB225, CRG300, CRG375; CRB fils fins a 26.600 dtex i 8.400 rpm de hus; CRG fins a 60.000 dtex).
- TORCEDORAS DE DOBLE TORSIÓN: UP-TWISTER 2X1 (UPTW550/3, UPTW2250/3 + PRX375/2; 1a i 2a torsió en una sola operació).
- RETORCEDORAS DE ALETAS: RTA (fils gruixuts HMPE, PES, PA; fibres naturals).
- BOBINADORAS: BBCA, BBCA500D, EPCA, BBJ (BBJA, BBJST, BBJAP; bobines petites, canvi de bobina en 10 s).
- ACCESSORIS ORIGINALS GALAN: tubs, bobines (botella/carrete), cursors; enviaments de recanvis en 24 h.
- DISPOSITIVO KISS-ROLL; FILETAS (DEFILÉ, DEROULÉ).

## Indústria 4.0 pròpia (galan.es/industria-40-es, verificat 18/11/2026)
- PC industrial amb panel tàctil (Display CTB) de 7" o 10" en les retorcedores noves.
- Exportació de dades del PLC a l'ERP mitjançant una taula SQL.
- Ajustos: RPM husos, TPM, torsions independents, velocitat d'alimentació, sentit de torsió S/Z, preselecció de metres, comptador individual i col·lectiu, detectors de fil trencat (amb unió de detectors i unió de husos), conicitat; memòria de 100 receptes; historial d'alarmes via USB.
- Terminals i inversors EtherCat.
- Això confirma: ells mateixos connecten PLC→ERP; la demo ha de parlar aquest idioma (receptes, torsió S/Z, detectors, marxa en buit).

## Com fabriquen (producció típica d'un fabricant de maquinària tèxtil sota comanda)
Cada màquina és un projecte únic (MTO/ETO): enginyeria mecànica + elèctrica + automatització. Ruta típica: enginyeria → mecanitzat (CNC) → caldereria/soldadura de bancada → pintura → premuntatge → muntatge mecànic de línia → quadre elèctric i cablejat → automatització (PLC, Display CTB, receptors) → proves (marxa en buit, prova de torsió S/Z amb fil del client, vibració) → desmuntatge parcial, embalatge marítim i expedicció. Compres crítiques de termini llarg: motors, PLC/inversors, rodaments, pneumàtica, mecanitzats externs de bancada.

Fonts del patró de producció/MES per a fabricants de maquinària:
- https://24flow.eu/manufacturing-industries/machine-builders-and-industrial-equipment-manufacturers/ (MES per a machine builders: cada màquina configurada diferent, de subconjunt a prova final)
- https://ibernova.com/mes/sectores/bienes-de-equipo-y-maquinaria-industrial/ (cada màquina és un projecte; control d'enginyeria, fabricació i muntatge)
- https://www.odoo.com/app/manufacturing-features (BOM multinivell, rutes, centres de treball, capacitat/OEE, controls de qualitat)
- https://planeofabricacion.com/sectores-erp-fabricacion-maquinaria/ · https://skyplanner.ai/es/programacion-produccion-maquinaria/

## Marcas reals usades a la demo (verificables)
Siemens SIMATIC S7-1200 / SIMOTICS / SINAMICS (siemens.com), SKF (skf.com), Gates Poly Chain (gates.com), Festo (festo.com), Schneider Electric (se.com). Empreses proveïdores de la demo: fictícies (marcades com a dades d'exemple).

## Ressenyes i opinions
- GoWork: 4,2/5 (11 valoracions, 16 ressenyes), gairebé totes d'empleats/candidats (jornada dl-dj, ambient). Cap queixa pública sobre compres o proveïdors.

## Si ja treballen amb algú
- Ja tenen ERP (declaració pública del gerent) i el PLC de les màquines exporta dades a l'ERP via SQL. No s'ha trobat cap consultora d'automatització de compres publicada. Conseqüència: posicionar-se com a capa de coordinació a sobre de l'ERP, no com a substitut.

## Per què aquesta demo (v7, manual i extensa)
- El centre és la sincronització compres ↔ producció: cada ordre de fabricació mostra el material pendent, quan arriba i què passa si una compra es mou; i la capacitat dels centres de treball marca el lliurament.
- Aprovacions mixtes: algunes decideix compres (seguiments, comanda nova, reclamació), d'altres producció (replanificar una OF, validar una substitució, tancar una NC). Res s'aplica sol.
