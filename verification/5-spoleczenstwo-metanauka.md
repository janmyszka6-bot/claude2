# Weryfikacja: 5. Społeczeństwo, metanauka i wildcard

Weryfikator, data: 2 października 2026. Plik źródłowy: candidates/5-spoleczenstwo-metanauka.md

> **Uwaga o metodzie (ważne dla czytelnika raportu).** Już przy pierwszym wywołaniu WebSearch zwrócił komunikat, że budżet wyszukiwań tej sesji jest wyczerpany (200 z 200, budżet wspólny z wyszukiwaczem). Nie obchodziłem tego limitu (np. przez wyszukiwarki otwierane przez WebFetch). Weryfikację oparłem więc na: (a) samodzielnym otwarciu każdego linku z pliku przez WebFetch, (b) linkach zwróconych przez otwarte strony, (c) metadanych Crossref (api.crossref.org/works/&lt;DOI&gt;), które zawierają też dane bazy Retraction Watch o retrakcjach, korektach i „expressions of concern”, (d) rozwiązywaniu DOI przez doi.org. Konsekwencja: nie mogłem samodzielnie wyszukać nowej krytyki, replikacji ani przedruków zablokowanych newsów. Status retrakcji i korekt sprawdziłem jednak dla każdego papera z DOI.

## Podsumowanie

(w toku: sprawdzone pary 1–6)

## Pary

### 1. Ariely i „sztuczne terminy”: wycofany paper o prokrastynacji: ✅ potwierdzone (pewność: wysoka)
- **Sprawdzone linki:**
  - Newsweek: działa; nagłówek zgodny; Joshua Rhett Miller, 3 IX 2026 (aktualizacja 4 IX 2026); narzędzie nie widzi paywalla.
  - Ynetnews: działa; autor tylko „ynet”; narzędzie nie podało daty; tekst opisuje retrakcję z 2 IX, więc artykuł jest z 2 IX 2026 lub późniejszy (dokładna data niepewna).
  - Poets&Quants: działa; Marc Ethier, 2 IX 2026; nazywa paper i czasopismo.
  - Duke Chronicle: HTTP 403 (potwierdzam).
  - Retraction Watch: działa; Kate Travis, 3 IX 2026.
  - datacolada.org/138 (31 VIII 2026, aktualizacja 3 IX) i /139 (2 IX 2026): działają.
  - PDF autorski (web.mit.edu): działa; przeczytałem s. 219–222.
  - Notka retrakcyjna (sagepub): HTTP 403; retrakcję potwierdza Crossref: oryginał ma tytuł z dopiskiem „RETRACTED”, pole updated-by: Retraction, DOI 10.1177/09567976261488042, 2 IX 2026.
  - Replikacja (sagepub): nieotwierana; metadane i abstrakt z Crossref (DOI 10.1177/09567976261460772).
  - Oświadczenie Arielyego (danariely.com): działa; według narzędzia datowane 7 VIII 2026.
  - Blog Gelmana: nie sprawdzałem ponownie (u wyszukiwacza HTTP 403).
- **News a paper:** Newsweek podaje pełny tytuł papera, rok i czasopismo oraz cytuje notkę retrakcyjną (redakcja nie może już ręczyć za wyniki z powodu replikacji, braku zaufania do danych i analizy Data Colada). Wspomina Data Colada i manuskrypt replikacyjny, ale nie wymienia Wertenbrocha z nazwiska. Około 4–5 akapitów dotyczy Epsteina; brak niezależnych ekspertów (tylko Ariely i Duke). Ynetnews nazywa czasopismo, datę retrakcji i replikację Hyndmana i Bisina; wyraźnie oddziela stanowisko czasopisma (nie da się potwierdzić autentyczności danych) od mocniejszej tezy Data Colada (manipulacja).
- **Fakty:**
  - Tytuł, autorzy (Ariely, MIT; Wertenbroch, INSEAD), Psychological Science 13(3), maj 2002, s. 219–224, DOI 10.1111/1467-9280.00441 → zgodne (Crossref, PDF).
  - Study 1: 99 uczestników executive education na MIT, 48 w sekcji ze sztywnymi terminami i 51 w sekcji z własnymi terminami → zgodne (PDF, s. 220). Drobna rozbieżność: w pliku danych Data Colada liczy 50 i 49 osób (paper sam wspomina o brakach danych).
  - Wynik Study 1: ludzie sami narzucali sobie kosztowne terminy, ale mieli gorsze oceny niż przy terminach zewnętrznych (M = 88,76 vs 85,67, t(97) = 3,03) → zgodne (PDF, s. 221).
  - Study 2: 60 studentów MIT zrekrutowanych z ogłoszenia (to nie byli słuchacze kursu), losowo przydzielonych do 3 warunków, czyli po 20 osób; zadanie korektorskie na tekstach z „generatora postmodernizmu” z 100 wstawionymi błędami → zgodne (PDF, s. 222; DC 138). Doprecyzowanie: liczba 20 wynika z samego papera, nie tylko z Data Colada.
  - Data Colada 138: 136,1 vs 71,1 poprawek, d = 2,5; 18 z 20 osób w warunku z jednym terminem końcowym ma „bliźniaka” z identycznymi wynikami i ID różniącym się o 10; korelacje między miarami w oryginale ok. 0 przy silnych korelacjach w replikacji; 11,7% zaokrąglonych szacunków czasu vs 85% w replikacji → zgodne.
  - Data Colada 139: oceny 13 z 49 studentów w sekcji z własnymi terminami zmienione, 12 z 13 w kierunku hipotezy; przeliczenie odtwarza t(95) = 2,92 z wersji roboczej z 2001 r. → zgodne.
  - Retrakcja 2 IX 2026, prośba Wertenbrocha 23 VII 2026, słowa Vazire, że sama replikacja nie byłaby podstawą do retrakcji → zgodne (Crossref, RW).
  - Replikacja: Kyle Hyndman (UT Dallas) i Alberto Bisin (NYU), online 15 VII 2026, druk VIII 2026; abstrakt: zmiany terminów miały znikomy wpływ na trzy miary wyników → zgodne (Crossref). Według RW replikacja Study 2 też miała 60 uczestników.
  - Cytowania: ok. 1000 w Web of Science → zgodne (RW). „Google Scholar ok. 2100–2200” → **RW tego nie podaje**; niepotwierdzone.
  - Ariely: oświadczenie mówi, że dokumentacja i pamięć po ponad dwóch dekadach nie wystarczają, by odpowiedzieć na zarzuty; w wideo z 31 VIII przyznał, że danym nie można ufać (RW); nie przyznaje się do fałszerstwa → zgodne co do sensu.
  - Wertenbroch: uznał analizę za przekonującą i stwierdził, że większość lub całość danych jest fałszywa → zgodne (RW).
  - „Współautor nigdy nie widział danych” → zgodne: według DC 138 Wertenbroch, o ile wiadomo autorom, nigdy nie miał dostępu do żadnej wersji danych; pliki przyszły do Hyndmana w 2006 r. z adresu związanego z Arielym.
  - Retrakcja PNAS 2012 (z Gino) → zgodne (RW). Utrata tenure przez Gino w maju 2025 i proces „wciąż we wrześniu 2026” → niezweryfikowane w tej sesji (kontekst, nie fakt kluczowy).
