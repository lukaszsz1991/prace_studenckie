### 12 factor

Aplikacje typu **Software-as-a-Service** stały się standardem.  
Jest to model dostarczania oprogramowania, w którym aplikacje są hostowane w chmurze i udostępniane użytkownikom przez Internet. Użytkownicy nie muszą instalować ani zarządzać oprogramowaniem na swoich komputerach - wystarczy im przeglądarka internetowa i dostęp do sieci.  
Wedle twórców, 12 aspektów aplikacji **SaaS** jest metodologią budowania aplikacji, które będą zautomatyzowane, przenoszalne, gotowe do wdrażania, przygotowane pod CI/CD oraz skalowalne.

1.  **Codebase**  
    Jedno źródło kodu śledzone systemem kontroli wersji, wiele wdrożeń.
2.  **Zależności**  
    Jawnie zadeklaruj i wydziel zależności
3.  **Konfiguracja**  
    Przechowuj konfigurację w środowisku
4.  **Usługi wspierające**  
    Traktuj usługi wspierające jako przydzielone zasoby.
5.  **Buduj, publikuj, uruchamiaj**  
    Oddzielaj etap budowania od uruchamiania
6.  **Procesy**  
    Uruchamiaj aplikację jako jeden lub więcej bezstanowych procesów.
7.  **Przydzielanie portów**  
    Udostępniaj usługi przez przydzielanie portów.
8.  **Współbieżność**  
    Skaluj przez odpowiednio dobrane procesy.
9.  **Zbywalność**  
    Zwiększ elastyczność pozwalając na szybkie uruchamianie i zatrzymywanie aplikacji
10. **Jednolitość środowisk**  
    Utrzymuj konfigurację środowisk jak najbardziej zbliżoną do siebie.
11. **Logi**  
    Traktuj logi jako strumień zdarzeń.
12. **Zarządzanie aplikacją**  
    Uruchamiaj zadania administracyjne jako jednorazowe procesy.

#### Podsumowanie

- deklaratywny format pomaga zautomatyzować konfigurację aplikacji
- czysty kontrakt z systemem  
    \-dopasowanie do wdrożenia na nowoczesne chmury
- minimalizacji rozbieżności pomiędzy środowiskami deweloperskimi
- aplikacje powinny skalować się bez większej zmiany narzędzi

#### Więcej

[12factors.net](http://www.12factor.net)
