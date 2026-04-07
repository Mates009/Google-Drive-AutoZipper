# Google Drive AutoZipper 🗜️☁️

Tato aplikace s grafickým uživatelským rozhraním (GUI) napsaná v Pythonu slouží k lokální kompresi vybraných souborů a adresářů do formátu ZIP a jejich následnému automatickému nahrání na Google Disk.

Projekt demonstruje schopnost pracovat s externími API, řešit autentizaci a využívat asynchronní programování pro plynulý chod desktopové aplikace.

## 🚀 Hlavní funkce

* **Grafické rozhraní (Tkinter):** Uživatelsky přívětivé prostředí pro výběr souborů a složek s ukazatelem průběhu (Progress bar).
* **Asynchronní běh (Multithreading):** Operace komprese a nahrávání běží v samostatném vlákně (`threading`), což zajišťuje, že GUI aplikace během náročných procesů nezamrzá.
* **Google Drive API:** Bezpečné nahrávání souborů přímo do cloudu s využitím `googleapiclient`.
* **OAuth 2.0 Autentizace:** Implementováno bezpečné přihlašování s lokálním ukládáním tokenu (`token.pickle`) pro pohodlnější opakované používání.
* **Rekurzivní ZIPování:** Algoritmus správně prochází složky a zachovává jejich vnitřní adresářovou strukturu uvnitř výsledného archivu.

## 🛠️ Použité technologie a knihovny

* **Python 3.x**
* `tkinter` (Standardní GUI knihovna)
* `threading` (Správa vláken)
* `zipfile`, `shutil`, `os` (Operace se souborovým systémem a archivace)
* `google-api-python-client`, `google-auth-httplib2`, `google-auth-oauthlib` (Komunikace s Google Cloud službami)

## ⚙️ Instalace a spuštění

1. **Naklonování repozitáře:**
   ```bash
   git clone [https://github.com/TVOJE_UZIVATELSKE_JMENO/Google-Drive-AutoZipper.git](https://github.com/TVOJE_UZIVATELSKE_JMENO/Google-Drive-AutoZipper.git)
   cd Google-Drive-AutoZipper# Google-Drive-AutoZipper
