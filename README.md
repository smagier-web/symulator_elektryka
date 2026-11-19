# ⚡ Symulator łączenia przewodów

Interaktywny symulator do nauki instalacji elektrycznych: puszki rozgałęźne, łączniki, rozdzielnica, trójfaza 400 V, projekt mieszkania i pomiary. **86 zadań** w 10 działach.

Działa w każdej przeglądarce (telefon, tablet, komputer), także **offline**, i można go zainstalować na telefonie jak aplikację.

## Co jest w środku

- **Zadania:** podstawy, średnie, zaawansowane (schodowy, krzyżowy, 4 miejsca), hotel i klatka schodowa, rozdzielnica (B10, B16, RCD), trójfaza (gniazdo 400 V, silnik, kierunek obrotów), projekt mieszkania (2 puszki), pomiary miernikiem, pomiary ochronne, „znajdź błąd”.
- **Symulacja prądu:** włączasz zasilanie, przełączasz łączniki, lampy świecą, silnik się kręci, przy zwarciu wybija zabezpieczenie, a przy błędzie N/PE różnicówka.
- **Miernik z 4 trybami:** napięcie i ciągłość, rezystancja izolacji, pętla zwarcia Zs, test RCD.
- **Realne ograniczenia:** złączki WAGO na 3 albo 5 przewodów, przekrój 1,5 albo 2,5 mm², kolory przewodów (także L1/L2/L3).
- **Motywacja:** gwiazdki, rangi (od Praktykanta do Inspektora SEP), rekordy czasu, egzamin z oceną 1–6, quiz (21 pytań), słowniczek, ranking graczy na urządzeniu.

## Jak opublikować na GitHub Pages (bez programowania)

1. Zaloguj się na [github.com](https://github.com) i kliknij **New repository**. Nazwa: np. `symulator-elektryka`, ustaw **Public**, kliknij **Create repository**.
2. Kliknij **uploading an existing file** i przeciągnij **wszystkie pliki z tego folderu** (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`, `.nojekyll`). Kliknij **Commit changes**.
3. Wejdź w **Settings → Pages**. W „Source” wybierz **Deploy from a branch**, branch **main**, folder **/ (root)** i kliknij **Save**.
4. Po 1–2 minutach strona będzie pod adresem:
   `https://TWOJA-NAZWA.github.io/symulator-elektryka/`

> Plik `.nojekyll` jest ukryty (zaczyna się od kropki). Jeśli system go nie pokazuje, możesz go pominąć – strona i tak zadziała.

## Instalacja na telefonie

Otwórz adres strony w telefonie:
- **Android (Chrome):** menu ⋮ → **Zainstaluj aplikację** / **Dodaj do ekranu głównego**.
- **iPhone (Safari):** przycisk Udostępnij → **Do ekranu początkowego**.

Po pierwszym otwarciu symulator działa też bez internetu.

## Postępy i ranking

Gwiazdki, rekordy i wyniki egzaminów zapisują się **w przeglądarce na danym urządzeniu**. W sekcji „🏆 Ranking” każdy gracz wpisuje swoją ksywkę, ma własne postępy i porównuje się z innymi grającymi na tym samym urządzeniu.

## Aktualizacja

Żeby wgrać nową wersję, w repozytorium kliknij `index.html` → ikona ołówka lub **Add file → Upload files**, wgraj nowy plik i zatwierdź. Przy zmianach warto podbić numer `symulator-v1` w `sw.js` (np. na `v2`), żeby telefony od razu pobrały nową wersję.

---

⚠️ To model edukacyjny. Prace przy prawdziwej instalacji wykonuje osoba z uprawnieniami (SEP), po wyłączeniu zasilania i sprawdzeniu braku napięcia.