- **Kontrowersja:** realna i dobrze udokumentowana (DC 138, 139, notka, replikacja, oświadczenia obu autorów). Opis wyszukiwacza jest uczciwy z jednym doprecyzowaniem: Newsweek **nie przekręca wyniku naukowego** (cytuje notkę i wspomina Data Colada), tylko przesuwa ciężar na Epsteina. To przykład sensacyjnej ramy i „clickbaitu przez skojarzenie”, a nie zniekształcenia badania.
- **Retrakcje / korekty / krytyka / replikacje:** retrakcja 2 IX 2026 (Crossref, pole updated-by). Negatywna replikacja Hyndmana i Bisina (15 VII 2026). Nowszych reakcji po 3 IX 2026 (np. ewentualnego dochodzenia Duke) nie mogłem wyszukać (brak WebSearch).
- **Poprawki:** usunąć albo oznaczyć jako niepewną liczbę cytowań w Google Scholar; Study 2 to studenci z ogłoszenia, nie słuchacze kursu; Newsweek nie wymienia Wertenbrocha; data Ynetnews niepewna (≥ 2 IX 2026); kontekst o Gino oznaczyć jako niezweryfikowany.
- **Dodatkowe znaleziska:** oświadczenie Arielyego jest z 7 VIII 2026, czyli przed publikacją Data Colada (31 VIII). Warto to pokazać na osi czasu: replikacja (15 VII) → prośba Wertenbrocha (23 VII) → oświadczenie Arielyego (7 VIII) → Data Colada (31 VIII i 2 IX) → retrakcja (2 IX) → media (2–4 IX).
- **Ocena niezależna:** 5/5. Paper znany, krótki i czytelny (PDF autorski otwarty); kompletny trójkąt z publicznymi danymi i przystępną forensyką statystyczną; temat (terminy, prokrastynacja) dotyczy każdego studenta; dwie wyraźnie różne ramy medialne (Newsweek vs Ynetnews/RW). Zdecydowanie polecam do piętnastki.
- **Do ręcznego sprawdzenia przez zespół:** Duke Chronicle (403); notka retrakcyjna na sagepub (403, treść znana z RW, Newsweeka i Ynetnews); dokładna data artykułu Ynetnews.
- **Opis po poprawkach:**
  - **Kategoria:** metanauka / oszustwo naukowe / retrakcja (trójkąt: paper + replikacja + analiza Data Colada + retrakcja + news).
  - **News:** „Epstein-Linked Professor Under Scrutiny as Research Data Raises 'Red Flags'”, Newsweek (Joshua Rhett Miller), 3 IX 2026 (akt. 4 IX), https://www.newsweek.com/epstein-linked-professor-under-scrutiny-as-research-data-raises-red-flags-12402686, paywall: nie. Nagłówek i kilka akapitów o znajomości Arielyego z Epsteinem; sam opis retrakcji poprawny (cytat z notki, wzmianka o Data Colada), ale bez niezależnych ekspertów. Kontrast: „Influential Dan Ariely study retracted after researchers flag possible data manipulation”, Ynetnews, wrzesień 2026 (≥ 2 IX), https://www.ynetnews.com/health_science/article/syznatc00fl, paywall: nie, ostrożna rama oddzielająca ustalenia czasopisma od zarzutów Data Colada. Prasa branżowa: Poets&Quants (Marc Ethier, 2 IX 2026), https://poetsandquants.com/2026/09/02/data-colada-accuses-dukes-dan-ariely-of-tampering-with-data-in-a-2nd-influential-study/.
  - **Paper:** „Procrastination, Deadlines, and Performance: Self-Control by Precommitment”, Dan Ariely i Klaus Wertenbroch, Psychological Science 13(3): 219–224, 2002, DOI 10.1111/1467-9280.00441, wersja autorska: https://web.mit.edu/ariely/www/MIT/Papers/deadlines.pdf, open access: wersja autorska tak. Study 1: 99 słuchaczy executive education na MIT (sekcje 48/51), samodzielnie wyznaczane terminy dawały gorsze oceny niż terminy równo rozłożone przez prowadzącego. Study 2: 60 studentów, 3 warunki po 20 osób, zadanie korektorskie; najlepiej wypadły terminy równo rozłożone, najgorzej jeden termin końcowy. **Wycofany 2 IX 2026** (notka DOI 10.1177/09567976261488042).
  - **Trzecie źródło:** Data Colada [138] https://datacolada.org/138 i [139] https://datacolada.org/139 (anomalie w Study 2 i ręcznie zmienione oceny w Study 1); Retraction Watch (Kate Travis, 3 IX 2026) https://retractionwatch.com/2026/09/03/procrastination-study-duke-dan-ariely-psychological-science-data-colada-tampering-retraction/ (oświadczenia autorów, rola redaktor Vazire); replikacja Hyndman i Bisin, Psychological Science, 15 VII 2026, DOI 10.1177/09567976261460772 (znikomy wpływ terminów); oświadczenie Arielyego https://danariely.com/dan-ariely-statement-on-2002-procrastination-study/.
  - **Dlaczego fajne:** każdy zna prokrastynację; paper był klasykiem sylabusów; badacz nieuczciwości z kolejną retrakcją; wszystkie dane i analizy są publiczne, więc da się na slajdzie pokazać, jak wykrywa się fałszerstwo (duplikaty, brak zaokrągleń, brak korelacji, nieprawdopodobny efekt).
  - **Kontrowersja / rozjazd:** rama Newsweeka (Epstein) vs rama danych (Ynetnews, RW); Ariely nie przyznaje się do fałszerstwa, Wertenbroch mówi, że dane są fałszywe; replikacja vs forensyka (Vazire: sama replikacja nie wystarcza do retrakcji); 24 lata i ok. 1000 cytowań (WoS) zanim ktoś sprawdził dane.
  - **Trudność techniczna:** niska–średnia: d Cohena, korelacje, rozkład zaokrągleń, duplikaty; wszystko da się pokazać na prostych wykresach.
  - **Pytanie do dyskusji:** Czy zasady terminów na waszych kursach powinny się zmienić, skoro badanie, które je uzasadniało, jest wycofane? Dlaczego sfałszowany wynik żył 24 lata?
  - **Weryfikacja:** ✅, pewność wysoka.

