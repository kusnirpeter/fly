FLY KILLER – Netlify Blobs verzia

1. Otvor https://app.netlify.com/ a vytvor projekt cez Import an existing project (Git).
2. Nahraj obsah priecinka do GitHub repozitara a prepoj ho s Netlify.
3. Netlify automaticky nainstaluje @netlify/blobs a nasadi funkciu /api/counter.
4. Obaja hraci otvoria rovnaku Netlify URL. Zaznamy su spolocne a pretrvavaju.

POZOR: Jednoduche manualne pretiahnutie ZIP/HTML do Netlify Drop neinstaluje zavislosti a nemusi spravne nasadit serverless funkciu. Odporucany je Git deploy alebo Netlify CLI build/deploy.

Netlify Blobs: kazdy zasah je samostatny zaznam s UUID, aby sa pri sucasnych kliknutiach neprepisovalo jedno spolocne cislo. Zapis nie je transakcny; sucasne opravy -1 mozu zriedkavo vytvorit zaporne skore. Nevyzaduje externu DB.

Bez prihlasovania: kazdy s URL moze pridavat/uberat zasahy aj menit mena. Verejne nasadenie pouzivaj len na neformalne ucely. Ulozisko moze casom rast – kazdy klik vytvara zaznam.

Farby su inspirovane zeleno-modrou vizualnou identitou SEPS, nejde o oficialnu firemnu aplikaciu.
