# Purple Technology - Currency Converter Project 

První verze (částečná) – [Fixer API](https://fixer.io/)
Začal jsem s tvorbou jednoduché aplikace pro převod měn s využitím Fixer API. To ale ve svém bezplatném tarifu podporuje pouze kurzy vztažené k EUR – což znamená, že:
Pokud jsem chtěl převést například USD → CZK, Fixer API mi poskytlo pouze:
kurz EUR → USD
kurz EUR → CZK

A z těchto dvou hodnot jsem vypočítával nepřímo kurz USD → CZK podle vzorce:
(amount / rateFrom) * rateTo

Přestože to funguje, není to oficiálně podporovaný přístup a výsledek nemusí být 100% přesný (hlavně při větších objemech nebo rychlých výkyvech na trhu). Backend ani server nejsou potřeba, ale API vrací pouze kurzy vztažené k EUR.

Spuštění:
Krok 1:
Naklonuj si repozitář https://github.com/Otoman666/Purple-currency-converter-partially.git

Krok 2:
Otevři index.html ve VS Code a použij Live Server (nebo otevři přímo file:///index.html)

Krok 3:
Zadej částku, vybírej měny a potvrď tlačítkem.

[Made by Otto Hyncica 2025]
