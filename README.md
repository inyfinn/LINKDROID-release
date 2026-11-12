# LinkDroid

**Telefon z Androidem i komputer z Windows jako jedno urządzenie.** Wiadomości, powiadomienia, zdjęcia, pliki, schowek i ekran telefonu na komputerze, a pliki i ekran komputera na telefonie. Działa w domu przez Wi-Fi i poza domem przez internet albo dane komórkowe: samo, bez konta i bez konfiguracji.

<p align="center">
  <img src="docs/img/uklad1-jasny.jpg" alt="LinkDroid, ekran główny, motyw jasny" width="49%">
  <img src="docs/img/uklad1-ciemny.jpg" alt="LinkDroid, ekran główny, motyw ciemny" width="49%">
</p>

## Pobierz

Najnowsza wersja jest w zakładce **[Releases](../../releases/latest)**:

- **Windows 10 i 11:** `LinkDroid_<wersja>_x64-setup.exe`. Jeden instalator, wszystko w środku.
- **Android 10 lub nowszy:** `LinkDroid-<wersja>.apk` (albo zeskanuj kod QR, który pokaże aplikacja na komputerze).

Windows 11 z włączoną ochroną „Smart App Control” może zablokować instalator, bo nie jest podpisany certyfikatem producenta. Wersja z Microsoft Store (w przygotowaniu) jest podpisana przez Microsoft. Program zabezpieczający (np. Bitdefender) może blokować LinkDroid po nazwie pliku: aplikacja sama to wykryje i pokaże, jak go zezwolić.

Po instalacji komputer pokazuje kod QR, telefon go skanuje i gotowe. Obie aplikacje same się aktualizują.

## Co potrafi

**Połączenie, które po prostu działa**
- W tej samej sieci Wi-Fi łączy się bezpośrednio i najszybciej.
- Gdy telefon jest na LTE albo w innej sieci, łączy się przez internet. Przełącza się samo, bez klikania, i samo wraca do Wi-Fi.
- Połączenie jest szyfrowane od końca do końca kluczami urządzeń. Nikt po drodze nie widzi treści.
- Licznik danych komórkowych pokazuje, ile LinkDroid zużył dziś przez LTE.
- Gdy połączenia nie ma, zaległe rzeczy (np. zrzut ekranu) czekają i dochodzą po ponownym połączeniu.
- Połączenie naprawia się samo: po błędzie, zmianie sieci albo odblokowaniu telefonu aplikacja łączy się ponownie, a przycisk „Połącz ponownie” jest zawsze pod ręką.
- Gdy coś nie działa, „Połącz ponownie” pokazuje sprawdzenie krok po kroku (sieć, internet, telefon, komputer) i konkretną radę, co zrobić.
- Działa także z komputerem w innej sieci, np. w pracy, przez internet, również w sieciach firmowych.
- „Odnów całkowicie połączenie” i kopia ustawień do pliku: naprawa i zapasowa kopia jednym przyciskiem, bez wiedzy technicznej.

**Telefon na komputerze**
- **Dyktowanie przez telefon (Win+H):** naciskasz Win+H na komputerze i mówisz do telefonu. Tekst rozpoznaje klawiatura Gboard (pisanie głosowe Google, z polską interpunkcją), a LinkDroid wpisuje go tam, gdzie masz kursor. Działa bez odblokowywania telefonu, na przyciemnionym ekranie; przerwa na myślenie go nie przerywa, a po około 30 sekundach ciszy kończy się samo. Gdy poprawisz albo skasujesz coś w tekście na telefonie, ta sama zmiana pojawia się na komputerze. Stan pokazuje cienki pasek, który możesz przesunąć myszą. LinkDroid nie nagrywa dźwięku: mikrofonu używa Gboard. Włącz w Ustawieniach, Funkcje.
- **Wiadomości SMS:** czytanie i pisanie z klawiatury komputera.
- **Powiadomienia z telefonu:** w Windows, z przyciskiem „Kopiuj kod” przy kodach SMS i wyciszaniem wybranych aplikacji.
- **Połączenia:** wybieranie numeru z komputera i historia połączeń.
- **Zdjęcia i filmy:** przeglądanie, pobieranie, przeciąganie prosto do folderu, Photoshopa czy innego programu. Przeciągasz od razu, bez czekania: nazwa i rozmiar pojawiają się natychmiast, a zawartość przychodzi z telefonu dopiero w chwili puszczenia. Na ekranie Start kafelek Zdjęcia ma zaznaczanie jak w Eksploratorze (Ctrl, Shift), przeciąganie prosto z kafelka i menu prawego przycisku. Zdjęcie na telefonie usuniesz, przeniesiesz do innego albumu albo zmienisz mu nazwę (F2) prosto z komputera.
- **Wiadomości z dużym „Kopiuj kod”:** kod jednorazowy wykrywany zawsze (także w czatach RCS), dowolny fragment wiadomości zaznaczasz i kopiujesz jak zwykły tekst, na komputerze i w telefonie.
- **Telefon jako dysk w Eksploratorze Windows:** własna litera dysku, miniatury, pojemność telefonu.
- **Ekran telefonu na komputerze ze sterowaniem myszą i klawiaturą,** także w pływającym oknie z ramką telefonu, które przesuwasz po pulpicie.
- **Zrzut ekranu z telefonu** od razu na komputerze: otwórz, zapisz, kopiuj, edytuj.
- **„Znajdź telefon”:** telefon dzwoni, nawet gdy jest wyciszony.

