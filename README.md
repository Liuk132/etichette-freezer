# Etichette Freezer

Web app per etichettare ciò che va in frigo o in freezer (anche sottovuoto): calcola una data di consumo prudente, stampa l'etichetta via Bluetooth e tiene un inventario.

**App:** https://liuk132.github.io/etichette-freezer/

## Come si usa
1. Apri il link con **Chrome per Android** (serve il Web Bluetooth).
2. Menu ⋮ → **Aggiungi a schermata Home**.
3. Impostazioni → scegli la stampante (Niimbot o Phomemo serie M) e il formato del rotolo.
4. Scrivi cosa stai etichettando: categoria e stato si impostano da soli. Premi **Stampa**.

## Stampanti
- **Niimbot** (B1, B1 Pro, B21, B21 Pro…) tramite [NiimBlueLib](https://github.com/MultiMote/niimblue).
- **Phomemo serie M** (M200, M220, M221, M250, M260): raster ESC/POS via BLE, comandi come nel progetto [phomymo](https://github.com/zachmoshe/phomymo).

## Durate
Valori prudenti basati sulle tabelle USDA/FSIS. In freezer la data indica la qualità migliore, non la sicurezza. Il sottovuoto in frigo non allunga oltre i limiti delle tabelle ufficiali.

L'inventario resta nel telefono (localStorage): usa **Impostazioni → Esporta backup**.
