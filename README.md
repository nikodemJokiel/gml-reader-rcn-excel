# GML Reader – Konwerter plików GML z RCN do Excela (.xlsx)

**GML Reader** to proste i szybkie narzędzie desktopowe stworzone dla rzeczoznawców majątkowych, geodetów oraz analityków rynku nieruchomości. Program pozwala na błyskawiczną konwersję plików ewidencyjnych **GML z Rejestru Cen Nieruchomości (RCN)** do przejrzystych arkuszy **Microsoft Excel (.xlsx)** – bez konieczności instalowania i obsługi skomplikowanych systemów GIS (takich jak QGIS).

🔗 **Oficjalna strona programu i pełna instrukcja:** [gml-reader](https://gml-reader.pages.dev)
📥 **Pobierz najnowszą wersję:** Przejdź do zakładki [Releases](https://github.com/nikodemJokiel/gml-reader-rcn-excel/releases) lub pobierz ze strony głównej.

---

## Dlaczego warto używać GML Reader

Dane o transakcjach pobierane z powiatowych portali mapowych (Geoportal, PODGiK, Geo-Info i.Rzeczoznawca, e-mapa) są udostępniane w formacie `.gml`, którego nie da się bezpośrednio otworzyć w Excelu. GML Reader automatyzuje ten proces:

* **Brak wiedzy GIS:** Nie musisz znać struktury baz danych przestrzennych ani konfigurować warstw. Przeciągasz plik i otrzymujesz gotową tabelę.
* **Pełne bezpieczeństwo danych:** Wszystkie operacje odbywają się offline (lokalnie na Twoim komputerze). Pliki z aktami i cenami transakcyjnymi nigdy nie są wysyłane na zewnętrzne serwery.
* **Automatyczny podział transakcji:** Program sam rozdziela dane na osobne zakładki w Excelu: **Działki**, **Budynki** oraz **Lokale**.
* **Obsługa transakcji wieloprzedmiotowych:** Sprzedaż wielu działek lub lokali w jednym akcie notarialnym jest poprawnie agregowana w czytelnych komórkach z zachowaniem spójności danych.
* **Słowne nazwy gmin i obrębów:** Automatyczne tłumaczenie kodów TERYT na pełne nazwy miejscowości i obrębów ewidencyjnych.
* **Konwersja seryjna (wsadowa):** Możliwość przetworzenia kilkudziesięciu plików z różnych powiatów jednym kliknięciem.

## Obsługiwane formaty danych przestrzennych

Oprócz standardowych plików **GML** zgodnych ze schematami aplikacyjnymi RCWiN, program obsługuje również:
* GeoPackage (`.gpkg`)
* Shapefile (`.shp`)
* GeoJSON (`.geojson`)
* Keyhole Markup Language (`.kml`)

## Jak otworzyć plik GML z RCWiN w Excelu? (Instrukcja)

1. Pobierz instalator z sekcji [Releases](https://github.com/nikodemJokiel/gml-reader-rcn-excel/releases) lub ze strony [gml-reader](https://gml-reader.pages.dev/download).
2. Uruchom program **GML Reader** na komputerze z systemem Windows.
3. Wybierz pobrany z powiatu plik `.gml` (lub cały folder z plikami).
4. Dostosuj kolejność i widoczność kolumn według własnych preferencji w zakładce **Kolmny Excela**.
5. Kliknij **Konwertuj** – program wygeneruje gotowy plik `.xlsx`.

## Wersja darmowa i licencjonowanie

Program działa w modelu freemium. Możesz go pobrać i używać całkowicie za darmo bez aktywacji klucza:
* **Wersja darmowa:** Umożliwia eksport do **7 transakcji na jeden arkusz Excela** – pozwala to bezpłatnie przetestować poprawność odczytu plików z Twojego powiatu.
* **Pełna licencja:** Znosi limit transakcji i odblokowuje pełną konwersję seryjną. Szczegóły na stronie głównej.

## Kontakt i wsparcie techniczne

Program jest stale aktualizowany i dostosowywany do zmian w strukturach plików GML publikowanych przez poszczególne starostwa powiatowe. Jeśli program nie wczytuje pliku z Twojego regionu lub potrzebujesz dodatkowej kolumny w eksporcie, skontaktuj się z autorem:

* **Strona WWW:** [gml-reader](https://gml-reader.pages.dev)
* **E-mail:** jokiel.nikodem@gmail.com
