# AI Allegro

**AI Allegro** to rozwijana aplikacja wspierająca sprzedawców platformy Allegro w codziennym zarządzaniu sprzedażą, obsłudze klientów oraz przygotowywaniu ofert z wykorzystaniem sztucznej inteligencji.

Celem projektu jest ograniczenie powtarzalnych czynności, ułatwienie pracy z danymi sklepu oraz wspieranie sprzedawcy w podejmowaniu decyzji.

## Funkcjonalności

Projekt obejmuje rozwijane moduły i obszary funkcjonalne:

- **Oferty i produkty** — identyfikacja produktów, analiza informacji, przygotowywanie tytułów, parametrów, opisów i zdjęć ofert z wykorzystaniem AI.
- **Obsługa klientów** — analiza wiadomości i kontekstu zamówień oraz przygotowywanie propozycji odpowiedzi do zatwierdzenia przez użytkownika.
- **Zamówienia i przesyłki** — pobieranie i prezentowanie informacji o zamówieniach, płatnościach oraz statusach dostawy.
- **Analiza sprzedaży** — planowane funkcje wspierające interpretację danych, identyfikację problemów i wskazywanie obszarów wymagających uwagi.
- **Automatyzacja pracy** — rozwijanie narzędzi usprawniających powtarzalne zadania sprzedawcy.

Poszczególne moduły znajdują się na różnych etapach rozwoju. Nie wszystkie opisane funkcjonalności są obecnie dostępne.

## Integracja z Allegro

AI Allegro komunikuje się z platformą Allegro za pośrednictwem oficjalnego REST API.

Integracja może obejmować, zależnie od przyznanych uprawnień:

- Odczyt i zarządzanie ofertami sprzedaży.
- Pobieranie ustawień i zasobów konta sprzedawcy.
- Odczyt zamówień, płatności oraz informacji o przesyłkach.
- Dostęp do wiadomości związanych z obsługą klientów.
- Pobieranie informacji o koncie użytkownika.

Połączenie z kontem Allegro odbywa się za pomocą autoryzacji OAuth 2.0. Aplikacja nie wymaga przekazywania jej hasła do konta Allegro.

## Wykorzystanie sztucznej inteligencji

AI Allegro wykorzystuje sztuczną inteligencję do analizy dostępnych informacji i przygotowywania propozycji działań.

W przypadku czynności wymagających decyzji sprzedawcy, takich jak publikacja ofert czy wysłanie przygotowanej odpowiedzi, użytkownik zachowuje kontrolę nad zatwierdzeniem działania.

## Informacje techniczne

Aplikacja jest obecnie rozwijana i testowana w środowisku lokalnym oraz Allegro Sandbox.

Projekt zakłada dalszy rozwój funkcjonalności i możliwość udostępnienia aplikacji innym sprzedawcom w przyszłości.

AI Allegro jest niezależnym projektem i nie stanowi oficjalnej aplikacji Allegro.

## Kontakt

W sprawach technicznych oraz pytań dotyczących integracji można skontaktować się z administratorem projektu.

**E-mail:** bloomnote.studio@gmail.com

---

**Uwaga:** Repozytorium ma charakter wyłącznie informacyjny i dokumentacyjny. Nie zawiera kodu źródłowego aplikacji, danych użytkowników, tokenów dostępu ani poufnych informacji uwierzytelniających.