### 2. SCORE: „połowa nauk społecznych się nie replikuje” (Nature, kwiecień 2026): ⚠️ poprawione (pewność: średnia–wysoka)
- **Sprawdzone linki:**
  - Science Friday: działa; „Why so many studies can't be replicated”, 10 IV 2026; goście Tim Errington (COS) i Abel Brodeur (Ottawa, I4R); bez paywalla. Strona linkuje do projektu SCORE, do newsa Nature i do osobnego papera Brodeura w Nature.
  - Forbes: HTTP 403 (potwierdzam). Chronicle: HTTP 403 (potwierdzam).
  - NRA-ILA: działa; 6 IV 2026; podaje 49% ze 164 paperów i poprawnie wymienia dziedziny SCORE, a potem rozciąga wniosek na badania nad przemocą z użyciem broni (cytuje analizę RAND z 2020 r.), których SCORE nie badał → opis wyszukiwacza zgodny.
  - nature.com (paper): działa po dwóch przekierowaniach; abstrakt potwierdza liczby; **strona pokazuje opcje zakupu (paywall u wydawcy)**.
  - PMC (PMC13456834): działa; wersja autorska (NIH Public Access), wolny dostęp.
  - LSE Impact Blog (Ilka Gleibs, 18 V 2026): działa; wprost omawia papery SCORE w Nature.
  - Quicknews (przedruk komunikatu KI, 15 IV 2026): działa. news.ki.se: nieotwierany.
  - arXiv 2604.26268 (Buzbas, Devezer): działa; v1 29 IV 2026, v2 30 IX 2026; abstrakt odnosi się do Many Labs 4, nie do SCORE → zgodne.
- **News a paper:** Science Friday mówi o projekcie SCORE i o tym, że udało się zreplikować tylko połowę badanych paperów; linkuje do relacji Nature. To audycja z transkrypcją, a nie artykuł prasowy, ale wprost omawia ten projekt. Forbes i Chronicle: treść nieotwarta, ich nagłówki sugerują omówienie.
- **Fakty:**
  - Tytuł, Nature 652(8108), DOI 10.1038/s41586-025-10078-y → zgodne. Doprecyzowanie z Crossref: s. 143–150, online 1 IV 2026, druk 2 IV 2026, 666 autorów (pierwsi: Tyner, Abatayo, Daley, Field, Fox).
  - 274 twierdzenia ze 164 paperów, 54 czasopisma, lata 2009–2018; 151/274 (55,1%) twierdzeń i 49,3% paperów; rozrzut 42,5–63,1%; r z 0,25 do 0,10 (82,4% mniej wspólnej wariancji); mediana mocy 99,6% → zgodne (abstrakt na nature.com).
  - Open access → **poprawka:** u wydawcy paywall; wolna wersja autorska w PMC.
  - „62 czasopisma” (Science Friday, KI) vs 54 (abstrakt): potwierdzam, że 62 i ok. 3900 artykułów dotyczy całej kolekcji SCORE, a 54 samego badania replikacji.
  - Liczby z komunikatu KI (865 badaczy; odtwarzalność 74% przybliżona i 54% dokładna, 91% i 77% przy udostępnionych danych i kodzie; analiza odporności na 100 artykułach: ok. 1/3 bardzo bliska oryginałowi, ok. 3/4 ten sam ogólny wniosek) → zgodne z przedrukiem.
  - „13 metod daje 28,6–74,8%” → **niepotwierdzone** (nie było w abstrakcie; PMC nie zwrócił tej części).
  - Liczba dyscyplin: tekst przytoczony przez NRA wymienia 6 (biznes, ekonomia, edukacja, politologia, psychologia, socjologia); w abstrakcie nie sprawdzone.
  - Finansowanie DARPA → niepotwierdzone w tej sesji (prawdopodobne, ale nie sprawdziłem).