**Komputer na telefonie**
- **Pliki komputera:** wszystkie dyski (C:, D: i inne), z pobieraniem i zapisem.
- **Ekran komputera** na telefonie i proste sterowanie komputerem. Po przybliżeniu palcami obraz jest ostry: telefon mówi komputerowi, jaki wycinek ekranu widać, a komputer wysyła go w pełnej rozdzielczości (na monitorze 4K do 2x tak ostro jak na komputerze), zamiast powiększać zmniejszony obraz.
- **Zdjęcia w telefonie:** podgląd w aplikacji z przewijaniem, ulubione, edycja, udostępnianie; siatka zmieniana dwoma palcami.
- **Zgłoś problem:** formularz w Ustawieniach na komputerze i telefonie.
- **Karta komputera na telefonie:** na ekranie Start przesuwasz z karty telefonu na kartę komputera: rodzaj komputera, zalogowany użytkownik, bateria i ładowanie, sieć, godzina na komputerze, a pod nią przyciski Zablokuj, Uśpij, Wyłącz ekran, Steruj, Wyślij pliki, Wyłącz komputer.
- **Wybudzanie komputera z telefonu** (Wake-on-LAN): przycisk „Wybudź komputer”. Każdy inny włączony komputer z LinkDroid w tej samej sieci przekaże sygnał.

**Powiadomienia zawsze pod kontrolą**
- Odrzucasz w telefonie albo na komputerze: znika w obu miejscach i trafia do historii.
- Udostępnianie ekranu zawsze widać: w powiadomieniu i na ekranie Start jest przycisk „Zakończ udostępnianie ekranu”. Gdy komputer przestaje oglądać, udostępnianie kończy się samo.

**Razem**
- **Wspólny schowek:** tekst i obrazy kopiowane na jednym urządzeniu wklejasz na drugim. Kopiowanie obiektów w Illustratorze, Photoshopie czy PowerPoincie działa normalnie.
- **Spam SMS i numery zablokowane** nie dają powiadomień i są ukryte, z przyciskiem „To nie spam”.
- **Wysyłanie plików** w obie strony, z paskiem przeciągania na górze ekranu Windows.
- **Kilka komputerów naraz:** schowek idzie do wszystkich, przy wysyłce telefon pyta „Na który komputer?”.

**Most w sieci domowej**
- Mały program LinkDroid na stale włączonym urządzeniu w domu (np. Synology NAS w Dockerze) daje stały punkt połączenia i wybudza komputer, gdy jesteś poza domem. Paruje się przez komputer, bez skanowania kodów.

**Wygląd po Twojemu**
- **Czysty, spójny wygląd na komputerze i telefonie:** ekran Start z kartą telefonu i kafelkami „Nowe z telefonu”, pasek boczny z ikonami o równej wielkości, motyw jasny i ciemny, cztery schematy kolorów.
- **Ustawienia jak na telefonie:** lista kategorii (Telefon i połączenie, Funkcje i dane, Aplikacja), każda z krótkim opisem. Wchodzisz w jedną i wracasz strzałką, bez przewijania długiej listy.
- Na telefonie: motyw jasny lub ciemny jednym dotknięciem na górze ekranu Start, powiadomienia aktywne i historia przesuwane palcem.
- Tryb „Dostosuj”: sam wybierasz kafelki (SMS, powiadomienia jednej aplikacji, zdjęcia, filmy, pliki, połączenia, schowek). Ekran wypełnia się treścią na każdym monitorze, od laptopa po 4K.

