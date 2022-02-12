# MTTPP

## Testiranje rada stranice https://www.saucedemo.com/
### Izvršeno je parcijalno testiranje frontenda stranice
* Testirana je prijava na stranicu s ispravnim korisničkim imenom i lozinkom
* Testiran je sustav odjave sa stranice
* Testiran je rad sustava za dodavanje proizvoda u košaricu
* Testiran je rad sustava za dodavanje pa uklanjanje proizvoda iz košarice
* Testiran je rad sustava za dodavanje pa uklanjanje proizvoda iz košarice poslije čega korisnik nastavlja kupovinu


## Upute za pokretanje testova

#### Testovi su pisani u C# programskom jeziku korištenjem NUnit Frameworka i Selenium WebDriver
#### Testovi su implementirani u VisaulStudio 2019 programu

### Programi koje je potrebno imati na računalu:
* VisualStudio 2019 (ili noviji)
* Firefox Browser

### Pokretanje testova:
1. Klonirajte repozitorij sa linka https://github.com/Aplexas99/MTTPP/
2. Pokrenuti **MTTP.sln** datoteku
3. Pokrenuti testove klikom na **Run All Test** unutar **Test** (Test->Run All Tests)
4. Ako želimo pokrenuti pojedinačno neki test otvorimo **Test Explorer** unutar **Test** (Test->Test Explorer)

### Dodavanje paketa
#### Ukoliko se iz nekog razloga nisu automatski dodali paketi koji se nalaze u *packages* folderu na repozitoriju potrebno ih je ručno instalirati
1. Kliknemo na **Manage NuGet Packages** unutar taba **Project** (Project->ManageNuGet Packages)
2. Kliknemo na prvi tab **Browse**
3. Pojedinačno nađemo i instaliramo sljedeće pakete:
	* NUnit
	* NUnit3TestAdapter
	* Selenium Support
	* Selenium WebDriver
	* Selenium WebDriver Gecko Driver
	
