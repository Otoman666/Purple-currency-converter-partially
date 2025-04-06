# Purple Technology - Currency Converter Project [Made by Otto Hyncica 2025]

První verze – Fixer API
Začal jsem s tvorbou jednoduché aplikace pro převod měn s využitím Fixer API. To ale ve svém bezplatném tarifu podporuje pouze kurzy vztažené k EUR – což znamená, že:
Pokud jsem chtěl převést například USD → CZK, Fixer API mi poskytlo pouze:
kurz EUR → USD
kurz EUR → CZK

A z těchto dvou hodnot jsem vypočítával nepřímo kurz USD → CZK podle vzorce:
(amount / rateFrom) * rateTo

Přestože to funguje, není to oficiálně podporovaný přístup a výsledek nemusí být 100% přesný (hlavně při větších objemech nebo rychlých výkyvech na trhu). Backend ani server nejsou potřeba, ale API vrací pouze kurzy vztažené k EUR.

Spuštění:
Krok 1:
Otevři soubor index.html přímo v prohlížeči.

Step 2:
Zadej částku, vybírej měny a potvrď tlačítkem.