<p align="center">
  <img src="docs/img/ustawienia-jasny.jpg" alt="LinkDroid, Ustawienia jako lista kategorii, motyw jasny" width="49%">
  <img src="docs/img/ustawienia-ciemny.jpg" alt="LinkDroid, Ustawienia jako lista kategorii, motyw ciemny" width="49%">
</p>

## Czym różni się od „Łącza z telefonem”

| | LinkDroid | Łącze z telefonem |
|---|---|---|
| Konto | Niepotrzebne | Wymaga konta Microsoft |
| Twoje dane | Idą prosto między Twoimi urządzeniami, szyfrowane od końca do końca | Przez usługi Microsoft |
| Ekran telefonu i sterowanie | Każdy telefon z Androidem 10+ | Tylko wybrane modele (m.in. Samsung, Honor) |
| Pliki komputera na telefonie | Tak, wszystkie dyski, z zapisem | Nie |
| Wybudzenie komputera z telefonu | Tak | Nie |
| Telefon jako dysk w Eksploratorze | Tak, z literą dysku i miniaturami | Zależnie od wersji Windows |
| Wygląd | Jasny i ciemny motyw, cztery schematy kolorów, Ustawienia jako czytelna lista kategorii | Stały |
| Wybór, co widać na ekranie głównym | Tryb Dostosuj: kafelki SMS, powiadomienia jednej aplikacji, zdjęcia, filmy, pliki, połączenia, schowek | Stały układ |
| Most w sieci domowej (np. NAS) | Tak: stały punkt połączenia i wybudzanie komputera spoza domu | Nie |
| Stan komputera na telefonie (bateria, sieć, użytkownik) | Tak, karta Komputer na ekranie Start | Nie |
| Licznik danych komórkowych | Tak, „LinkDroid dziś: X MB” | Nie |
| Kilka komputerów naraz z jednym telefonem | Tak, schowek do wszystkich, wybór komputera przy wysyłce | Tak |
| Zrzut ekranu z telefonu na komputerze | Okno z podglądem: Otwórz, Zapisz, Kopiuj, Edytuj, Usuń z cofnięciem | Przez zdjęcia |

Porównanie dotyczy wersji „Łącza z telefonem” dostępnych w październiku 2026 i może się zmienić wraz z jego aktualizacjami.

## Gdy coś nie działa

**Kopiowanie i wklejanie między telefonem a komputerem**
1. Na komputerze zamknij LinkDroid i sprawdź, czy zwykłe Ctrl+C / Ctrl+V działa w Notatniku. Jeśli nie działa, to nie LinkDroid.
   Częsta przyczyna: Linux w Windows (WSL) z oknami WSLg, który przejmuje schowek. Wyłącz WSLg (plik `.wslconfig`, `guiApplications=false`) i zamknij WSL (`wsl --shutdown`).
2. Tekst skopiowany na telefonie dociera na komputer przez usługę dostępności LinkDroid. Jeśli system ją wyłączył (zdarza się po aktualizacji), telefon pokaże powiadomienie: włącz ją w Ułatwienia dostępu, Zainstalowane aplikacje, LinkDroid.
3. Telefon co kilkadziesiąt sekund zmieniający sieć Wi-Fi (np. łączący się z adapterem Android Auto) co chwilę gubi połączenie z komputerem. Wyłącz Bluetooth z takim urządzeniem albo zapomnij tę sieć.
4. Zrzut z Wycinania się nie wkleja: zakończ zawieszony proces SnippingTool, nowy wstanie przy następnym Win+Shift+S.
5. Program zabezpieczający (np. Bitdefender) może blokować LinkDroid po ścieżce pliku: aplikacja pokaże, jak to zezwolić.

Pełna diagnoza krok po kroku (test A/B, dzienniki, skrypt sprawdzający) jest w dokumentacji projektu w repozytorium prywatnym (`docs/features/clipboard.md`, `tools/diag-schowek.ps1`).

## Prywatność

LinkDroid nie ma kont, serwera ani reklam. Urządzenia rozpoznają się po własnych kluczach. Gdy bezpośrednie połączenie przez internet nie jest możliwe, ruch idzie przez publiczny przekaźnik, ale jest zaszyfrowany i przekaźnik nie widzi treści.

Pełne zasady: [Polityka prywatności](PRIVACY.md) i [Regulamin](TERMS.md).

---

Zrzuty pokazują wygląd aplikacji na przykładowych danych.
