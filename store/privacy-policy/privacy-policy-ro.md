# Politica de confidențialitate — Hilitely

**Ultima actualizare:** 7 noiembrie 2026

Această politică descrie modul în care extensia Chrome **Hilitely** („Extensia”) tratează informațiile.

## Cine oferă Extensia

Extensia este publicată de **PeterShift**.
Contact: **petershift.dev@gmail.com**

## Ce face Extensia

Pe un site pe care îl activați, Extensia evidențiază un fragment pe care îl selectați și găsește din nou acea evidențiere după o reîncărcare sau după o modificare a paginii, după cuvinte, nu după locul lor în așezarea paginii. Notele, etichetele și biblioteca de citate rămân pe acest calculator.

## Ce stochează Extensia

Când evidențiați un text, Extensia salvează o înregistrare pe calculatorul dumneavoastră:

- textul citatului și aproximativ 100 de caractere înainte și după el, pentru ca evidențierea să poată fi găsită din nou;
- adresa paginii, adresa canonică dacă pagina o declară și titlul paginii;
- culoarea, precum și nota și etichetele, dacă le scrieți;
- când a fost creată și modificată evidențierea și dacă a fost găsită pe pagină data trecută.

Setările rămân și ele pe acest calculator: ultima culoare aleasă, dacă cursorul trece în câmpul de notă, cum sortează biblioteca site-urile și ce site-uri activate le-ați oprit.

## Unde ajung datele

Nicăieri. Evidențierile rămân în browser, în baza de date proprie a Extensiei, pe acest calculator. Extensia nu are server, cont sau analitice. Extensia nu face cereri de rețea. Nu primim niciodată evidențierile, notele sau adresele paginilor pe care le citiți.

## Ce site-uri poate citi

Extensia nu cere să citească toate site-urile. Rulează numai pe site-urile pe care le activați din pictograma din bara de instrumente, câte un site, prin dialogul de permisiuni al Chrome. Până atunci, nu adaugă nimic pe pagină.

Oprirea unui site îl pune pe pauză. Evidențierile dispar din filele deschise ale acelui site, iar scriptul nu mai pornește acolo până nu reactivați site-ul. Permisiunea Chrome rămâne, așa că reactivarea nu cere accesul a doua oară. „Remove access to this site” retrage permisiunea. Data viitoare când activați acel site, Chrome întreabă din nou. Citatele salvate rămân în bibliotecă în ambele cazuri.

## Copii de rezervă

Un fișier de rezervă este creat numai când alegeți Download backup. Este salvat acolo unde browserul salvează descărcările. Importul unei copii citește un fișier pe care îl alegeți. Niciuna dintre acestea nu este încărcată nicăieri.

## Ștergerea datelor

Ștergeți o evidențiere de pe pagină sau din bibliotecă, ori folosiți Delete all on this site în bibliotecă. Eliminarea Extensiei șterge toate datele ei locale prin curățarea obișnuită a browserului.

## Permisiuni

| Permisiune | De ce este cerută |
| --- | --- |
| `storage` | Salvează setările pe acest calculator: ultima culoare de evidențiere, dacă cursorul trece în câmpul de notă, ce site-uri activate le-ați oprit și cum sortează biblioteca site-urile. Citatele sunt păstrate în baza de date proprie a Extensiei; această permisiune nu le stochează. |
| `activeTab` | Când apăsați pictograma din bară, fereastra citește adresa filei curente, ca să arate comutatorul acelui site și să parcurgă evidențierile de pe pagină. |
| `scripting` | Pornește evidențierea în fila curentă imediat după ce activați site-ul și în filele acelui site deja deschise, fără să reîncarce pagina. Când opriți site-ul, scoate evidențierile din acele file. |
| Acces la site-uri | Nu este acordat la instalare. Chrome cere câte un site, prima dată când îl activați. Evidențierea rulează numai pe site-urile pe care le-ați permis și nu le-ați oprit. Oprirea o oprește pe acel site și păstrează permisiunea. „Remove access to this site” o retrage. |

## Cod la distanță

Extensia rulează numai fișierele locale din pachet. Nu descarcă și nu execută JavaScript din rețea.

## Utilizare limitată

Datele sunt folosite numai ca să arate din nou evidențierile și să le listeze în bibliotecă. Nu sunt vândute, nu sunt transferate nimănui, nu sunt folosite pentru publicitate sau pentru evaluarea bonității, și nicio persoană nu le citește. Utilizarea acestor informații respectă politica Chrome Web Store User Data Policy (https://developer.chrome.com/docs/webstore/program-policies/limited-use), inclusiv cerințele Limited Use.

## Modificări

Dacă o versiune ulterioară începe să trimită date undeva, această politică o va spune înainte ca acea versiune să fie publicată, iar Extensia vă va întreba mai întâi.

## Contact

Întrebări despre această politică: **petershift.dev@gmail.com**
