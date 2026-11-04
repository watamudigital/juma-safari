# Juma Safari — Demo sito web

Landing page dimostrativa mobile-first per un possibile sito dedicato a Juma, ispirata alla struttura di offerta di Discovery Kenya con Fragola ma con grafica e contenuti originali.

## Come provarla

Aprire `index.html` in un browser con accesso a Internet. Le fotografie e Google Fonts sono caricati online. Tutto il resto funziona senza server, database o account.

Funzioni incluse:
- Lingue italiano/inglese
- Schede di quattro esperienze indicative: Tsavo East, Taita Hills, Amboseli, Watamu
- Pulsanti delle esperienze che precompilano il modulo
- Generatore di messaggio personalizzato per WhatsApp
- Copia del messaggio e condivisione su WhatsApp
- Responsive mobile e desktop

## Attenzione: prototipo non operativo

- Il contatto diretto non punta ancora al numero di Juma: nel file `index.html`, trovare `const JUMA_WHATSAPP = '';` e sostituire le virgolette vuote con il suo numero verificato nel formato 254...
- Tutti i safari, le durate, le disponibilità, i prezzi, le autorizzazioni e i servizi effettivamente forniti vanno verificati con Juma.
- Nessun prezzo o recensione è stato inventato. Il ritratto di Juma è volutamente un segnaposto.
- Il modulo non invia dati a server. In modalità demo, WhatsApp si apre senza destinatario preimpostato.
- Prima della messa online: controllare la normativa applicabile, la licenza/abilitazione professionale, le condizioni di prenotazione, il trattamento dei dati personali, le policy dei parchi e i partner di trasporto/alloggio.

## Fotografie e attribuzioni

Fotografie esterne recuperate al caricamento dai siti Wikimedia Commons, sotto licenze Creative Commons. Nella pagina i relativi crediti sono presenti nel footer. Le foto sono ritagliate visivamente tramite `object-fit: cover` (non modificano i file sorgente):

1. Hero — Byrdyak, "Red elephant in dirt", CC BY-SA 4.0: https://commons.wikimedia.org/wiki/File:Red_elephant_in_dirt.jpg
2. Tsavo — Filip Rožánek, "Stádo slonů afrických v národním parku Tsavo East, Keňa", CC BY-SA 3.0: https://commons.wikimedia.org/wiki/File:St%C3%A1do_slon%C5%AF_africk%C3%BDch_v_n%C3%A1rodn%C3%ADm_parku_Tsavo_East,_Ke%C5%88a.jpg
3. Taita — Christopher T Cooper, "Loxodonta africana and Aepyceros melampus melampus individuals next to a game viewer vehicle in the Taita Hills Wildlife Sanctuary, Kenya", CC BY 3.0: https://commons.wikimedia.org/wiki/File:Loxodonta_africana_and_Aepyceros_melampus_melampus_individuals_next_to_a_game_viewer_vehicle_in_the_Taita_Hills_Wildlife_Sanctuary,_Kenya.jpg
4. Amboseli — Ninaras, "Amboseli National Park and Mt. Kilimanjaro", CC BY 4.0: https://commons.wikimedia.org/wiki/File:Amboseli_National_Park_and_Mt._Kilimanjaro.jpg
5. Watamu — Queen Asali, "Mida Creek", CC BY 4.0: https://commons.wikimedia.org/wiki/File:Mida_Creek.jpg

License texts: https://creativecommons.org/licenses/by/4.0/ ; https://creativecommons.org/licenses/by/3.0/ ; https://creativecommons.org/licenses/by-sa/4.0/ ; https://creativecommons.org/licenses/by-sa/3.0/

## Ispirazione commerciale

Discovery Kenya con Fragola: https://discoverykenyaconfragola.com/
Progetto indipendente, non affiliato, con copy e design originali.

## Repository e collaborazione

Questo progetto vive in `watamudigital/juma-safari` (repository privata). La demo è una proposta, non un servizio turistico ancora operativo. Foto autentiche, contatti, disponibilità e autorizzazioni devono essere confermati con Juma. Prima della pubblicazione commerciale verificare privacy e condizioni.