- **Kontrowersja:** realna, ale głównie interpretacyjna (co znaczy „zreplikować”, „szklanka do połowy pełna”). Gleibs (LSE) jest źródłem polemiki; NRA-ILA to realny przykład politycznego użycia. Buzbas i Devezer dają ogólną krytykę binarnych werdyktów, ale nie piszą o SCORE wprost; tak to trzeba przedstawić. Opis wyszukiwacza jest uczciwy.
- **Retrakcje / korekty / krytyka / replikacje:** Crossref: brak korekt i retrakcji. Wyszukiwania komentarzy krytycznych w Nature nie mogłem wykonać; news Nature linkuje do News & Views (nieotwarte).
- **Poprawki:** OA u wydawcy: nie (PMC: tak); dodać strony 143–150 i liczbę autorów; „28,6–74,8%” oznaczyć jako niepotwierdzone; doprecyzować, że Buzbas i Devezer nie odnoszą się do SCORE; Brodeur mówi o osobnym badaniu w Nature (I4R), nie o SCORE.
- **Dodatkowe znaleziska:** news w Nature: „Half of social-science studies fail replication test in years-long project”, Nicola Jones, 1 IV 2026, https://www.nature.com/articles/d41586-026-00955-5 (otwarte po przekierowaniach; paywall). Lead mówi o „siedmioletnim projekcie badającym 3900 paperów”, a „replikowało się tylko pół”, choć replikacje dotyczyły 164 paperów. To gotowy przykład skrótu medialnego do roli 1. Osobny paper Brodeura w Nature (link ze Science Friday): https://www.nature.com/articles/s41586-026-10251-x (nieotwierany).
- **Ocena niezależna:** 4/5. Paper wybitny, świeży i dotyczy kierunków publiczności. Minusy: para jest „o całym polu”, a nie o jednym wyniku; dostępne newsy to audycja radiowa i paywallowane Nature/Forbes. Polecam do piętnastki, jeśli zespół chce temat kryzysu replikacji (dobrze łączy się z parą 1 jako „systemowe tło”).
- **Do ręcznego sprawdzenia przez zespół:** Forbes (403), Chronicle (403): czy wprost nazywają paper; news Nature (paywall, dostęp przez UU).
- **Opis po poprawkach:**
  - **Kategoria:** metanauka / kryzys replikacji.
  - **News:** „Why so many studies can't be replicated”, Science Friday (audycja z transkrypcją; Tim Errington i Abel Brodeur), 10 IV 2026, https://www.sciencefriday.com/segments/social-science-replication-crisis-score-study/, paywall: nie. Spokojna rama: replikuje się ok. połowa, ważne jest udostępnianie danych. Uzupełniająco: Nature News (Nicola Jones, 1 IV 2026, paywall) https://www.nature.com/articles/d41586-026-00955-5 oraz Forbes (Michael T. Nietzel, 4 IV 2026, nieotwarty) https://www.forbes.com/sites/michaeltnietzel/2026/04/04/only-about-half-of-social-science-results-can-be-replicated-finds-new-study/.
  - **Paper:** „Investigating the replicability of the social and behavioural sciences”, Andrew H. Tyner i in. (666 autorów, konsorcjum SCORE/Center for Open Science), Nature 652(8108): 143–150, 2026, DOI 10.1038/s41586-025-10078-y, open access: u wydawcy nie, wersja autorska w PMC tak (https://pmc.ncbi.nlm.nih.gov/articles/PMC13456834/). Próba replikacji 274 twierdzeń ze 164 paperów (54 czasopisma, 2009–2018) przy bardzo wysokiej mocy (mediana 99,6%). Zreplikowało się 55,1% twierdzeń i 49,3% paperów, z rozrzutem 42,5–63,1% między dziedzinami; mediana efektu spadła z r = 0,25 do 0,10.
  - **Trzecie źródło:** Ilka Gleibs, LSE Impact Blog, 18 V 2026, https://blogs.lse.ac.uk/impactofsocialsciences/2026/05/18/is-it-really-bad-that-only-50-of-social-science-papers-are-reproducible/ (polemika z narracją porażki); NRA-ILA, 6 IV 2026, https://www.nraila.org/articles/20260406/social-science-replication-crisis-shows-danger-field-poses-to-public-policy (polityczne użycie); komunikat KI w przedruku https://www.quicknews.co.za/2026/04/15/half-of-social-science-research-results-cannot-be-replicated/ (liczby z całej kolekcji); kontekst: Buzbas i Devezer, arXiv 2604.26268 (krytyka binarnych werdyktów, bez odniesienia do SCORE).
  - **Dlaczego fajne:** największe systematyczne badanie replikowalności nauk społecznych; dotyczy kierunków studentów UCU.
  - **Kontrowersja / rozjazd:** „połowa się nie replikuje” vs niuanse definicji sukcesu; lead Nature (3900 paperów) vs 164 replikowane papery; polityczne użycie przez NRA; spór „kryzys” vs „szklanka do połowy pełna”.
  - **Trudność techniczna:** średnia: moc, wielkość efektu, definicje replikacji, spadek efektu.
  - **Pytanie do dyskusji:** Czy wynik „50%” to powód do nieufności wobec nauk społecznych, czy dowód, że nauka się koryguje? Komu wolno używać takich danych przeciw konkretnym badaniom?
  - **Weryfikacja:** ⚠️, pewność średnia–wysoka.

### 3. Smartfon przed 12. rokiem życia (Pediatrics, grudzień 2025): ⚠️ poprawione (pewność: średnia–wysoka)
- **Sprawdzone linki:**
  - Boston Globe: działa; nagłówek zgodny; bez autora; na końcu dopisek, że tekst ukazał się pierwotnie w NYT; narzędzie nie widziało paywalla (Boston Globe stosuje jednak licznik artykułów, więc „możliwy paywall”).
  - ABC7: działa; Mary Kekatos, 1 XII 2025; bez paywalla.
  - Mental Elf: działa; „Should we wait until age 13 before giving our kids a smartphone?”, Andre Tomlin, 9 VI 2026.
  - KTVZ (CNN Newsource): działa; Amanda Schupak, 25 IX 2026.
  - doi.org / AAP: nie otwierałem ponownie (u wyszukiwacza 403); metadane i abstrakt z Crossref.
- **News a paper:** przedruk NYT pisze, że badanie opublikowane w poniedziałek w Pediatrics wykazało wyższe ryzyko depresji, otyłości i niewystarczającego snu u dzieci ze smartfonem w wieku 12 lat; cytuje autora (tylko związek, nie przyczynowość) i Jacqueline Nesi (przyczynowość bardzo trudna albo niemożliwa do wykazania). ABC podaje te same liczby i zastrzeżenie autora, bez niezależnych ekspertów → zgodne z opisem.
- **Fakty:**
  - Tytuł, Pediatrics 157(1): e2025072941, DOI 10.1542/peds.2025-072941, online 1 XII 2025 → zgodne; druk 1 I 2026 (Crossref).
  - Autorzy → doprecyzowanie: Ran Barzilay, Samuel D. Pimentel, Kate T. Tran, Elina Visoki, David Pagliaccio, Randy P. Auerbach (Crossref).
  - Próba „ponad 10 500” → dokładnie 10 588 uczestników ABCD (abstrakt w Crossref).
  - OR 1,31 (depresja), 1,40 (otyłość), 1,62 (niewystarczający sen) → zgodne z abstraktem (ABC zaokrągla do 1,3/1,4/1,6). „+10% na każdy rok wcześniej” → tylko z ABC; abstrakt mówi ogólnie, że wcześniejszy wiek wiązał się z gorszymi wynikami.
  - Open access → niepewne (Crossref nie podaje licencji).
  - **Krytyka Mental Elf: poprawka przypisania.** Zarzuty „35,5% bez danych o social mediach”, „nie dało się sprawdzić zarejestrowanej hipotezy o social mediach” i „depresja na granicy istotności (OR 1,45; 95% CI 0,98–2,14)” dotyczą **kontynuacji Bren i in. (JAMA Pediatrics 2026)**, a nie papera z Pediatrics. Do papera Barzilaya odnoszą się: pojedynczy pomiar posiadania i użycia z samoopisu lub relacji rodzica (słabo zgodny z danymi logowanymi), ograniczenie części analiz do grup o wyższym statusie, szeroka miara psychopatologii zamiast depresji w analizie w wieku 13 lat oraz konflikty interesów (Barzilay: udziały w Taliaz Health, rada naukowa organizacji Children and Screens).
  - Bren i in. → doprecyzowanie tytułu: „Smartphone Acquisition and Use at Age 13 Years and Health Outcomes at Age 14 Years”; online 8 VI 2026 (Mental Elf), wydanie 1 VIII 2026 (Crossref); 1959 nastolatków; **samo nabycie smartfona ok. 13. roku życia nie wiązało się istotnie z depresją ani otyłością**, natomiast łączny czas używania już tak (abstrakt w Crossref). To ważne: kontynuacja tego samego zespołu częściowo osłabia przekaz „poczekaj do 13 lat”.
  - Nagata (JAMA Network Open, IX 2026): prawie 9000 nastolatków, 24% vs poniżej 16% z objawami zaburzeń odżywiania w wieku 14 lat (KTVZ/CNN) → zgodne co do kierunku; „+49%” nie pada w tekście KTVZ (24/16 daje ok. 1,5, więc wartość jest wiarygodna, ale niepotwierdzona).
- **Kontrowersja:** realna (obserwacyjny projekt, umiarkowane OR, spór Haidt vs Odgers/Orben w tle, krytyka Mental Elf). Opis rozjazdu newsów uczciwy: NYT oddaje ograniczenia (Nesi), ABC mniej. Nagłówki „higher risk” nie twierdzą wprost, że telefon *powoduje* szkodę, więc rozjazd jest umiarkowany, nie rażący.
- **Retrakcje / korekty / krytyka / replikacje:** Crossref: brak korekt i retrakcji dla obu paperów (Barzilay, Bren). Krytyka: Mental Elf. Nowej krytyki nie mogłem wyszukać.
- **Poprawki:** przypisać zarzuty Mental Elf właściwym paperom (patrz wyżej); N = 10 588; pełna lista autorów; druk 1 I 2026; Mental Elf: Andre Tomlin, 9 VI 2026; dodać wynik Bren (brak istotnego związku samego nabycia w wieku 13 lat z depresją i otyłością); paywall Boston Globe: możliwy (licznik).
- **Dodatkowe znaleziska:** Bren i in. (1959 osób) jako „druga połowa historii”: ten sam zespół rok później pokazuje, że liczy się raczej czas używania i telefon w sypialni niż sam wiek nabycia. Dobre do dyskusji o tym, jak media relacjonują pierwsze, a nie kolejne badanie.
- **Ocena niezależna:** 4/5. Temat bliski każdemu, renomowane czasopismo i medium (NYT przez przedruk), gotowa krytyka i kontynuacje. Minus: typowy paper korelacyjny bez efektownej historii. Polecam do piętnastki (najlepiej razem z parą 4 jako jedna prezentacja-debata).
- **Do ręcznego sprawdzenia przez zespół:** oryginał NYT (autor, data; domena blokowana); pełny tekst papera (AAP, 403) dla przedziałów ufności i informacji o pre-rejestracji; czy paper jest open access.
- **Opis po poprawkach:**
  - **Kategoria:** smartfony i nastolatki.
  - **News:** „A smartphone before age 12 could carry health risks, study says”, The New York Times (przedruk w The Boston Globe), 1 XII 2025, https://www.bostonglobe.com/2025/12/01/nation/smartphone-before-age-12-could-carry-health-risks-study-says, paywall: możliwy (licznik Boston Globe). Nagłówek ostrożny („could carry”); w tekście autor i zewnętrzna ekspertka (Jacqueline Nesi) podkreślają brak dowodu przyczynowości. Drugi: „Kids who have smartphones by age 12 have higher risk of depression, obesity: Study”, ABC News (Mary Kekatos, ABC7), 1 XII 2025, https://abc7.com/post/kids-have-smartphones-age-12-higher-risk-depression-obesity-study/18237775/, paywall: nie; mocniejszy nagłówek, bez niezależnych ekspertów.
  - **Paper:** „Smartphone Ownership, Age of Smartphone Acquisition, and Health Outcomes in Early Adolescence”, Ran Barzilay, Samuel D. Pimentel, Kate T. Tran, Elina Visoki, David Pagliaccio, Randy P. Auerbach, Pediatrics 157(1): e2025072941, online 1 XII 2025, DOI 10.1542/peds.2025-072941, open access: niepewne. Dane 10 588 dzieci z kohorty ABCD. Posiadanie smartfona w wieku 12 lat wiązało się z wyższymi szansami depresji (OR 1,31), otyłości (1,40) i niewystarczającego snu (1,62); wcześniejsze nabycie wiązało się z gorszymi wynikami. Badanie obserwacyjne.
  - **Trzecie źródło:** Mental Elf (Andre Tomlin, 9 VI 2026), https://www.nationalelfservice.net/treatment/digital-health/wait-13-giving-kids-smartphone/: krytyczna ocena tego papera i kontynuacji Bren i in. (JAMA Pediatrics 2026, DOI 10.1001/jamapediatrics.2026.2118; 1959 osób; samo nabycie w wieku 13 lat nieistotnie związane z depresją i otyłością, łączny czas użycia tak; 35,5% bez danych o social mediach). Kontynuacja: Nagata, JAMA Network Open, IX 2026, relacja CNN (Amanda Schupak) w przedruku KTVZ: https://ktvz.com/health/cnn-health/2026/09/25/12-year-olds-with-smartphones-are-more-likely-to-develop-eating-disorders-by-14.
  - **Dlaczego fajne:** pytanie „kiedy dać dziecku smartfon” zna każdy; NYT i ABC; ten sam zespół rok później pokazuje bardziej niejednoznaczny obraz.
  - **Kontrowersja / rozjazd:** obserwacyjny wynik z umiarkowanymi OR, a nagłówki o „ryzyku”; NYT ostrożny, ABC mniej; konflikty interesów autora (Children and Screens); kontynuacja Bren osłabia przekaz o wieku nabycia.
  - **Trudność techniczna:** średnia: ilorazy szans, confounding, braki danych, samoopis vs dane logowane, odwrotna przyczynowość.
  - **Pytanie do dyskusji:** Czy rodzice i szkoły powinni opóźniać smartfon do 13–14 lat na podstawie badań korelacyjnych? Jaki dowód byłby dla was przekonujący?
  - **Weryfikacja:** ⚠️, pewność średnia–wysoka.

### 4. Sapien Labs (2025) kontra Ferguson (2026) o wieku pierwszego smartfona: ⚠️ poprawione (pewność: średnia)
- **Sprawdzone linki:**
  - PsyPost: działa; Eric W. Dolan; narzędzie dwukrotnie podało datę publikacji 10 IX 2026 (ponad rok po paperze; możliwe, że PsyPost opisał badanie z opóźnieniem, data niepewna); podaje DOI papera; nie wspomina Fergusona ani krytyków.
  - News-Medical: działa; 21 VII 2025; to komunikat prasowy Taylor & Francis.
  - clinicalneuropsychiatry.org (Ferguson): działa; DOI 10.36131/cnfioritieditore20260303 rozwiązuje się przez doi.org na tę stronę (w Crossref API brak rekordu, HTTP 404).
  - Mike Males (Substack): działa; 1 XII 2025.
  - doi.org/10.1080/19452829.2025.2518313: nieotwierany; metadane z Crossref.
  - Raport Sapien Labs z 2023 r.: nie sprawdzałem ponownie (nie dotyczy papera).
- **News a paper:** PsyPost podaje tytuł, wszystkich trzech autorów, czasopismo i DOI → zgodne.
- **Fakty:**
  - Tytuł, autorzy (Thiagarajan, Newson, Swaminathan; Sapien Labs), DOI → zgodne. Doprecyzowanie z Crossref: Journal of Human Development and Capabilities 26(3): 493–504, online 20 VII 2025; finansowanie Sapien Labs; tylko 15 pozycji bibliografii (to raczej krótki artykuł programowy z danymi niż pełny paper empiryczny, niepewne). Open access: niepewne (Crossref nie podaje).
  - Ponad 100 000 osób w wieku 18–24 lat ze 163 krajów; MHQ ok. 30 przy wieku 13 lat i ok. 1 przy wieku 5 lat; myśli samobójcze u kobiet 48% vs 28% (u mężczyzn 31% vs 20%); social media „wyjaśniają” ok. 40% związku (do 70% w krajach anglojęzycznych) → zgodne (PsyPost).
  - Ograniczenia w PsyPost: dane obserwacyjne, retrospektywny samoopis, brak pomiaru całkowitego czasu ekranowego i treści → zgodne.
  - Ferguson: 80 878 młodych dorosłych (średnia wieku 23,3), dane Sapien Labs, regresja OLS; niekorzystne doświadczenia dziecięce przewidują zdrowie psychiczne, wiek dostępu do smartfona i tabletu nie; rady, by opóźniać smartfon, „wydają się nieuzasadnione” → zgodne. **Doprecyzowanie:** strona papera nie odnosi się wprost do Thiagarajan i in. (2025), więc „odpowiedź na paper Sapien Labs” to interpretacja wyszukiwacza, nie deklaracja Fergusona. To ten sam zbiór źródłowy (Global Mind Project), ale inny podzbiór i inny model.
  - Males: krytyka (retrospekcja 12–20 lat, porównanie skrajnych grup, „brak różnicy” dla 80–95% badanych, brak ACE) i cytowany nagłówek MSN → zgodne z tekstem Malesa; sam artykuł MSN niezweryfikowany.
  - Czy Thiagarajan i in. kontrolowali ACE → nadal niepewne.
- **Kontrowersja:** realna; źródła konkretne (Ferguson, Males). Opis uczciwy, łącznie z zastrzeżeniem, że Ferguson jest znanym krytykiem „paniki technologicznej”. Należy dodać, że autorzy papera Sapien Labs pracują w organizacji, która prowadzi Global Mind Project i finansowała badanie, a z wyników wyprowadzają rekomendacje polityczne (zakaz smartfonów przed 13. rokiem życia).
- **Retrakcje / korekty / krytyka / replikacje:** Crossref: brak korekt i retrakcji dla papera Sapien Labs; dla Fergusona brak rekordu w Crossref. Nowej krytyki nie mogłem wyszukać.
- **Poprawki:** Ferguson nie odpowiada wprost na paper Sapien Labs (to zestawienie wyszukiwacza); dane bibliograficzne JHDC 26(3): 493–504; data PsyPost niepewna (strona: 10 IX 2026); MSN niezweryfikowany; finansowanie Sapien Labs.
- **Ocena niezależna:** 3/5. Świetny materiał dydaktyczny o zmiennych kontrolnych, ale media słabe (PsyPost, komunikat prasowy), czasopisma średniej rangi, a samo zestawienie „ten sam zbiór, odwrotny wniosek” jest konstrukcją wyszukiwacza. Samodzielnie nie polecam do piętnastki; polecam jako uzupełnienie pary 3.
- **Do ręcznego sprawdzenia przez zespół:** pełny tekst papera Sapien Labs (Taylor & Francis): metoda, kontrola ACE, open access; data PsyPost; nagłówek MSN.
- **Opis po poprawkach:**
  - **Kategoria:** smartfony i nastolatki / metanauka (czynniki zakłócające).
  - **News:** „Getting a smartphone before age 13 linked to worse mental health in young adulthood”, PsyPost (Eric W. Dolan), data na stronie 10 IX 2026 (niepewna), https://www.psypost.org/getting-a-smartphone-before-age-13-linked-to-worse-mental-health-in-young-adulthood/, paywall: nie. Rzeczowe streszczenie z liczbami i ograniczeniami, bez głosów krytycznych. Uzupełniająco: komunikat Taylor & Francis w News-Medical, 21 VII 2025, https://www.news-medical.net/news/20250721/Early-smartphone-use-linked-to-poorer-mental-health-in-young-adults.aspx.
  - **Paper:** „Protecting the Developing Mind in a Digital Age: A Global Policy Imperative”, Tara C. Thiagarajan, Jennifer Jane Newson, Shailender Swaminathan (Sapien Labs), Journal of Human Development and Capabilities 26(3): 493–504, 2025, DOI 10.1080/19452829.2025.2518313, open access: niepewne. Retrospektywne dane Global Mind Project od ponad 100 000 osób w wieku 18–24 lat ze 163 krajów: im wcześniej pierwszy smartfon, tym niższy wskaźnik MHQ i więcej myśli samobójczych (kobiety: 48% przy wieku 5–6 lat vs 28% przy 13); ok. 40% związku przypisują social mediom. Autorzy postulują ograniczenia dostępu do smartfonów przed 13. rokiem życia.
  - **Trzecie źródło:** Christopher J. Ferguson, „Adverse Childhood Events, Not Age of Acquiring Smartphones or Tablets, Predict Mental Health in Young Adults”, Clinical Neuropsychiatry 2026 nr 3, DOI 10.36131/cnfioritieditore20260303, https://www.clinicalneuropsychiatry.org/download/adverse-childhood-events-not-age-of-acquiring-smartphones-or-tablets-predict-mental-health-in-young-adults/ (80 878 osób z danych Sapien Labs; po uwzględnieniu ACE wiek nabycia nie przewiduje zdrowia psychicznego). Mike Males, Substack, 1 XII 2025, https://mikemales.substack.com/p/the-massive-global-mind-project-study (krytyka metody i nagłówków).
  - **Dlaczego fajne:** ten sam zbiór źródłowy, przeciwne wnioski zależnie od zmiennych w modelu.
  - **Kontrowersja / rozjazd:** z danych korelacyjnych i retrospektywnych do rekomendacji zakazu; media powtarzają komunikat; obie strony mają swoje „biasy” (organizacja prowadząca projekt vs znany krytyk paniki technologicznej).
  - **Trudność techniczna:** średnia: confounding, mediacja, retrospektywny samoopis.
  - **Pytanie do dyskusji:** Kto ma rację, jeśli dwa zespoły analizujące te same dane dochodzą do przeciwnych wniosków?
  - **Weryfikacja:** ⚠️, pewność średnia.

### 5. Wycofany paper Nature o kosztach zmian klimatu (Kotz, Levermann, Wenz): ⚠️ poprawione (pewność: średnia)
- **Sprawdzone linki:**
  - Notka retrakcyjna w PMC (PMC12711553): działa.
  - treefrogcreative.ca: działa; to przedruk tekstu Retraction Watch z 5 XII 2025 na obcej stronie (nieoficjalna kopia, status licencyjny niepewny; nie polecam jej zespołowi jako źródła). Oryginału RW nie mogłem znaleźć bez wyszukiwania.
  - Pielke Jr., Substack: działa; zwrócił linki do AP i NYT.
  - **AP** (https://apnews.com/article/climate-change-economic-impact-global-emissions-nature-3b99e4c317214554d28decf253bad3bb): „Claude Code is unable to fetch from apnews.com” (blokada wydawcy).
  - **NYT** (https://www.nytimes.com/2025/12/03/business/economy/study-climate-damage-retracted.html): „unable to fetch” (blokada wydawcy). Przedruków nie mogłem wyszukać.
  - EDHEC (Nicolas Schneider, 17 III 2026): działa.
  - spectator.org i AEI: nie sprawdzałem ponownie.
- **News a paper:** newsy główne (AP, NYT) nieotwarte. Pielke wprost omawia paper i retrakcję oraz krytykuje ramę AP (zmiana z 19% na 17% przedstawiona jako drobna, „slightly overstate”) i chwali NYT za głosy krytyczne. Przedruk RW nazywa paper i datę publikacji, wspomina dwa komentarze z sierpnia 2025 oraz relacje Bloomberga, Euronews i WSJ (bez linków).
- **Fakty:**
  - Tytuł, autorzy, 17 IV 2024, DOI 10.1038/s41586-024-07219-0 → zgodne; doprecyzowanie z Crossref: Nature 628(8008): 551–557.
  - Open access → **poprawka:** tak, CC BY 4.0 (Crossref).
  - Retrakcja 3 XII 2025, DOI notki 10.1038/s41586-025-09726-0 → zgodne.
  - **Brakujące u wyszukiwacza:** korekta z 24 VI 2024 (DOI 10.1038/s41586-024-07732-2) i nota redakcyjna z 6 XI 2024 ostrzegająca, że wiarygodność danych i metody jest kwestionowana (Crossref). Retrakcja była więc poprzedzona rocznym sygnałem ostrzegawczym.
  - Uzbekistan (dane 1995–1999), autokorelacja przestrzenna, przedział 11–29% → 6–31%, prawdopodobieństwo rozejścia scenariuszy 99% → 90%, Zenodo 10.5281/zenodo.15984134, zgoda wszystkich autorów, osoby zgłaszające (Bearpark, Hogan, Hsiang, Schötz) → zgodne z notką.
  - 19% → 17% → zgodne (EDHEC; Pielke o ramie AP).
  - „ok. 38 bln USD rocznie”, „drugi najczęściej opisywany paper klimatyczny 2024”, „scenariusze NGFS” → niezweryfikowane w tej sesji.
  - Komentarze z sierpnia 2025 → przedruk RW tylko o nich wspomina; autorów i tytułów nie potwierdziłem (Crossref nie pokazuje ich jako relacji).
  - Gregory Hopper (Bank Policy Institute) jako pierwszy zgłaszający → tak twierdzi Pielke; notka wymienia innych. Obie informacje mogą być prawdziwe, ale to opinia Pielkego.
- **Kontrowersja:** realna. Rama AP vs NYT jest znana tylko z relacji Pielkego (źródło stronnicze), więc **nie można jej jeszcze przedstawić jako faktu** bez przeczytania obu tekstów. EDHEC to realny kontrargument („wniosek się nie zmienia”).
- **Retrakcje / korekty / krytyka / replikacje:** korekta VI 2024, nota redakcyjna XI 2024, retrakcja XII 2025 (Crossref). Poprawiona wersja na Zenodo czeka na ponowną recenzję (stan z notki). Nie mogłem sprawdzić, czy została opublikowana w 2026 r.
- **Poprawki:** OA: tak (CC BY 4.0); dodać korektę z VI 2024 i notę z XI 2024; tom i strony; liczby 38 bln, ranking i NGFS oznaczyć jako niezweryfikowane; ramy AP i NYT tylko według Pielkego; zastąpić kopię treefrogcreative oryginałem RW (do odnalezienia przez zespół).
- **Ocena niezależna:** 4/5. Paper najwyższej rangi, głośny, open access, z ciekawą historią (jeden kraj, ostrzeżenie redakcji, retrakcja) i z wyraźnie politycznym sporem o interpretację. Minus: oba newsy główne są zablokowane i trzeba je przeczytać ręcznie; ekonometria jest trudna. Polecam do piętnastki warunkowo, jeśli zespół potwierdzi teksty AP i NYT.
- **Do ręcznego sprawdzenia przez zespół:** AP i NYT (linki wyżej): nagłówki, daty, czy nazywają paper, jak opisują zmianę 19% → 17%; oryginał Retraction Watch z 5 XII 2025; komentarze z sierpnia 2025 (autorzy, tytuły); czy poprawiona wersja została opublikowana.
- **Opis po poprawkach:**
  - **Kategoria:** retrakcja / metanauka / wildcard (ekonomia klimatu).
  - **News:** AP, grudzień 2025, https://apnews.com/article/climate-change-economic-impact-global-emissions-nature-3b99e4c317214554d28decf253bad3bb, i The New York Times, 3 XII 2025, https://www.nytimes.com/2025/12/03/business/economy/study-climate-damage-retracted.html (oba nieotwarte; paywall NYT: tak; AP: nie). Według Pielkego AP przedstawia retrakcję jako drobną korektę, a NYT daje głos krytykom. Dostępne: Roger Pielke Jr., „A Huge Retraction, the Usual Playbook, and Reason for Optimism”, Substack, 3 XII 2025, https://rogerpielkejr.substack.com/p/a-huge-retraction-the-usual-playbook (blog, autor stronniczy w sporze klimatycznym).
  - **Paper:** „The economic commitment of climate change”, Maximilian Kotz, Anders Levermann, Leonie Wenz (PIK), Nature 628(8008): 551–557, 2024, DOI 10.1038/s41586-024-07219-0, open access: tak (CC BY 4.0). Panel danych subnarodowych o klimacie i wzroście gospodarczym; wniosek: do połowy wieku zmiany klimatu obniżą światowe dochody o ok. 19% niezależnie od przyszłych emisji. Korekta (VI 2024), nota redakcyjna (XI 2024), **retrakcja 3 XII 2025** (DOI 10.1038/s41586-025-09726-0): wyniki wrażliwe na błędne dane Uzbekistanu z lat 1995–1999 i na autokorelację przestrzenną; po poprawkach przedział 6–31% zamiast 11–29%.
  - **Trzecie źródło:** notka retrakcyjna w PMC, https://pmc.ncbi.nlm.nih.gov/articles/PMC12711553/ (co i kto wykrył); Nicolas Schneider, EDHEC, 17 III 2026, https://climateinstitute.edhec.edu/news/climate-economics-isnt-broken-and-risks-remain-significant (kontrargument: 17% vs 19% to ten sam rząd wielkości).
  - **Dlaczego fajne:** liczba „−19% dochodów” krążyła po mediach i instytucjach finansowych, a okazała się wrażliwa na dane z jednego kraju; spór o to, czy to „drobiazg”, czy „porażka recenzji”.
  - **Kontrowersja / rozjazd:** ramy medialne (według Pielkego: AP bagatelizuje, NYT krytycznie; WSJ i Spectator politycznie; EDHEC „nic się nie zmieniło”); czy retrakcja to dowód, że nauka działa.
  - **Trudność techniczna:** średnia–wysoka (ekonometria panelowa, autokorelacja przestrzenna), da się uprościć do „usuń jeden kraj i wynik się zmienia”.
  - **Pytanie do dyskusji:** Czy jedna wycofana praca powinna zmieniać politykę klimatyczną? Kto zyskuje na narracji „nauka się myli”, a kto na „nic się nie stało”?
  - **Weryfikacja:** ⚠️, pewność średnia (news główny do ręcznego sprawdzenia).

### 6. „Arsenic life”: retrakcja po 15 latach (Science, lipiec 2025): ✅ potwierdzone (pewność: wysoka)
- **Sprawdzone linki:**
  - Retraction Watch: działa; „After 15 years of controversy, Science retracts 'arsenic life' paper”, **Ellie Kincaid**, 24 VII 2025; bez paywalla.
  - Times Higher Education (David A. Sanders, 14 VIII 2025): działa; paywall/rejestracja.
  - Jerry Coyne (25 VII 2025): działa; zwrócił linki do notki w Science, NYT (11 II 2025) i AP.
  - science.org, nytimes.com, apnews.com: nieotwierane (domeny blokowane); paper, notka, „expression of concern” i replikacje potwierdzone przez Crossref.
- **News a paper:** RW nazywa paper z 2010 r. i Felisę Wolfe-Simon, przytacza uzasadnienie Holdena Thorpa (rozszerzone kryteria: retrakcja, gdy eksperymenty nie wspierają kluczowych wniosków, bez zarzutu oszustwa) → zgodne.
- **Fakty:**
  - Tytuł, DOI 10.1126/science.1197258 → zgodne; doprecyzowanie z Crossref: Science 332(6034): 1163–1166, online 2 XII 2010, druk 3 VI 2011, 12 autorów (Wolfe-Simon, Blum, Kulp, Gordon, Hoeft, Pett-Ridge, Stolz, Webb, Weber, Davies, Anbar, Oremland).
  - Retrakcja 24 VII 2025, DOI 10.1126/science.adu5488, autor notki H. Holden Thorp, Science 389(6758) → zgodne (Crossref).
  - **Brakujące u wyszukiwacza:** „Expression of Concern” z 3 VI 2011 (DOI 10.1126/science.1208877).
  - 326 cytowań, 8 komentarzy technicznych, kwasy nukleinowe niedostatecznie oczyszczone (zanieczyszczenie fosforanem) → zgodne (RW).
  - Dwie nieudane replikacje z 2012 r. → zgodne: Reaves, Sinha, Rabinowitz, Kruglyak, **Redfield**, „Absence of Detectable Arsenate in DNA from Arsenate-Grown GFAJ-1 Cells”, Science 337: 470–473; Erb, Kiefer, Hattendorf, Günther, Vorholt, „GFAJ-1 Is an Arsenate-Resistant, Phosphate-Dependent Organism”, Science 337: 467–470; obie 27 VII 2012 (Crossref). Rosie Redfield potwierdzona jako współautorka replikacji.
  - Konferencja NASA → zgodne (RW cytuje zapowiedź „astrobiology finding that will impact the search for evidence of extraterrestrial life”; Coyne: Wolfe-Simon była jedyną autorką na konferencji).
  - Autorzy: większość współautorów podpisała list sprzeciwu i „stoi za danymi” → zgodne. Anbar według RW krytykuje głównie to, że o zanieczyszczeniu Science pisze tylko na blogu, a nie w notce.
  - „Science przekroczył wytyczne COPE” → niepotwierdzone w otwartych źródłach.
  - NYT z 11 II 2025: według Coyne'a przedstawia Wolfe-Simon jako ofiarę; treść niezweryfikowana (blokada).
- **Kontrowersja:** realna i dobrze udokumentowana (RW, THE, replikacje, list autorów). Opis uczciwy.
- **Retrakcje / korekty / krytyka / replikacje:** EoC 2011, replikacje 2012, retrakcja 2025 (Crossref). Krytyka procesu: Sanders (THE). Nowych materiałów z 2026 r. nie mogłem wyszukać.
- **Poprawki:** autorka RW: Ellie Kincaid; dodać EoC z 2011 r.; dane bibliograficzne; COPE oznaczyć jako niepotwierdzone; „z pamięci” w opisie wyszukiwacza potwierdzone (NASA, Redfield).
- **Dodatkowe znaleziska:** NYT z lutego 2025 (według Coyne'a sympatyzujący z Wolfe-Simon) i AP to potencjalnie świetny materiał do roli 1 (dwie ramy: „ofiara systemu” vs „hype NASA”), ale wymagają ręcznego przeczytania.
- **Ocena niezależna:** 4/5. Fascynująca, kompletna historia: hype instytucji, krytyka blogerów, replikacje, nowa polityka retrakcji „za błąd”. Minus: paper z 2010 r. (retrakcja z 2025 r. odnawia temat), news główny to serwis branżowy. Polecam do piętnastki.
- **Do ręcznego sprawdzenia przez zespół:** NYT (11 II 2025) i AP (linki od Coyne'a): tytuły, daty, rama; notka retrakcyjna i wpis redakcyjny na science.org (403).
- **Opis po poprawkach:**
  - **Kategoria:** retrakcja / metanauka / wildcard (astrobiologia).
  - **News:** „After 15 years of controversy, Science retracts 'arsenic life' paper”, Retraction Watch (Ellie Kincaid), 24 VII 2025, https://retractionwatch.com/2025/07/24/science-retraction-arsenic-life-nasa-astrobiology/, paywall: nie. Rzeczowy opis retrakcji, uzasadnienia redaktora, głosu krytyka (Sanders) i sprzeciwu autorów. Do ręcznego sprawdzenia: NYT, 11 II 2025, https://www.nytimes.com/2025/02/11/science/arseniclife-felisa-wolfe-simon-retraction.html, i AP, https://apnews.com/article/arsenic-alien-life-mono-lake-nasa-bacteria-eb6b70b302457e4066006a17257d536b.
  - **Paper:** „A Bacterium That Can Grow by Using Arsenic Instead of Phosphorus”, Felisa Wolfe-Simon i 11 współautorów (m.in. Paul Davies, Ariel Anbar, Ronald Oremland), Science 332(6034): 1163–1166, online XII 2010, DOI 10.1126/science.1197258, open access: niepewne. Twierdził, że bakteria GFAJ-1 z jeziora Mono rośnie, wbudowując arsen zamiast fosforu, także w DNA. Expression of Concern 2011, dwie nieudane replikacje 2012, retrakcja 24 VII 2025 (DOI 10.1126/science.adu5488) z powodu niedostatecznego oczyszczenia próbek, bez zarzutu oszustwa.
  - **Trzecie źródło:** David A. Sanders, „The 'arsenic life' paper's retraction is good – but the process was poisonous”, Times Higher Education, 14 VIII 2025, https://www.timeshighereducation.com/node/738359 (paywall/rejestracja; krytyka recenzentów, redakcji, autorów i mediów). Replikacje: Reaves i in. (z Rosie Redfield) i Erb i in., Science 337, 2012. Blog: Jerry Coyne, https://whyevolutionistrue.com/2025/07/25/science-finally-retracts-the-2010-arsenic-life-paper-by-felisa-wolfe-simon-et-al/.
  - **Dlaczego fajne:** „życie, jakiego nie znamy” i konferencja NASA; krytyka z blogów naukowych; replikacje; pierwsza tak głośna retrakcja „za błędne wnioski”, a nie za oszustwo.
  - **Kontrowersja / rozjazd:** autorzy nadal bronią danych; krytycy mówią, że retrakcja przyszła 13 lat po replikacjach; czy czasopismo powinno wycofywać prace „tylko” błędne; odpowiedzialność mediów za hype.
  - **Trudność techniczna:** średnia: biochemia DNA i zanieczyszczenie próbek da się prosto wytłumaczyć.
  - **Pytanie do dyskusji:** Czy czasopisma powinny wycofywać prace błędne, ale nie sfałszowane? Kto odpowiada za hype: naukowcy, NASA czy media?
  - **Weryfikacja:** ✅, pewność wysoka.

(kolejne pary w toku)

## Lista do ręcznego sprawdzenia

(w toku)
