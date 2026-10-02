# Weryfikacja: 2b. AI a społeczeństwo: praca, perswazja, polityka, nauka, etyka

Weryfikator, data: 2 października 2026. Plik źródłowy: candidates/2b-ai-spoleczenstwo.md

## Podsumowanie
Sprawdzono 9 par: **✅ 3** (1, 6, 7), **⚠️ 6** (2, 3, 4, 5, 8, 9), **❌ 0**. Wszystkie linki z pliku otwierałem sam albo potwierdziłem, że są zablokowane (HPCwire, scimex: 403 także u mnie; The Verge, Washington Post i pnas.org nie były otwierane ze względu na znaną blokadę; PNAS sprawdzony przez PMC i Europe PMC). WebSearch działał przez całą sesję, więc pary 6–9 (weryfikowane przez wyszukiwacza bez wyszukiwarki) sprawdziłem od nowa i w trzech z nich znalazłem istotne nowe fakty.

Najważniejsze problemy i znaleziska:
- **Para 8:** korekta autorska w Nature Human Behaviour z **3 września 2026**: przewaga GPT-4 z personalizacją nad zwykłym GPT-4 jest nieistotna (P = 0,07). Wyszukiwacz tego nie znał. Wzmacnia to parę (gotowy spór), ale zmienia opis wyniku.
- **Para 6:** formalna wymiana w PNAS (luty 2026), w której list krytyczny napisali psychologowie z **Uniwersytetu w Utrechcie**, plus odrzucona przez PNAS krytyka Rothschilda i in. (Microsoft Research, Prolific, Duke). Paper jest open access (wyszukiwacz: „niepewne”).
- **Para 3:** liczby 13% → 16% → 19% to nie jedna seria: 13% i 16% to estymacje z regresji z kontrolą firmy, a 19% to prostsza miara opisowa (na tej mierze 15% → 19%).
- **Para 2:** znak „-18%” w kontynuacji METR z 2026 rozstrzygnięty (krótszy czas, nieistotne statystycznie); TechCrunch błędnie podaje, że 56% uczestników znało Cursora (w paperze: 44%).
- **Para 5:** Android Headlines myli wodę pośrednią z wodą chłodzenia; lepszy news to MIT Technology Review (Crownhart, 21 i 28.08.2025).
- **Para 9:** zamiast niedostępnego HPCwire i promocyjnego 36Kr: NPR (17.02.2026) z niezależnym krytykiem.
- **Modele Anthropic:** żaden paper w tej grupie nie jest autorstwa Anthropic (brak oznaczenia ⚑), ale w parach 2, 4 i 6 testowano lub używano modeli Claude, a para 3 korzysta z danych Anthropic Economic Index; warto to powiedzieć na prezentacji, bo raport przygotowuje Claude.

Polecane do finałowej piętnastki: **1** (chatboty a wyborcy, 5/5), **6** (bot łamiący ankiety, 5/5, haczyk utrechcki), **2** (METR, 5/5), **3** (Canaries, 4/5), **4** (Zurych/Reddit, 4/5, para etyczna), **5** (woda i energia, 4/5, z MIT TR). Warunkowo: **8** (64% debat, 4/5, samodzielnie albo jako uzupełnienie pary 1), **9** (AI zawęża naukę, 4/5), **7** (Toner-Rodgers, 4/5, jeśli nie trafi do grupy 5).

## Pary

### 1. Chatboty AI przesuwają preferencje wyborców (Nature + Science, grudzień 2025): ✅ potwierdzone (pewność: wysoka)
- **Sprawdzone linki:**
  - MIT Technology Review (https://www.technologyreview.com/2025/12/04/1128824/ai-chatbots-can-sway-voters-better-than-political-advertisements/): działa, WebFetch, brak oznak paywalla; tytuł, autorka (Michelle Kim), data 4.12.2025 zgodne.
  - Nature, paper (https://www.nature.com/articles/s41586-025-09771-9): działa po 2 przekierowaniach; tytuł, autorzy, tom 648, s. 394–401, data 4.12.2025, DOI zgodne; paywall (zakup 39,95 USD), brak korekt na stronie.
  - arXiv 2507.13919 (abs i PDF v1): działa; PDF przeczytany (s. 1–9).
  - News & Views, PDF w pure.uva.nl: działa; PDF przeczytany w całości (WebFetch zapisał plik, odczyt przez Read).
  - SMC Spain: działa; zgodne z opisem.
  - Nature news Kozlova (d41586-025-03975-9): działa po przekierowaniach; tytuł „AI chatbots can sway voters with remarkable ease — is it time to worry?”, 4.12.2025, paywall; omawia oba papery.
  - Strona UvA (dont-ask-ai-for-election-advice): działa; tytuł „1 in 10 Dutch citizens are likely to ask AI for election advice. This is why they shouldn't”, 29.10.2025.
  - Dodatkowo otwarte samodzielnie: komunikat Cornell Chronicle (https://www.news.cornell.edu/stories/2025/12/ai-chatbots-can-effectively-sway-voters-either-direction), Science News (https://www.sciencenews.org/?p=3163269), PsyPost, Science in Poland (PAP).
- **News a paper:** MIT TR wprost opisuje „badanie w Nature” (Pennycook z Cornell, Costello z American University) i „badanie w Science” (Hackenburg, UK AI Security Institute) i podaje ich wyniki. Jednoznaczne.
- **Fakty:**
  - Autorzy, czasopismo, tom, strony, DOI, data papera w Nature → zgodne (strona Nature).
  - Open access Nature: nie → zgodne.
  - „Ponad 2300 osób w USA” → zgodne (N&V, Cornell). Uzupełnienie: Kanada 1530, Polska 2118 uczestników (Cornell Chronicle, Science News); liczebności dla Massachusetts nie znalazłem (niepewne).
  - Trump → Harris 3,9 pkt → zgodne (MIT TR, Cornell, PAP).
  - Harris → Trump 2,3 pkt → **niejednoznaczne**: tak podaje MIT TR (i PAP/Science in Poland), ale komunikat prasowy Cornell (instytucja autorów) podaje 1,51 pkt. Paper (paywall) nie był dostępny do rozstrzygnięcia. Do sprawdzenia w Fig. 1 papera.
  - Ok. 10 pkt w Kanadzie i Polsce → zgodne (MIT TR, Cornell, Science News). PAP: w Polsce efekt ok. 3 razy większy niż w USA; po zablokowaniu faktów efekt spadał o 78%.
  - Massachusetts: N&V pisze o efektach „dwucyfrowych” na skali 0–100; PsyPost: wśród sceptyków prawie 15 pkt.
  - Ok. 1/3 efektu po miesiącu → zgodne (N&V).
  - Większa nieprawdziwość twierdzeń modeli agitujących za prawicą we wszystkich 3 krajach → zgodne (abstrakt).
  - Science: 76 977 uczestników, 19 modeli, 707 kwestii, 466 769 twierdzeń, +51% (post-training), +27% (prompting) → zgodne (arXiv v1, abstrakt).
  - Personalizacja +0,43 pp (95% CI 0,22–0,64) → zgodne (arXiv v1, s. 5).
  - Rozmowa vs statyczny tekst +41% (GPT-4o) i +52% (GPT-4.5) → zgodne (arXiv v1, s. 2).
  - Trwałość 36–42% po miesiącu → zgodne (arXiv v1, s. 2).
  - GPT-4.5: ponad 30% twierdzeń nieprawdziwych (badanie 2) → zgodne (arXiv v1, s. 8).
  - „Wszystkie dźwignie”: 16 i 26 pkt (N&V) → zgodne; arXiv v1 podaje 15,9 i 26,5 pp, MIT TR podaje 26,1 (prawdopodobnie wersja z Science; różnica wersji, drobna). W tej konfiguracji 29,7% twierdzeń było nieprawdziwych (arXiv v1).
  - Science 390(6777), DOI 10.1126/science.aea3884, publikacja 4.12.2025 → zgodne (repozytorium LSE w wynikach wyszukiwania, SMC Spain).
  - Reklama polityczna < 1 pkt proc. → zgodne (N&V, cytując Kalla i Broockman 2017). MIT TR: efekt „ok. 4 razy większy” niż reklamy z 2016 i 2020.
  - Cytaty Guessa (Princeton) i Coppocka (Northwestern) w MIT TR → zgodne.
- **Kontrowersja:** ma realne źródła: N&V w samym Nature (kontrolowane eksperymenty online vs dobrowolna ekspozycja w realu), SMC Spain (Gayo Avello: samoselekcja, sztuczne warunki, brak pomiaru głosowania; Quattrociocchi: efekty „nie należy traktować jako górnej granicy”). Opis wyszukiwacza uczciwy. Nagłówek MIT TR jest zgodny z wynikiem; nie przesadza. Uwaga dla zespołu: porównanie z reklamami jest pośrednie (efekty reklam z wcześniejszych badań, np. Coppock, Hill i Vavreck 2020), co wyszukiwacz poprawnie zaznaczył.
- **Retrakcje / korekty / krytyka / replikacje:** nie znaleziono korekt, „Matters Arising” ani retrakcji. Zapytania: „"Persuading voters using human" Nature correction OR erratum OR "matters arising"”, „critique response Lin et al. Nature 2025 AI chatbot voter persuasion … 2026”. Strona Nature nie pokazuje noty redakcyjnej.
- **Poprawki:** brak istotnych. Uzupełnienia: liczebności prób (Kanada 1530, Polska 2118); rozbieżność 2,3 vs 1,51 pkt dla zwolenników Harris między MIT TR a komunikatem Cornell; 26,1 (MIT TR) vs 26,5 (arXiv v1) vs 26 (N&V).
- **Dodatkowe znaleziska:**
  - Science News, Sujata Gupta, 4.12.2025, „Chatbots spewing facts, and falsehoods, can sway voters” (https://www.sciencenews.org/?p=3163269): otwarty, niezależne komentarze (Jillian Fisher, University of Washington) i odesłanie do komentarza Lisy Argyle (Purdue) w Science. Uwaga: streszczenie narzędzia odwróciło liczby dla USA, więc liczby z tego artykułu sprawdzić ręcznie.
  - Perspective w Science: Lisa Argyle, „Political persuasion by artificial intelligence”, Science 390(6777), 2025 (tylko z wyników wyszukiwania, nieotwierany).
  - Science in Poland (PAP), 16.12.2025 (https://scienceinpoland.pl/en/news/news%2C110808%2Cai-chatbots-can-sway-voters-more-traditional-political-ads.html): polski wątek (Trzaskowski vs Nawrocki, współautorka dr Gabriela Czarnek z UJ).
  - Rozbieżność 2,3 vs 1,51 pkt w różnych mediach to gotowy, mały przykład dla roli 1 (analiza mediów): różne media cytują różne liczby z tego samego papera.
- **Ocena niezależna:** 5/5. Dwa prerejestrowane badania w Nature i Science, otwarty i rzetelny news, krytyka w tym samym numerze Nature i od ekspertów SMC, temat dotyczący każdego (wybory, chatboty), polski i holenderski haczyk. Polecam do piętnastki (jeden z najmocniejszych kandydatów).
- **Do ręcznego sprawdzenia przez zespół:** liczba dla zwolenników Harris (2,3 czy 1,51 pkt) w Fig. 1 papera w Nature (paywall; dostęp przez bibliotekę UU); liczebność próby w Massachusetts.
- **Opis po poprawkach:**
  - **Kategoria:** perswazja i polityka
  - **News:** „AI chatbots can sway voters better than political advertisements”, Michelle Kim, MIT Technology Review, 4 grudnia 2025, https://www.technologyreview.com/2025/12/04/1128824/ai-chatbots-can-sway-voters-better-than-political-advertisements/ , paywall: nie (narzędzie otworzyło pełny tekst; MIT TR może stosować limit darmowych artykułów). Artykuł omawia jednocześnie papery w Nature i Science, podaje liczby (Trump → Harris 3,9 pkt, Harris → Trump 2,3 pkt wg MIT TR, ok. 10 pkt w Kanadzie i Polsce, prawie 77 000 uczestników w UK) i wprost pisze, że najbardziej przekonujące modele były najmniej prawdomówne. Cytuje sceptyków: Andy Guess (Princeton) i Alex Coppock (Northwestern).
  - **Paper:** „Persuading voters using human–artificial intelligence dialogues”, Hause Lin, Gabriela Czarnek, Benjamin Lewis, Joshua P. White, Adam J. Berinsky, Thomas Costello, Gordon Pennycook, David G. Rand, *Nature* 648, 394–401 (2025), 4.12.2025, DOI 10.1038/s41586-025-09771-9, https://www.nature.com/articles/s41586-025-09771-9 , open access: nie. Prerejestrowane eksperymenty: rozmowy z modelem agitującym za jednym z dwóch kandydatów (USA 2024, ponad 2300 osób; Kanada 2025, 1530; Polska 2025, 2118) plus referendum w Massachusetts. Efekty większe niż typowe dla reklam wideo, ok. 1/3 utrzymuje się po miesiącu; modele przekonują faktami, a modele agitujące za prawicą podawały więcej nieprawdy. Bliźniaczy paper: Hackenburg et al., „The levers of political persuasion with conversational artificial intelligence”, *Science* 390(6777), 2025, DOI 10.1126/science.aea3884, preprint open access https://arxiv.org/abs/2507.13919 : 76 977 osób w UK, 19 modeli, 707 kwestii, 466 769 sprawdzonych twierdzeń; post-training do +51%, prompting do +27%, personalizacja tylko +0,43 pp; im bardziej perswazyjny model, tym mniej prawdziwych twierdzeń.
  - **Trzecie źródło:** News & Views w Nature, Chiara Vargiu i Alessandro Nai (UvA), „AI chatbots can persuade voters”, Nature 648, 287–288, DOI 10.1038/d41586-025-03733-x, https://pure.uva.nl/ws/files/295900960/AI_chatbots_can_persuade_voters.pdf : kontekst (reklama < 1 pkt), zastrzeżenia (eksperymenty online, dobrowolna ekspozycja w realu), postulaty regulacyjne. Plus SMC Spain (https://sciencemediacentre.es/en/conversations-ai-chatbots-can-significantly-influence-direction-vote): Gayo Avello (samoselekcja, brak pomiaru głosowania) kontra Quattrociocchi (efekty raczej zaniżone).
  - **Dlaczego fajne:** każdy na sali głosuje i rozmawia z chatbotami; wybory w Polsce i Kanadzie; autorzy komentarza z Amsterdamu; holenderski urząd AP i ankieta UvA (1 na 10 Holendrów zapyta AI o radę wyborczą: https://www.uva.nl/en/shared-content/faculteiten/en/faculteit-der-maatschappij-en-gedragswetenschappen/news/2025/10/dont-ask-ai-for-election-advice.html ).
  - **Kontrowersja / rozjazd:** kompromis „perswazja kontra prawda”; asymetria polityczna nieprawdy; spór o trafność zewnętrzną (laboratorium vs kampania). News jest wierny paperowi; ciekawostka do analizy mediów: różne media podają różne liczby (2,3 vs 1,51 pkt).
  - **Trudność techniczna:** średnia (RCT, skala 0–100, post-training i reward modeling pod perswazję, gęstość informacji, automatyczny fact-checking twierdzeń).
  - **Pytanie do dyskusji:** Czy firma AI lub partia powinna mieć prawo optymalizować chatbota pod perswazję polityczną, skoro wiemy, że to obniża prawdomówność? Kto ma to regulować?
  - **Weryfikacja:** ✅, pewność wysoka.

### 2. METR: doświadczeni programiści z AI wolniejsi o 19%, choć byli przekonani, że szybsi: ⚠️ poprawione (pewność: wysoka)
- **Sprawdzone linki:**
  - TechCrunch (https://techcrunch.com/2025/07/11/ai-coding-tools-may-not-speed-up-every-developer-study-shows): działa; tytuł, autor (Maxwell Zeff), data 11.07.2025 zgodne; bez paywalla.
  - arXiv 2507.09089 (abs i PDF v2): działa; abs: v1 12.07.2025, v2 25.07.2025, brak journal ref; PDF v2 przeczytany (s. 1–4).
  - metr.org/blog/2026-02-24-uplift-update/: działa; trzykrotnie odpytany o dokładne sformułowania.
  - simonwillison.net (12.07.2025): działa; zgodny z opisem.
- **News a paper:** TechCrunch pisze o „nowym badaniu non-profitu METR opublikowanym w czwartek” i podaje jego liczby (16 programistów, 246 zadań, 19% wolniej, prognoza 24%). Jednoznaczne.
- **Fakty:**
  - Tytuł, autorzy, daty wersji, brak recenzji → zgodne. Uwaga: w v2 Beth Barnes podpisana jako „Beth Barnes”.
  - 16 programistów, 246 zadań, średnio 5 lat w repozytorium, Cursor Pro + Claude 3.5/3.7 Sonnet → zgodne (abstrakt v2).
  - Prognoza 24%, ocena po badaniu 20%, faktycznie +19% czasu, ekonomiści 39%, ML 38% → zgodne.
  - CI +2% do +39% → zgodne (wpis METR 2026; Fig. 1 papera).
  - 143 h nagrań ekranu → zgodne (paper s. 2: 29% wszystkich godzin).
  - „56% uczestników nie znało wcześniej Cursora” → zgodne z paperem (przypis 2: 93% używało wcześniej LLM, tylko 44% miało doświadczenie z Cursorem). **Ale TechCrunch pisze odwrotnie**: „only 56% of the developers in the study had experience using Cursor”. To błąd TechCrunch, nie narzędzia; wyszukiwacz przypisał TechCrunch poprawną wersję. Do poprawy w opisie newsa, a zarazem dobry przykład dla roli 1.
  - Wątpliwość wyszukiwacza „TechCrunch: forecasted 56%” → nieaktualna: TechCrunch podaje prawidłowo 24%; 56% pada tylko w zdaniu o Cursorze.
  - Znak w kontynuacji z 2026 → **rozstrzygnięte**: METR wprowadza akapit zdaniem „Our raw results show some evidence for speedup”, a podpis wykresu mówi, że AI z końca 2025 „likely accelerated” programistów. Zatem „speedup of -18%” (CI -38% do +9%) w konwencji METR oznacza 18% krótszy czas (oś „change in time” jak w Fig. 1 papera z 2025, gdzie wartości ujemne = krócej). Wynik nieistotny statystycznie. Nowi uczestnicy: -4% (CI -15% do +9%). 57 programistów (10 powracających, 47 nowych), 143 repozytoria, 800+ zadań, stawka 50 zamiast 150 USD/h → zgodne. Część blogów czyta to jako dalsze spowolnienie (np. particula.tech, 2.07.2026: „A speedup of -18% is an 18% slowdown”); to wbrew samemu METR. Ta niejednoznaczność notacji to świetny materiał na prezentację.
  - Uwaga: wpis METR z 2026 opisuje wynik z 2025 raz jako „20% slowdown”, a raz jako „19% longer”; różnica wynika z różnych sposobów liczenia (spowolnienie vs wydłużenie czasu), drobna.
  - Willison: jedyny uczestnik z ponad 50 h w Cursorze miał przyspieszenie; większe spowolnienie przy dobrze znanych zadaniach → zgodne.
- **Kontrowersja:** realna i dobrze udokumentowana (sami autorzy zastrzegają, że nie twierdzą, iż AI nie pomaga większości programistów; TechCrunch to powtarza). Opis wyszukiwacza uczciwy. TechCrunch nie przesadza w nagłówku („may not speed up every developer”), wręcz łagodzi; przesadzały inne media („AI spowalnia programistów”), ale tego nie weryfikowałem na konkretnych tekstach.
- **Retrakcje / korekty / krytyka / replikacje:** brak recenzowanej wersji papera (zapytanie: „Becker Rush Barnes Rein "Experienced Open-Source Developer Productivity" published conference OR journal 2026”). Brak niezależnej replikacji; jedyna kontynuacja to badanie samego METR z 2026 (zapytanie: „METR "Measuring the Impact of Early-2025 AI" critique OR rebuttal OR replication 2026”). W wynikach pojawia się analiza heterogeniczności na forum EA (Nuño Sempere, „Assessing heterogeneity in METR's late 2025 developer productivity experiment”, nieotwierana).
- **Poprawki:**
  1. Opis newsa: TechCrunch błędnie podaje, że 56% uczestników *miało* doświadczenie z Cursorem (paper: 44% miało, 56% nie miało).
  2. Znak w kontynuacji 2026 rozstrzygnięty: -18% = krótszy czas (przyspieszenie), nieistotne statystycznie; METR sam uznaje dane za obciążone w dół.
  3. Wątpliwość „forecasted 56%” usunięta (TechCrunch podaje 24%).
- **Dodatkowe znaleziska:** Rozbieżne interpretacje „-18%” w blogach z 2026 (particula.tech vs METR) to gotowy przykład, jak notacja wprowadza w błąd. Paper nie jest autorstwa Anthropic, ale testowane narzędzie to głównie Claude 3.5/3.7 Sonnet (Anthropic), a raport przygotowuje model Anthropic; warto o tym wspomnieć.
- **Ocena niezależna:** 5/5. Czysty RCT z zaskakującym wynikiem (rozjazd odczucia i pomiaru), otwarty news, otwarty paper, krytyka i kontynuacja autorów z 2026, idealna część techniczna dla Janka. Minusy: preprint, 16 osób, szybkie starzenie się. Polecam do piętnastki.
- **Do ręcznego sprawdzenia przez zespół:** nic (wszystko otwarte).
- **Opis po poprawkach:**
  - **Kategoria:** praca i produktywność
  - **News:** „AI coding tools may not speed up every developer, study shows”, Maxwell Zeff, TechCrunch, 11 lipca 2025, https://techcrunch.com/2025/07/11/ai-coding-tools-may-not-speed-up-every-developer-study-shows , paywall: nie. Artykuł zaczyna od tego, że badanie METR podważa przekonanie o przyspieszeniu doświadczonych programistów; podaje 16 osób, 246 zadań, 19% wolniej, prognozę 24%, i zastrzeżenia (mała próba, szybki postęp modeli, inne badania pokazują przyspieszenie). Zawiera błąd: pisze, że tylko 56% uczestników miało doświadczenie z Cursorem (w paperze: 44%).
  - **Paper:** „Measuring the Impact of Early-2025 AI on Experienced Open-Source Developer Productivity”, Joel Becker, Nate Rush, Beth (Elizabeth) Barnes, David Rein (METR), preprint arXiv:2507.09089 (v1 12.07.2025, v2 25.07.2025), https://arxiv.org/abs/2507.09089 , open access: tak, bez recenzji. RCT: 16 doświadczonych programistów, 246 zadań w dojrzałych repozytoriach (średnio 5 lat stażu), każde zadanie losowo z AI lub bez (Cursor Pro + Claude 3.5/3.7 Sonnet). Przewidywali przyspieszenie o 24%, po badaniu szacowali 20%, a czas wydłużył się o 19% (CI +2% do +39%); eksperci przewidywali 38–39% przyspieszenia.
  - **Trzecie źródło:** METR, 24.02.2026, „We are Changing our Developer Productivity Experiment Design”, https://metr.org/blog/2026-02-24-uplift-update/ : nowe badanie (57 osób, 143 repozytoria, 800+ zadań) daje dla powracających -18% czasu (CI -38% do +9%), dla nowych -4%; METR uznaje dane za niewiarygodne (selekcja: ludzie nie chcą pracować bez AI, niższa stawka, równoległe agenty) i przebudowuje badanie. Komentarz: Simon Willison, https://simonwillison.net/2025/Jul/12/ai-open-source-productivity/ (krzywa uczenia, znajomość repozytorium).
  - **Dlaczego fajne:** rozjazd między odczuciem a pomiarem dotyczy każdego studenta; rzadki prawdziwy RCT; kontynuacja pokazuje, że grupy kontrolnej „bez AI” nie da się już utrzymać.
  - **Kontrowersja / rozjazd:** mała, specyficzna próba; uproszczenia w mediach („AI spowalnia programistów”); błąd TechCrunch o Cursorze; sprzeczne odczytania znaku „-18%” w 2026.
  - **Trudność techniczna:** niska–średnia (RCT, przedziały ufności, selekcja, notacja „zmiana czasu” vs „przyspieszenie”).
  - **Pytanie do dyskusji:** Skoro ludzie systematycznie przeceniają, ile AI im pomaga, czy możemy ufać ankietom o produktywności z AI (w tym własnym odczuciom przy pisaniu esejów)?
  - **Weryfikacja:** ⚠️ (drobne poprawki w opisie newsa i rozstrzygnięcie znaku), pewność wysoka.

### 3. „Canaries in the Coal Mine”: AI a zatrudnienie młodych (Stanford, 2025–2026): ⚠️ poprawione (pewność: wysoka)
- **Sprawdzone linki:**
  - The Register 26.08.2025 (https://www.theregister.com/2025/08/26/ai_hurts_recent_college_grads_jobs/): działa; tytuł, autor (Thomas Claburn), data zgodne.
  - Strona papera (https://digitaleconomy.stanford.edu/publications/canaries-in-the-coal-mine): działa; rewizja 12.08.2026, link do PDF.
  - PDF 2026 (https://digitaleconomy.stanford.edu/app/uploads/2026/08/Canaries_August2026.pdf): działa; przeczytane s. 1–4 (Read zapisanego pliku).
  - Odpowiedź autorów 9.02.2026: działa; zgodna z opisem.
  - OPB (przedruk NPR, 18.08.2026): działa; zgodny z opisem.
  - The Register 1.10.2025 (Yale): **otwarty przeze mnie**, działa; nagłówek „AI has had zero effect on jobs so far, says Yale study”.
  - RePEc NBER 33777: działa; zgodne.
  - npr.org: nie próbowałem ponownie (przedruk OPB wystarcza).
- **News a paper:** The Register wymienia tytuł papera i trzech autorów ze Stanford Digital Economy Lab. NPR/OPB cytuje Brynjolfssona i jego badanie (16% spadku). Jednoznaczne.
- **Fakty:**
  - Tytuł, autorzy, working paper bez recenzji, rewizja 12.08.2026, open access → zgodne.
  - Dane ADP do czerwca 2026 → zgodne (abstrakt 2026).
  - 13% w wersji 2025 (dane styczeń 2021–lipiec 2025) → zgodne (The Register).
  - **„Liczba rosła 13% → 16% → 19%” → poprawione.** Wg PDF z sierpnia 2026 wcześniejsze wersje podawały estymację z regresji z kontrolą szoków na poziomie firmy (13% dla danych z lipca 2025; 16% dla danych z września 2025). Wersja 2026 eksponuje prostszą, opisową miarę „o ile zatrudnienie jest poniżej poziomu, gdyby rosło jak u mniej narażonych rówieśników”: wg tej miary 15% przy danych z lipca 2025 i 19% w czerwcu 2026. Czyli 19% to **inna specyfikacja** niż 13% i 16%; porównywalny wzrost to 15% → 19%. NPR (sierpień 2026) cytuje 16%, czyli estymację z regresji z wersji z jesieni 2025.
  - W liczbach bezwzględnych: zatrudnienie 22–25-latków w dwóch najbardziej narażonych kwintylach spadło o ok. 11% (XI 2022–VI 2026), w trzech najmniej narażonych wzrosło o ok. 10% (PDF 2026, s. 3).
  - Mechanizm przez mniejsze zatrudnianie, nie zwolnienia; spadek tam, gdzie AI automatyzuje → zgodne.
  - Autorzy: „early, descriptive indicators … rather than causal estimates” → zgodne. Abstrakt 2026 sam przyznaje, że wzorce słabną po kontroli wykształcenia, częściowo poprzedzają generatywną AI i są silniejsze w próbie ADP niż w ogólnokrajowych badaniach ankietowych.
  - Odpowiedź z 9.02.2026: przy efektach stałych firma × czas spadek istotny dopiero od 2024; wcześniejsze spadki „przynajmniej częściowo” z innych powodów → zgodne.
  - Yale Budget Lab (Gimbel, Kinder, Kendall, Lee), 1.10.2025, brak „discernible disruption” w 33 miesiące → zgodne (wyniki wyszukiwania i The Register).
  - Humlum i Vestergaard, NBER WP 33777, „Still Waters, Rapid Currents…”, efekty większe niż 2% wykluczone → zgodne.
  - NPR/OPB: New York Fed (praca zdalna), Ramp/Revelio (+12% stanowisk entry-level w firmach z największymi inwestycjami w AI) → zgodne; cytowani też David Deming (Harvard) i Anders Humlum.
  - The Register (2025) wspomina, że miary ekspozycji na AI pochodzą od Anthropic, OpenAI i Microsoftu. Paper nie jest autorstwa Anthropic, ale korzysta z danych Anthropic Economic Index (rozróżnienie automatyzacja/augmentacja); warto o tym wiedzieć.
- **Kontrowersja:** realna i dobrze udokumentowana (Yale, Dania, NY Fed, Ramp/Revelio, odpowiedź autorów). Opis wyszukiwacza uczciwy co do nagłówka The Register („AI robs jobs” jest mocniejsze niż deklaracja autorów). Dodatkowo: nagłówek The Register o Yale („zero effect”) też przesadza w drugą stronę (Yale pisze o braku „dostrzegalnego zakłócenia”, nie o zerowym efekcie). To dobry materiał: to samo medium, ten sam autor, dwa przeciwne, przesadzone nagłówki w odstępie 5 tygodni.
- **Retrakcje / korekty / krytyka / replikacje:** brak retrakcji (working paper). Krytyka: Yale Budget Lab, Humlum i Vestergaard, NY Fed; odpowiedź autorów (II 2026); paper 2026 cytuje wiele nowych badań z 2026 (np. Tucker 2026 z danymi administracyjnymi rządu USA, opisany jako zgodny). Zapytanie: „"Canaries in the Coal Mine" Brynjolfsson critique 2026 young workers AI employment ADP”.
- **Poprawki:**
  1. 13%, 16% i 19% to nie jedna rosnąca seria: 13% i 16% to estymacje z regresji (kontrola szoków na poziomie firmy), 19% to miara opisowa (na tej samej miarze: 15% → 19%).
  2. Dopisać zastrzeżenia z samego abstraktu 2026 (osłabienie po kontroli wykształcenia, trendy sprzed AI, różnica ADP vs dane ankietowe).
  3. Link do The Register o Yale otwarty (wcześniej tylko z wyników wyszukiwania); nagłówek „AI has had zero effect on jobs so far, says Yale study”.
- **Dodatkowe znaleziska:** Raport Yale Budget Lab w PDF (z wyników wyszukiwania, nieotwierany): https://budgetlab.yale.edu/sites/default/files/page_to_pdf/1154/publication_1154.pdf . Para nagłówków The Register (sierpień vs październik 2025) jako ćwiczenie dla roli 1.
- **Ocena niezależna:** 4/5. Bardzo relewantne dla publiczności, świetny „trójkąt” z odpowiedzią autorów, otwarte źródła, świeża rewizja z 2026. Minusy: working paper, opisowy, zmieniające się specyfikacje (co jednak samo w sobie jest lekcją). Polecam do piętnastki.
- **Do ręcznego sprawdzenia przez zespół:** nic krytycznego; ewentualnie oryginał NPR (npr.org zwracał 503 wyszukiwaczowi).
- **Opis po poprawkach:**
  - **Kategoria:** rynek pracy
  - **News:** „AI robs jobs from recent college grads, but isn't hurting wages, Stanford study says”, Thomas Claburn, The Register, 26 sierpnia 2025, https://www.theregister.com/2025/08/26/ai_hurts_recent_college_grads_jobs/ , paywall: nie. Nazywa tytuł i autorów, podaje 13% względnego spadku zatrudnienia 22–25-latków w zawodach narażonych na AI (dane ADP I 2021–VII 2025); nagłówek „AI robs jobs” jest mocniejszy niż deklaracja autorów. Drugi, świeży news: NPR, Lee V. Gaines, 18.08.2026, „Many recent grads say AI is making it harder to get a job. Economists aren't so sure”, przedruk OPB https://www.opb.org/article/2026/08/18/recent-college-grads-say-ai-is-making-it-harder-to-get-a-job-is-it/ : cytuje 16% (estymacja z jesieni 2025) i zestawia z NY Fed (praca zdalna), Ramp/Revelio (+12% entry-level), Demingiem i Humlumem.
  - **Paper:** „Canaries in the Coal Mine? Six Facts about the Recent Employment Effects of Artificial Intelligence”, Erik Brynjolfsson, Bharat Chandar, Ruyu Chen, Stanford Digital Economy Lab, working paper (bez recenzji), pierwsza wersja VIII 2025, rewizja 12.08.2026, https://digitaleconomy.stanford.edu/publications/canaries-in-the-coal-mine (PDF: https://digitaleconomy.stanford.edu/app/uploads/2026/08/Canaries_August2026.pdf ), open access: tak. Dane płacowe ADP (miliony pracowników, do VI 2026). Brak spadku zatrudnienia w całej gospodarce, ale zatrudnienie 22–25-latków w zawodach narażonych na AI jest 19% poniżej poziomu, gdyby rosło jak u mniej narażonych (miara opisowa; wcześniejsze wersje: 13% i 16% z regresji z kontrolą firmy). Działa przez mniejsze zatrudnianie; spadki tam, gdzie AI automatyzuje. Autorzy: wskaźniki opisowe, nie przyczynowe.
  - **Trzecie źródło:** odpowiedź autorów, 9.02.2026, https://digitaleconomy.stanford.edu/news/canaries-interest-rates-and-timinga-more-on-recent-drivers-of-employment-changes-for-young-workers (przy ostrzejszych kontrolach spadek istotny dopiero od 2024); Yale Budget Lab, 1.10.2025 (brak dostrzegalnego zakłócenia; omówienie: https://www.theregister.com/2025/10/01/ai_isnt_taking_people_jobs/ ); Humlum i Vestergaard, NBER WP 33777, https://ideas.repec.org/p/nbr/nberwo/33777.html (precyzyjne zero w Danii).
  - **Dlaczego fajne:** dotyczy bezpośrednio publiczności; spór „korelacja czy przyczyna” zrozumiały dla wszystkich kierunków; widać, jak media cytują różne wersje i specyfikacje (13, 16, 19%).
  - **Kontrowersja / rozjazd:** nagłówki („AI robs jobs” vs „zero effect”) kontra ostrożność autorów; konkurencyjne wyjaśnienia (stopy procentowe, praca zdalna, wykształcenie, trendy sprzed AI); sprzeczne badania.
  - **Trudność techniczna:** średnia (difference-in-differences, efekty stałe firma × czas, miary ekspozycji na AI; więcej ekonometrii niż informatyki).
  - **Pytanie do dyskusji:** Czy jako studenci powinniśmy wybierać kierunki i zawody pod kątem „odporności na AI”, skoro dowody są wciąż sporne? Jak odróżnić sygnał od paniki?
  - **Weryfikacja:** ⚠️ (poprawka interpretacji liczb), pewność wysoka.

### 4. Tajny eksperyment Uniwersytetu w Zurychu z botami AI na r/changemyview: ⚠️ poprawione (pewność: wysoka)
- **Sprawdzone linki:**
  - 404 Media (https://404media.co/researchers-secretly-ran-a-massive-unauthorized-ai-persuasion-experiment-on-reddit-users): działa; tytuł, autor (Jason Koebler), data 28.04.2025 zgodne; częściowy paywall (widoczny fragment).
  - PDF extended abstract (retractionwatch.com/wp-content/uploads/2025/04/ExtendedAbstract-Zurich-AI-Reddit.pdf): działa; przeczytany w całości (8 stron PDF: 2 strony tekstu, 2 strony bibliografii, 4 strony rycin).
  - Retraction Watch (28.04.2025, aktualizacja 30.04): działa; zgodny z opisem.
  - WAMC (przedruk NPR, 7.05.2025): działa; zgodny.
  - Dodatkowo otwarte: 404 Media, 29.04.2025, „Reddit Issuing 'Formal Legal Demands' Against Researchers Who Conducted Secret AI Experiment on Users” (https://www.404media.co/reddit-issuing-formal-legal-demands-against-researchers-who-conducted-secret-ai-experiment-on-users/); Decrypt, 30.04.2025 (https://decrypt.co/316976/secret-reddit-experiment-using-ai-personas-sparks-ethics-scandal-in-academia).
- **News a paper:** 404 Media pisze o zespole, który „podaje się za badaczy z Uniwersytetu w Zurychu” i potajemnie wpuścił boty na r/changemyview; opisuje persony (ofiara napaści seksualnej, czarnoskóry przeciwnik BLM, pracownik schroniska dla ofiar przemocy domowej) i ponad 1700 komentarzy. W widocznej części nie omawia wyników szkicu. NPR/WAMC omawia wyniki („more persuasive than the vast majority of human comments”). Para czytelna, choć „paper” to szkic.
- **Fakty:**
  - Tytuł „Can AI Change Your View? Evidence from a Large-Scale Online Field Experiment”, autorzy nieujawnieni → zgodne (PDF nie podaje nazwisk).
  - Prerejestracja, XI 2024–III 2025, 1061 postów, N=478 → zgodne.
  - Trzy warunki (generic, personalization z cechami OP wywnioskowanymi przez inny LLM z ostatnich 100 postów i komentarzy, community aligned z modelem dostrojonym na komentarzach z deltą) → zgodne.
  - Odsetki delt: personalization 0,18, generic 0,17 (dokładnie 0,168), community aligned 0,09, baseline 0,03 (0,027) → zgodne; „3–6 razy” → zgodne.
  - 99. percentyl → zgodne (personalization: 99,4% wszystkich użytkowników, 98,2% ekspertów).
  - Zatwierdzenie przez komisję etyczną UZH; „użytkownicy nigdy nie zgłaszali podejrzeń, że to AI” → zgodne.
  - **Precyzja do poprawy:** ludzki baseline to nie „wszyscy komentujący”, tylko komentarze najwyższego poziomu (bezpośrednie odpowiedzi do OP), przy czym delta liczy się, jeśli padła gdziekolwiek w wątku pod nimi (podpis Fig. 3). Wyszukiwacz podaje raz „4 strony”, raz „2-stronicowy abstrakt”: tekst ma 2 strony, cały PDF 8.
  - **Uzupełnienie:** pipeline korzystał z GPT-4o, Claude 3.5 Sonnet (Anthropic) i Llama 3.1 405B do generowania odpowiedzi, a Claude 3.5 Sonnet (z wyszukiwaniem Perplexity) do filtrowania postów i jako sędzia rankingujący (Fig. 2). Paper nie jest autorstwa Anthropic, ale używał modelu Anthropic, a raport przygotowuje Claude; warto to zaznaczyć.
  - Komisja etyczna: formalne ostrzeżenie dla kierownika, odmowa zablokowania publikacji („minimal” risks) → zgodne (Retraction Watch). Cytaty Fiesler i Gilbert → zgodne.
  - Reddit: „formal legal demands” (Ben Lee, główny radca prawny), Reddit „rozważał” kroki prawne; pozwu nie znalazłem → doprecyzowane (404 Media, 29.04.2025).
  - UZH: wyniki nie zostaną opublikowane, uczelnia bada sprawę i zapowiada ostrzejszy przegląd etyczny → zgodne (404 Media, wyniki wyszukiwania).
  - Decrypt (wg ujawnienia badaczy): 1783 komentarze, 137 delt. Uwaga: to inna jednostka niż N=478 postów w abstrakcie, więc „3–6 razy” liczone jest na poziomie postów, nie komentarzy (137/1783 ≈ 7,7% komentarzy z deltą). Nie wiem, jak dokładnie zdefiniowano obserwację; do dyskusji metodologicznej, nie jako twierdzenie.
- **Kontrowersja:** realna i bardzo dobrze udokumentowana (moderatorzy, Reddit, Retraction Watch, eksperci od etyki). Opis wyszukiwacza uczciwy. Krytyka metodologiczna (brak recenzji, porównywalność baseline'u, inne boty na forum) to w dużej mierze własne uwagi wyszukiwacza, a nie opublikowana krytyka; w prezentacji trzeba to przedstawić jako pytania, nie ustalenia.
- **Retrakcje / korekty / krytyka / replikacje:** paper nigdy nie został opublikowany (autorzy i UZH zrezygnowali). Nie znalazłem recenzowanej analizy tego przypadku z 2026 w czasopiśmie etyki badań. Zapytania: „University of Zurich Reddit changemyview AI experiment Reddit legal demands outcome ethics review changes”, „r/changemyview Zurich AI experiment research ethics analysis journal article 2026”, „"changemyview" "Zurich" bots experiment lessons research ethics commentary Nature OR Science … 2025 2026”.
- **Poprawki:**
  1. Baseline = komentarze najwyższego poziomu, nie wszyscy komentujący.
  2. Reddit wystosował „formal legal demands”; brak informacji o pozwie.
  3. Długość: 2 strony tekstu (PDF 8 stron z bibliografią i rycinami).
  4. Dopisać, że w eksperymencie użyto m.in. Claude 3.5 Sonnet (Anthropic).
- **Dodatkowe znaleziska:** Szkic sam cytuje paper z pary 8 (Salvi et al.) i badanie perswazyjności Anthropic (Durmus et al. 2024); dobrze łączy się z parami 1 i 8.
- **Ocena niezależna:** 4/5. Najlepszy kandydat na dyskusję o etyce eksperymentów (zgoda, fałszywe tożsamości, profilowanie), każdy zna Reddita. Słabość: „paper” to nierecenzowany, wycofany z obiegu szkic, więc część techniczna musi opierać się na pipeline'ie z Fig. 2 i na krytycznej analizie metryki „delta”. Polecam do piętnastki jako parę „etyczną”, najlepiej z parą 1 lub 8 jako tłem.
- **Do ręcznego sprawdzenia przez zespół:** pełny tekst 404 Media (częściowy paywall).
- **Opis po poprawkach:**
  - **Kategoria:** etyka eksperymentów z AI / perswazja
  - **News:** „Researchers Secretly Ran a Massive, Unauthorized AI Persuasion Experiment on Reddit Users”, Jason Koebler, 404 Media, 28 kwietnia 2025, https://404media.co/researchers-secretly-ran-a-massive-unauthorized-ai-persuasion-experiment-on-reddit-users , paywall: częściowy. Akcent na etykę: fałszywe persony (ofiara napaści, czarnoskóry przeciwnik BLM, pracownik schroniska), profilowanie użytkowników z historii postów, ponad 1700 komentarzy. Drugi news: NPR, 7.05.2025, „A controversial experiment on Reddit reveals the persuasive powers of AI”, przedruk WAMC https://www.wamc.org/2025-05-07/a-controversial-experiment-on-reddit-reveals-the-persuasive-powers-of-ai (rozmowa z Tomem Bartlettem z The Atlantic; wyniki i etyka).
  - **Paper:** „Can AI Change Your View? Evidence from a Large-Scale Online Field Experiment”, anonimowi autorzy z Uniwersytetu w Zurychu, extended abstract 2025, nieopublikowany, kopia: https://retractionwatch.com/wp-content/uploads/2025/04/ExtendedAbstract-Zurich-AI-Reddit.pdf , open access: tak (kopia). Prerejestrowany eksperyment terenowy XI 2024–III 2025: 1061 postów, N=478; trzy warunki (generic, personalization, community aligned); odpowiedzi z GPT-4o, Claude 3.5 Sonnet i Llama 3.1 405B, wybierane przez sędziego-LLM. Odsetek z deltą 0,17–0,18 (generic, personalization) i 0,09 (community aligned) vs 0,03 u ludzi (komentarze najwyższego poziomu); personalizacja w 99. percentylu użytkowników.
  - **Trzecie źródło:** Retraction Watch, Kate Travis, 28.04.2025, https://retractionwatch.com/2025/04/28/experiment-using-ai-generated-posts-on-reddit-draws-fire-for-ethics-concerns/ : komisja etyczna dała ostrzeżenie, ale nie zablokowała publikacji; Casey Fiesler: jedno z najgorszych naruszeń etyki badań; Sara Gilbert: utrata zaufania społeczności. Plus 404 Media, 29.04.2025 (formalne żądania prawne Reddita): https://www.404media.co/reddit-issuing-formal-legal-demands-against-researchers-who-conducted-secret-ai-experiment-on-users/
  - **Dlaczego fajne:** realni ludzie bez zgody, fałszywe tożsamości, a jednocześnie wynik ważny dla demokracji (boty przekonujące i niewykrywalne). Każdy zna Reddita.
  - **Kontrowersja / rozjazd:** „ważna wiedza vs zgoda”; kto decyduje: komisja, platforma, społeczność? Metodologicznie: brak recenzji, jednostka analizy (posty vs komentarze), definicja baseline'u; media skupiły się na etyce, a liczby „3–6×” krążyły bez krytycznej oceny.
  - **Trudność techniczna:** niska–średnia (pipeline: LLM profilujący z historii postów, fine-tuning na komentarzach z deltą, sędzia-LLM w turnieju, randomizacja warstwowa).
  - **Pytanie do dyskusji:** Gdyby wynik był ważny dla obrony przed botami wyborczymi, czy usprawiedliwiałby oszukanie użytkowników forum liczącego prawie 4 mln osób? Kto powinien decydować: uczelniana komisja, platforma czy społeczność?
  - **Weryfikacja:** ⚠️ (drobne poprawki), pewność wysoka.

### 5. Ile wody i energii zużywa jeden prompt? Google „pięć kropli” kontra „butelka wody na maila”: ⚠️ poprawione (pewność: wysoka co do paperów, średnia co do newsa)
- **Sprawdzone linki:**
  - Android Headlines (25.08.2025): działa; tytuł, autor (Tyler Lee) zgodne; bez paywalla.
  - ScienceBlog (10.07.2026): działa; zgodny z opisem.
  - arXiv 2508.15734 (abs i HTML v1): działa; zgodne.
  - arXiv 2304.03271: działa; v1 6.04.2023 … v5 26.03.2025, „Accepted by Communications of the ACM”.
  - arXiv 2603.02705: działa; zgodne (v1 3.03.2026, rewizja 18.03.2026).
  - IBTimes (26.06.2026): działa; zgodny częściowo (patrz niżej).
  - The Verge: nie otwierałem (domena zablokowana); URL zwrócony przez Android Headlines: https://www.theverge.com/report/763080/google-ai-gemini-water-energy-emissions-study . Tytuł wg wyników wyszukiwania (agregator RSS): „Google says a typical AI text prompt only uses 5 drops of water — experts say that's misleading” (niepewne, z drugiej ręki).
  - Washington Post 2024: nie otwierałem (403).
  - Dodatkowo otwarte: MIT Technology Review, Casey Crownhart, 21.08.2025, „In a first, Google has released data on how much energy an AI prompt uses” (https://www.technologyreview.com/2025/08/21/1122288/google-gemini-ai-energy/) i 28.08.2025, „Google's still not giving us the full picture on AI energy use” (https://www.technologyreview.com/2025/08/28/1122685/ai-energy-use-gemini/).
- **News a paper:** Android Headlines nazywa raport Google i podaje jego liczby; krytykę Rena i de Vries-Gao przytacza za The Verge. MIT TR (21.08) wprost omawia raport techniczny Google z cytatami Jeffa Deana i niezależnych ekspertów.
- **Fakty:**
  - Autorzy (12 osób, wszyscy Google), arXiv 21.08.2025, brak recenzji, open access → zgodne.
  - 0,24 Wh, 0,03 g CO2e, 0,26 ml; 33× (energia) i 44× (emisje) w okresie V 2024–V 2025 → zgodne.
  - Woda: kategoria 2 WUE (pobór minus zwrot), bez wody na produkcję prądu; emisje market-based (94 gCO2e/kWh w 2024); wąska granica 0,10 Wh; porównania Li et al. 10–50 ml, Mistral 45 ml, Epoch 0,3 Wh → zgodne (HTML v1).
  - Li et al.: 700 000 l (trening GPT-3), 4,2–6,6 mld m³ (2027) → zgodne. CACM: arXiv podaje „accepted”, wyniki wyszukiwania podają publikację w CACM w 2025; tom i numer niepotwierdzone. Liczba „ok. 500 ml na 10–50 odpowiedzi” nie jest w abstrakcie; ScienceBlog przypisuje ją temu paperowi (prawdopodobnie z treści; niepewne, nie sprawdziłem w PDF).
  - „Small Bottle, Big Pipe”: Han, Li, Wierman, Ren; 697–1451 mln galonów dziennie do 2030; porównanie z ok. 1000 MGD Nowego Jorku → zgodne.
  - IBTimes: „największy szacunek ok. 2000× większy od najmniejszego” → zgodne; LBNL 228 mld galonów w 2023 (17 mld bezpośrednio, ok. 211 mld pośrednio przez prąd) → zgodne z artykułem. Uwaga: IBTimes nie omawia jednego raportu, tylko streszcza analizę CBS News i dane LBNL/IEA; słabe źródło.
  - **Android Headlines myli pojęcia:** pisze, że Google pominęło „indirect water use … for instance, the water used in the cooling systems”. To błąd: Google wlicza wodę chłodzenia na miejscu, a pomija wodę pośrednią z produkcji energii. Krytyka Rena dotyczy właśnie tej drugiej. Wyszukiwacz opisał krytykę poprawnie, ale nie zauważył błędu w newsie.
- **Kontrowersja:** ma realne źródła: Ren i de Vries-Gao (za The Verge i Android Headlines), Sasha Luccioni (Hugging Face) oraz Chung i Chowdhury (ML.Energy) w MIT TR (market-based emissions, mediana zamiast sumy, brak liczby zapytań). Opis wyszukiwacza uczciwy, a teza „obie liczby mogą być prawdziwe przy różnych granicach” jest dobrze podparta (ScienceBlog: „The studies are not measuring the same thing”).
- **Retrakcje / korekty / krytyka / replikacje:** nie znaleziono recenzowanej wersji raportu Google ani formalnej odpowiedzi w czasopiśmie (zapytanie: „"Measuring the environmental impact of delivering AI at Google Scale" critique OR response OR peer-reviewed 2026”). Kontynuacja Rena z 2026 (Small Bottle, Big Pipe) potwierdzona.
- **Poprawki:**
  1. Android Headlines błędnie opisuje „wodę pośrednią” jako wodę chłodzenia; to błąd newsa (dobry materiał dla roli 1), nie papera.
  2. Lepszy, otwarty news z renomowanego medium istnieje: MIT TR (Crownhart, 21.08.2025 i 28.08.2025) z niezależnymi ekspertami. Proponuję go jako news główny, a Android Headlines jako przykład zniekształcenia.
  3. IBTimes to streszczenie analizy CBS News, nie „raport”.
  4. Status CACM: „accepted” wg arXiv; tom/numer niepotwierdzone.
- **Dodatkowe znaleziska:** MIT TR 28.08.2025 wylicza, czego brakuje w raporcie Google (łączna liczba zapytań, obrazy i wideo, modele rozumujące) i pokazuje, że przy 2,5 mld zapytań dziennie ChatGPT (0,34 Wh każde) daje to ponad 300 GWh rocznie. To świetny materiał do pokazania „mediana na prompt vs suma”.
- **Ocena niezależna:** 4/5. Namacalny spór o liczby, dobra lekcja o granicach systemu i konflikcie interesów (Google mierzy siebie), holenderski akcent (de Vries-Gao, VU). Minusy: główny paper to raport firmy bez recenzji; przeciwny paper Li et al. jest z 2023 (dla AI starszy), choć z kontynuacją 2026. Polecam do piętnastki z MIT TR jako newsem.
- **Do ręcznego sprawdzenia przez zespół:** artykuł The Verge (zablokowany; sprawdzić tytuł, datę i dokładne cytaty Rena i de Vries-Gao); artykuł Washington Post z 18.09.2024 (403).
- **Opis po poprawkach:**
  - **Kategoria:** ślad środowiskowy AI
  - **News:** „In a first, Google has released data on how much energy an AI prompt uses”, Casey Crownhart, MIT Technology Review, 21 sierpnia 2025, https://www.technologyreview.com/2025/08/21/1122288/google-gemini-ai-energy/ , paywall: możliwy limit darmowych artykułów (narzędzie otworzyło pełny tekst). Chwali przejrzystość raportu, ale cytuje Luccioni (to firma decyduje, co ujawnić; brak łącznej liczby zapytań) i Chunga/Chowdhury'ego (emisje market-based, mediana). Kontynuacja: „Google's still not giving us the full picture on AI energy use”, 28.08.2025, https://www.technologyreview.com/2025/08/28/1122685/ai-energy-use-gemini/ . Alternatywnie, jako przykład zniekształcenia: Android Headlines, Tyler Lee, 25.08.2025, „Google Says AI Is Tiny on Resources, Experts Say It's Much Bigger”, https://www.androidheadlines.com/2025/08/google-says-ai-is-tiny-on-resources-experts-say-its-much-bigger.html (krytyka Rena i de Vries-Gao za The Verge, z błędnym opisem wody pośredniej). Objaśniacz 2026: ScienceBlog, 10.07.2026, https://scienceblog.com/t-writing-a-single-100-word-email-with-chatgpt-consumes-approximately-the-volume-of-a-standard-bottle-of-water-the-global-infrastructure-processing-ai-queries-is-projected-to-use-the-equivalent-of-hal/
  - **Paper:** „Measuring the environmental impact of delivering AI at Google Scale”, Elsworth, Huang, Patterson, Schneider, Sedivy, Goodman, Townsend, Ranganathan, Dean, Vahdat, Gomes, Manyika (Google), raport techniczny arXiv:2508.15734, 21.08.2025, https://arxiv.org/abs/2508.15734 , open access: tak, bez recenzji. Pomiar w produkcji: medianowy prompt tekstowy Gemini Apps = 0,24 Wh, 0,03 g CO2e, 0,26 ml wody; spadek 33× (energia) i 44× (emisje) w rok. Woda tylko konsumpcyjna na miejscu (bez wody na produkcję prądu), emisje market-based; wąska granica (same akceleratory) dałaby 0,10 Wh. Paper przeciwny: Li, Yang, Islam, Ren, „Making AI Less 'Thirsty'…”, arXiv:2304.03271 (v5 26.03.2025), przyjęty do Communications of the ACM, https://arxiv.org/abs/2304.03271 : 700 000 l na trening GPT-3, 4,2–6,6 mld m³ poboru w 2027.
  - **Trzecie źródło:** Han, Li, Wierman, Ren, „Small Bottle, Big Pipe…”, arXiv:2603.02705, marzec 2026, https://arxiv.org/abs/2603.02705 : 697–1451 mln galonów dziennie nowej przepustowości wodociągów w USA do 2030 (porównywalne z dziennym zaopatrzeniem Nowego Jorku); skutki lokalne. Plus krytyka Rena i de Vries-Gao w The Verge (do ręcznego sprawdzenia).
  - **Dlaczego fajne:** każdy słyszał „butelka wody na maila” albo „pięć kropli”; obie liczby mogą być „prawdziwe” przy różnych granicach (woda bezpośrednia vs pośrednia, mediana vs suma, market- vs location-based); konflikt interesów; holenderski akcent.
  - **Kontrowersja / rozjazd:** media w 2024 uogólniły „butelkę na maila”; Google w 2025 wybrało korzystne granice; Android Headlines pomylił pojęcia; spór naukowców z firmą.
  - **Trudność techniczna:** średnia (WUE, PUE, scope 2 market vs location, wnioskowanie vs trening, batching i bezczynne maszyny).
  - **Pytanie do dyskusji:** Kto powinien liczyć ślad środowiskowy AI: firmy same o sobie, naukowcy z niepełnymi danymi czy regulator? Czy indywidualne „oszczędzanie promptów” ma sens, czy problem jest systemowy (lokalne wodociągi)?
  - **Weryfikacja:** ⚠️ (zmiana newsa głównego, poprawka opisu Android Headlines), pewność wysoka co do paperów, średnia co do The Verge.

### 6. Bot AI, który przechodzi 99,8% testów uwagi: zagrożenie dla badań ankietowych (PNAS 2025): ✅ potwierdzone (pewność: wysoka)
Uwaga: wyszukiwacz weryfikował tę parę bez WebSearch (wyczerpany limit). Wszystkie pola oznaczone jako niepewne sprawdziłem od nowa.
- **Sprawdzone linki:**
  - 404 Media (https://www.404media.co/a-researcher-made-an-ai-that-completely-breaks-the-online-surveys-scientists-rely-on/): działa; tytuł, autor (Emanuel Maiberg), data 17.11.2025 zgodne. Paywall: narzędzie tym razem nie widziało blokady, wyszukiwacz widział wymóg logowania; 404 Media często wymaga darmowej rejestracji (niepewne).
  - PNAS (pnas.org): nie próbowałem ponownie (403 u wyszukiwacza); zamiast tego Europe PMC (API) i pełny tekst w PMC: https://pmc.ncbi.nlm.nih.gov/articles/PMC12663962/ (otwarty).
  - Dartmouth (28.04.2026): działa; zgodny.
  - APS Observer (27.03.2026): działa; zgodny.
  - Research Live (23.04.2026): działa; zgodny.
  - CloudResearch (Aaron Moss, 23.07.2026, „AI and the Future of Survey Fraud”): działa; zgodny (głównie promocja własnych rozwiązań).
  - Dodatkowo otwarte: odpowiedź Rothschilda i in. (PDF, https://researchdmr.com/files/Letter_Westwood.pdf ), metadane listów w PNAS z 2026 (Europe PMC).
- **News a paper:** 404 Media nazywa Seana Westwooda (Dartmouth, Polarization Research Lab), czasopismo PNAS i podaje liczby z papera. Jednoznaczne. Zgodnie z narzędziem brak głosów zewnętrznych.
- **Fakty:**
  - Tytuł, autor (jedyny: Sean J. Westwood), PNAS 122(47), e2518075122, DOI 10.1073/pnas.2518075122 → zgodne. Data: Europe PMC podaje wydanie elektroniczne 20.11.2025, PMC 25.11.2025, a 404 Media pisało 17.11.2025; dokładny dzień publikacji online niepewny (listopad 2025).
  - **Open access: tak** (licencja CC BY-NC-ND, PMC12663962, PMID 41264250) → uzupełnione (wyszukiwacz: „niepewne”).
  - 99,8% z 6000 prób testów uwagi → zgodne (abstrakt).
  - Ok. 0,05 USD za odpowiedź vs 1,50 USD za człowieka (marża ponad 96,8%) → zgodne (PMC).
  - 7 sondaży z 2024, 10–52 fałszywe odpowiedzi wystarczą do zmiany prowadzącego kandydata → zgodne (PMC).
  - Działa przy promptach po rosyjsku, mandaryńsku i koreańsku → zgodne.
  - „Reverse shibboleth”: agent strategicznie odmawia 97,7% takich zadań → zgodne, doprecyzowane.
  - Wnioskowanie hipotezy badacza i jej „potwierdzanie” → zgodne (abstrakt).
  - **Uzupełnienie:** główny model to OpenAI o4-mini, wynik potwierdzony na 9 innych modelach, w tym Claude (Anthropic), Gemini i Llama. Paper nie jest autorstwa Anthropic.
  - **Uzupełnienie:** paper sam przyznaje, że nie ma bezpośredniego porównania danych syntetycznych z dużą próbą ludzką (PMC), co potwierdza zarzut z Research Live.
  - Nagroda Cozzarelli 2025 (kategoria Behavioral and Social Sciences), komunikat z 28.04.2026 → zgodne.
  - APS Observer: cytat „just because it's possible doesn't mean that it's common” pada z ust Justina Sulika (LMU Monachium); odsetki porażek w teście na AI: zweryfikowani ludzie ok. 2%, Prolific 6%, CloudResearch 10%, MTurk 40% (wg preprintu cytowanego przez APS). Uwaga: w artykule wypowiada się też Leib Litman, współzałożyciel CloudResearch (konflikt interesów).
  - Research Live: Andrew Gordon (Prolific), zarzuty (agent zbudowany pod konkretną ankietę, kod nieudostępniony, ok. 75% trafności w stolicach stanów, brak porównania z ludźmi, zabezpieczenia platform „close to 100%”) → zgodne.
- **Kontrowersja:** realna i lepsza, niż opisał wyszukiwacz: istnieje formalna wymiana w PNAS (patrz niżej). Opis „news straszy bardziej, niż paper udowadnia” jest uczciwy: nagłówek „completely breaks” mówi o fakcie dokonanym, a paper demonstruje możliwość (choć sam tytuł papera też jest mocny: „existential threat”).
- **Retrakcje / korekty / krytyka / replikacje:**
  - **Nowe (ważne):** list w PNAS: Van der Stigchel, Strauch, de Zwart, Van Maanen (**Helmholtz Institute, Uniwersytet w Utrechcie**), „Will online behavioral research follow the fate of online survey research?”, PNAS 123(8), e2535585123, 18.02.2026, open access (CC BY). Odpowiedź: Westwood i Frederick (Penn), „Reply to Van der Stigchel et al.: Empirical evidence that AI survey contamination is real and substantial”, PNAS 123(8), e2537420123, 18.02.2026, open access. (Metadane z Europe PMC; treści listów nie czytałem.)
  - **Nowe:** Rothschild (Microsoft Research), Barari (NORC), Buskirk (Old Dominion), Gordon (Prolific), Hillygus (Duke), „Reply to Westwood: Questioning the empirical evidence that AI survey contamination is real and substantial”, złożony do PNAS 27.02.2026, odrzucony 22.05.2026, opublikowany jako „pre-preprint”: https://researchdmr.com/files/Letter_Westwood.pdf (przeczytany). Zarzuty: mieszanie trzech różnych zjawisk (ludzie wspomagani LLM, prosty agent z linkiem, autonomiczny agent w panelu), brak benchmarków, kod Westwooda nieudostępniony. Konflikt interesów zadeklarowany (Gordon pracuje w Prolific, Rothschild doradzał Prolific).
  - Brak korekt i retrakcji (Europe PMC nie pokazuje; zapytania: „PNAS letter reply Westwood synthetic respondent online survey 2026 "existential threat" response”, „Westwood "The potential existential threat…" PNAS”).
- **Poprawki:** open access: tak (było „niepewne”); data publikacji doprecyzowana; dopisany model o4-mini i testy na 9 modelach (w tym Claude); dopisana wymiana listów w PNAS (2026) i odrzucona odpowiedź Rothschilda i in.; autor cytatu w APS (Sulik) i konflikt interesów Litmana.
- **Dodatkowe znaleziska:** List w PNAS jest autorstwa psychologów z **Uniwersytetu w Utrechcie**, czyli uczelni macierzystej UCU. To bardzo mocny lokalny haczyk: zespół może zapytać, czy badania online na UU (i ankiety studentów UCU) są zagrożone. „Trójkąt” jest tu kompletny i recenzowany: paper, list krytyczny, odpowiedź autora, plus odrzucona krytyka branży.
- **Ocena niezależna:** 5/5. Recenzowany, otwarty, nagrodzony paper; namacalny dla studentów (Prolific, ankiety na zajęcia); news z wyraźną przesadą w nagłówku; pełna wymiana krytyczna w PNAS z udziałem Utrechtu; świetna część techniczna (agent LLM z personą i pamięcią). Polecam do piętnastki (jeden z najmocniejszych).
- **Do ręcznego sprawdzenia przez zespół:** pełny tekst 404 Media (możliwa rejestracja); treść listów Van der Stigchela i in. oraz Westwooda i Fredericka w PNAS (open access, ale pnas.org blokowało narzędzie).
- **Opis po poprawkach:**
  - **Kategoria:** AI w nauce / polityka (sondaże)
  - **News:** „A Researcher Made an AI That Completely Breaks the Online Surveys Scientists Rely On”, Emanuel Maiberg, 404 Media, 17 listopada 2025, https://www.404media.co/a-researcher-made-an-ai-that-completely-breaks-the-online-surveys-scientists-rely-on/ , paywall: możliwy wymóg darmowej rejestracji (niepewne). Nazywa autora i PNAS, podaje 99,8%, 5 centów vs 1,50 USD, 10–52 odpowiedzi w 7 sondażach z 2024; brak głosów zewnętrznych, a nagłówek („completely breaks”) sugeruje problem już powszechny.
  - **Paper:** „The potential existential threat of large language models to online survey research”, Sean J. Westwood (Dartmouth), *PNAS* 122(47), e2518075122 (listopad 2025), DOI 10.1073/pnas.2518075122, pełny tekst: https://pmc.ncbi.nlm.nih.gov/articles/PMC12663962/ , open access: tak (CC BY-NC-ND). Autonomiczny „syntetyczny respondent” (głównie o4-mini, sprawdzony na 9 innych modelach) wypełnia ankiety z dopasowaną personą i pamięcią; zdał 99,8% z 6000 prób testów uwagi, odmawia 97,7% zadań „reverse shibboleth”, potrafi wywnioskować i „potwierdzić” hipotezę badacza; 10–52 fałszywe odpowiedzi za ok. 5 centów wystarczyłyby do odwrócenia prowadzenia w 7 sondażach z 2024. Paper sam przyznaje brak bezpośredniego porównania z próbą ludzką.
  - **Trzecie źródło:** list w PNAS z Uniwersytetu w Utrechcie: Van der Stigchel i in., „Will online behavioral research follow the fate of online survey research?”, PNAS 123(8), e2535585123 (18.02.2026), z odpowiedzią Westwooda i Fredericka (e2537420123); odrzucona przez PNAS krytyka Rothschilda i in.: https://researchdmr.com/files/Letter_Westwood.pdf ; APS Observer, 27.03.2026, https://www.psychologicalscience.org/publications/observer/humans-not-bots.html (większym zagrożeniem są ludzie, nie boty); Research Live (Prolific), 23.04.2026, https://www.research-live.com/article/opinion/the-right-safeguards-can-protect-public-opinion-polls-from-ai-pollution/id/5148723 .
  - **Dlaczego fajne:** studenci UCU sami robią ankiety i biorą udział w płatnych badaniach (Prolific); sondaże dotyczą każdego; krytyka pochodzi m.in. z Utrechtu.
  - **Kontrowersja / rozjazd:** możliwość vs powszechność; nagłówek newsa przesadza; krytycy z branży paneli mają konflikt interesów (Prolific, CloudResearch), ale ich zarzuty (kod, benchmarki, definicje) są merytoryczne; spór toczy się w PNAS.
  - **Trudność techniczna:** średnia (agent LLM z pamięcią i personą, testy uwagi, „reverse shibboleth”, detekcja botów na poziomie platformy).
  - **Pytanie do dyskusji:** Jeśli nie da się już odróżnić człowieka od AI w ankiecie online, czy wyniki badań psychologicznych i sondaży z ostatnich lat są wiarygodne? Kto ma udowodnić, że problem jest (albo nie jest) powszechny?
  - **Weryfikacja:** ✅, pewność wysoka.

### 7. Sfałszowane badanie MIT o AI w laboratorium materiałowym (Toner-Rodgers, 2024–2025): ✅ potwierdzone (pewność: wysoka)
Uwaga: wyszukiwacz weryfikował tę parę bez WebSearch; sprawdziłem wszystko od nowa.
- **Sprawdzone linki:**
  - tovima.com (przedruk WSJ): działa; tytuł, autorzy (Kevin T. Dugan, Justin Lahart), data 26.11.2025 zgodne. Licencja: To Vima prowadzi anglojęzyczne wydanie we współpracy z WSJ i jest „publishing partner” WSJ (wyniki wyszukiwania, m.in. newgreektv.com, Wikipedia). Przedruk legalny.
  - TechCrunch (17.05.2025): działa; zgodny; zawiera dwa linki WSJ (nieotwierane, paywall).
  - The Decoder (17.05.2025, Matthias Bastian): działa; zgodny.
  - arXiv 2412.17866: działa; v1 21.12.2024, v2 20.05.2025 (wycofana); v1 nadal dostępna (https://arxiv.org/abs/2412.17866v1 , otwarta).
  - MIT Economics (16.05.2025): działa; zgodne.
- **News a paper:** WSJ (przedruk) i TechCrunch nazywają tytuł i autora. Jednoznaczne.
- **Fakty:**
  - Tytuł, autor, v1/v2, złożony do QJE → zgodne.
  - 1018 naukowców, +44% materiałów, +39% zgłoszeń patentowych, +17% innowacji produktowych → zgodne (abstrakt v1). Uzupełnienie: abstrakt podaje też, że AI zautomatyzowało 57% zadań „generowania pomysłów”, a 82% naukowców zgłosiło mniejszą satysfakcję z pracy.
  - Powód wycofania z arXiv: „concerns about the validity of the data and incomplete Institutional Review Board requirements” → zgodne.
  - MIT: „no confidence in the provenance, reliability or validity of the data” → zgodne; MIT poprosiło o wycofanie z arXiv i QJE; autor nie jest już na MIT.
  - WSJ: Acemoglu i Autor, cytowanie w zeznaniach w Kongresie (XI 2024), Charles Elkan (list z 5.01.2025), zaprzeczenia Corning i 3M → zgodne.
  - **„Autor przyznał się do nieuczciwości” → zgodne:** WSJ cytuje jego wiadomość na WhatsAppie, w której nazywa to „huge and embarrassing act of dishonesty”.
  - The Decoder: odnotowuje wcześniejsze relacje m.in. w Nature → zgodne.
- **Kontrowersja:** w pełni udokumentowana (MIT, arXiv, WSJ). Opis wyszukiwacza uczciwy.
- **Retrakcje / korekty / krytyka / replikacje:** wycofanie z arXiv (V 2025); poza tym dodatkowo: Corning złożył skargę do WIPO w sprawie domeny „corning research” zarejestrowanej przez autora (wyniki wyszukiwania; nieotwierane). Zapytanie: „Aidan Toner-Rodgers 2026 MIT AI materials paper fraud aftermath”. Nie znalazłem nowych faktów z 2026.
- **Poprawki:** brak istotnych (uzupełnienia: 57% i 82% z abstraktu; potwierdzenie licencji tovima.com).
- **Dodatkowe znaleziska:** w wynikach wyszukiwania są analizy blogowe („Materials of Fraud”, someunpleasant.substack.com; „The AI-Productivity Paper That Fooled a Nobel”, nicolasrasmont.substack.com), nieotwierane; mogą pomóc w roli 1.
- **Ocena niezależna:** 4/5. Znakomita historia medialna i lekcja o preprintach i confirmation bias, otwarte źródła, legalny przedruk WSJ. Minusy: paper jest sfałszowany, więc część techniczna to analiza czerwonych flag, a nie wyniku; nakłada się z grupą 5 (oszustwa naukowe). Polecam do piętnastki, jeśli orchestrator nie przypisze go grupie 5.
- **Do ręcznego sprawdzenia przez zespół:** oryginalne teksty WSJ (paywall): https://www.wsj.com/economy/will-ai-help-hurt-workers-income-productivity-5928a389 i https://www.wsj.com/tech/ai/mit-says-it-no-longer-stands-behind-students-ai-research-paper-11434092 (linki z TechCrunch, nieotwierane).
- **Opis po poprawkach:**
  - **Kategoria:** AI w nauce i produktywność (nakłada się z grupą 5)
  - **News:** „An MIT Student Awed Top Economists With His AI Study—Then It All Fell Apart”, Kevin T. Dugan i Justin Lahart, The Wall Street Journal, 26 listopada 2025; licencjonowany przedruk w To Vima (partner WSJ): https://www.tovima.com/wsj/an-mit-student-awed-top-economists-with-his-ai-study-then-it-all-fell-apart/ , paywall: oryginał tak, przedruk nie. Opisuje entuzjazm Acemoglu i Autora, cytowanie w Kongresie, wątpliwości Elkana, zaprzeczenia Corning i 3M oraz przyznanie się autora. Drugi news: TechCrunch, Anthony Ha, 17.05.2025, „MIT disavows doctoral student paper on AI's productivity benefits”, https://techcrunch.com/2025/05/17/mit-disavows-doctoral-students-paper-on-ai-productivity-benefits .
  - **Paper:** „Artificial Intelligence, Scientific Discovery, and Product Innovation”, Aidan Toner-Rodgers (MIT), preprint arXiv:2412.17866, v1 21.12.2024 (https://arxiv.org/abs/2412.17866v1 , dostępna), wycofany w v2 20.05.2025; złożony do QJE, nigdy nieopublikowany. Twierdził, że narzędzie AI u 1018 naukowców R&D dało +44% materiałów, +39% patentów, +17% innowacji produktowych, przy spadku satysfakcji z pracy u 82% naukowców. Dane uznane przez MIT za niewiarygodne.
  - **Trzecie źródło:** MIT Economics, 16.05.2025, „Assuring an accurate research record”, https://economics.mit.edu/news/assuring-accurate-research-record ; The Decoder, https://the-decoder.com/mit-says-a-high-profile-ai-productivity-study-used-data-that-cannot-be-trusted/
  - **Dlaczego fajne:** wynik „za dobry, żeby był prawdziwy” pasował do narracji wszystkich stron, więc nikt go nie sprawdził; noblista go promował; niezrecenzowany preprint trafił do Kongresu.
  - **Kontrowersja / rozjazd:** całkowite fałszerstwo; dlaczego media i ekonomiści nie zauważyli czerwonych flag (anonimowa firma, nieprawdopodobna skala)?
  - **Trudność techniczna:** niska–średnia (projekt naturalnego eksperymentu w firmie, wskaźniki patentowe, rozpoznawanie czerwonych flag w danych).
  - **Pytanie do dyskusji:** Dlaczego tak chętnie wierzymy badaniom, które potwierdzają nasze oczekiwania wobec AI? Czy preprinty o AI powinny trafiać do mediów i polityków przed recenzją?
  - **Weryfikacja:** ✅, pewność wysoka.

### 8. „AI wygrywa 64% debat”: GPT-4 z danymi o rozmówcy (Nature Human Behaviour 2025): ⚠️ poprawione (pewność: wysoka)
Uwaga: wyszukiwacz nie otworzył wersji czasopiśmienniczej (limit wyszukiwań). Sprawdziłem ją i znalazłem **korektę autorską z 3 września 2026**, która zmienia interpretację.
- **Sprawdzone linki:**
  - eWeek (https://www.eweek.com/news/ai-debates-persuasion/): działa; tytuł, autorka (Liz Ticong), 22.05.2025 (akt. 23.05) zgodne; bez paywalla.
  - arXiv 2403.14380v1: nie otwierałem ponownie (wersja czasopiśmiennicza ma pierwszeństwo).
  - Nature Human Behaviour (https://www.nature.com/articles/s41562-025-02194-6): działa po 2 przekierowaniach; otwarty.
  - Korekta autorska (https://www.nature.com/articles/s41562-026-02588-0 , DOI 10.1038/s41562-026-02588-0): działa po przekierowaniach; przeczytana.
  - RePEc (metadane NHB): działa.
  - scimex.org: HTTP 403 (także u mnie).
- **News a paper:** eWeek nazywa czasopismo, podaje 900 uczestników, 64% i 81%, cytuje Salviego. Jednoznaczne.
- **Fakty:**
  - **Tytuł wersji NHB: „On the conversational persuasiveness of GPT-4”** (inny niż preprint) → poprawione.
  - NHB 9(8), 1645–1653, online 19.05.2025, DOI 10.1038/s41562-025-02194-6 → uzupełnione.
  - **Open access: tak** (strona Nature, wersja w PMC: PMC12367540) → uzupełnione.
  - N=900 (wersja NHB; preprint v1: 820) → poprawione, zgodne z eWeek.
  - 64,4%: dotyczy wyłącznie warunku GPT-4 z personalizacją i tylko par debat, w których AI i człowiek nie byli równie przekonujący (81,2% względny wzrost szans na wyższą zgodę po debacie, 95% CI +26,0% do +160,7%) → interpretacja wyszukiwacza poprawna. eWeek w treści to zaznacza („in 64.4% of debates with clear results”), ale nagłówek uogólnia do „AI Wins 64% of Online Arguments”.
  - Projekt 2×2×3 (człowiek/GPT-4, z danymi/bez, siła opinii) → zgodne.
  - **Korekta autorska, 3.09.2026:** po ponownej analizie różnica między GPT-4 z personalizacją a GPT-4 bez personalizacji **nie jest istotna statystycznie** (+48,7%, 95% CI −2,9% do +127,6%, P = 0,07; wcześniej podano P = 0,04 jako istotne). Autorzy utrzymują, że personalizowany GPT-4 wyraźnie przewyższa ludzi, ale przewagi samej personalizacji nad zwykłym GPT-4 nie da się rozstrzygnąć przy tej mocy statystycznej. Poprawiono też literówki (Ã_pre zamiast Ã_post).
- **Kontrowersja:** teraz ma bardzo konkretne źródła: (1) korekta samych autorów z 2026, (2) bliźniacze, znacznie większe badanie (Hackenburg et al., Science 2025, para 1): personalizacja tylko +0,43 pp (sprawdzone w arXiv v1). Narracja „personalizacja doładowuje perswazję AI” jest więc słabsza, niż sugerowały nagłówki z maja 2025. Opis wyszukiwacza uczciwy, ale niekompletny (bez korekty).
- **Retrakcje / korekty / krytyka / replikacje:** korekta autorska 3.09.2026 (patrz wyżej). Brak retrakcji. Zapytania: „"Author Correction" "On the conversational persuasiveness of GPT-4" Nature Human Behaviour 2026” (wyszukiwarka nie znalazła; korektę znalazłem na stronie artykułu), „Salvi GPT-4 debate persuasion Nature Human Behaviour May 2025 expert reaction criticism limitations independent”.
- **Poprawki:**
  1. Tytuł wersji NHB: „On the conversational persuasiveness of GPT-4”; NHB 9(8):1645–1653; 19.05.2025; open access.
  2. N=900.
  3. Dopisać korektę autorską z 3.09.2026 (personalizacja vs zwykły GPT-4: P = 0,07, nieistotne).
- **Dodatkowe znaleziska:** Szkic z Zurychu (para 4) cytuje ten paper; para 1 (Science) przeczy tezie o sile personalizacji; korekta z 2026 domyka „trójkąt”. Jako news dodatkowy: The Decoder (24.03.2024) o preprincie: https://the-decoder.com/a-personalized-chatbot-is-more-likely-to-change-your-mind-than-another-human-study-finds/ (relacja z wersji preprintu: 81,7%).
- **Ocena niezależna:** 4/5 (wyszukiwacz: 3). Recenzowany, otwarty paper z prostym, intuicyjnym eksperymentem; nagłówek newsa upraszcza; świeża korekta autorów z września 2026 i sprzeczny wynik z Science dają gotowy spór o to, czy „personalizacja” to realne zagrożenie. Minusy: news z przeciętnego medium bez głosów zewnętrznych; GPT-4 z 2024 to już stary model. Polecam warunkowo: świetny jako para samodzielna o „rozjeździe nagłówek–wynik”, albo jako uzupełnienie pary 1.
- **Do ręcznego sprawdzenia przez zespół:** komentarze ekspertów z AusSMC/scimex (HTTP 403): https://www.scimex.org/newsfeed/could-chatgpt-be-more-persuasive-than-people
- **Opis po poprawkach:**
  - **Kategoria:** perswazja
  - **News:** „'Fascinating and Terrifying': AI Wins 64% of Online Arguments Compared to Humans”, Liz Ticong, eWeek, 22 maja 2025 (akt. 23.05), https://www.eweek.com/news/ai-debates-persuasion/ , paywall: nie. Nazywa czasopismo, podaje 900 uczestników, 64% i 81%, cytuje współautora Francesco Salviego; w treści zaznacza, że 64,4% dotyczy debat z personalizacją i „wyraźnym wynikiem”, ale nagłówek robi z tego ogólne „AI wygrywa 64% kłótni”. Brak głosów zewnętrznych.
  - **Paper:** „On the conversational persuasiveness of GPT-4”, Francesco Salvi, Manoel Horta Ribeiro, Riccardo Gallotti, Robert West, *Nature Human Behaviour* 9(8), 1645–1653, 19.05.2025, DOI 10.1038/s41562-025-02194-6, https://www.nature.com/articles/s41562-025-02194-6 , open access: tak (preprint: arXiv:2403.14380). Prerejestrowane RCT 2×2×3, N=900: krótkie debaty z człowiekiem lub GPT-4, z dostępem lub bez do danych socjodemograficznych rozmówcy. W parach, gdzie jedna strona była bardziej przekonująca, GPT-4 z personalizacją wygrywał w 64,4% (81,2% wyższe szanse wzrostu zgody). Korekta autorska z 3.09.2026: przewaga personalizowanego GPT-4 nad zwykłym GPT-4 nieistotna (P = 0,07).
  - **Trzecie źródło:** korekta autorska, Nature Human Behaviour, 3.09.2026, https://www.nature.com/articles/s41562-026-02588-0 ; Hackenburg et al., Science 2025 (preprint https://arxiv.org/abs/2507.13919 ): personalizacja tylko +0,43 pp w próbie 76 977 osób.
  - **Dlaczego fajne:** prosty, intuicyjny eksperyment („czy przegrałbyś debatę z ChatGPT, gdyby znał twój wiek i poglądy?”); nagłówek to gotowy przykład uproszczenia; autorzy sami skorygowali kluczowy wniosek.
  - **Kontrowersja / rozjazd:** „64%” tylko w jednym warunku i tylko w parach z rozstrzygnięciem; sztuczne warunki (krótkie debaty z przypisanym stanowiskiem); korekta z 2026 i sprzeczny wynik z dużego badania w Science.
  - **Trudność techniczna:** niska–średnia (projekt 2×2×3, iloraz szans, regresja porządkowa, moc statystyczna i różnica „istotne vs nieistotne”).
  - **Pytanie do dyskusji:** Czy powinniśmy mieć prawo wiedzieć, że rozmawiamy z AI, i zakazać AI dostępu do naszych danych w rozmowach o polityce, skoro dowody na siłę personalizacji są słabsze, niż mówiły nagłówki?
  - **Weryfikacja:** ⚠️ (poprawki metadanych, dopisana korekta z 2026), pewność wysoka.

### 9. AI zwiększa wpływ pojedynczych naukowców, ale zawęża naukę (Nature, styczeń 2026): ⚠️ poprawione (pewność: wysoka co do papera, średnia co do newsa)
Uwaga: wyszukiwacz nie znalazł porządnego anglojęzycznego newsa (limit wyszukiwań). Znalazłem otwarty artykuł NPR.
- **Sprawdzone linki:**
  - HPCwire (oba linki z pliku oraz wariant aiwire): HTTP 403 (także u mnie); treści nie znam.
  - 36Kr (15.01.2026): działa; po angielsku (przedruk z Quantum Bit), promocyjny, bez krytyki, kończy się reklamą systemu autorów (OmniScientist). Nie nadaje się jako news.
  - Nature (https://www.nature.com/articles/s41586-025-09922-y): działa po 2 przekierowaniach; paywall; metadane zgodne.
  - arXiv 2412.07727 (abs v4 i HTML v4): działa.
  - arXiv 2601.13187v1: działa.
  - Blog Quintarellego: działa; po włosku; to raczej streszczenie z ironicznym tytułem niż merytoryczna krytyka.
  - Dodatkowo otwarte: **NPR, Katia Riddle, 17.02.2026, „AI is helping individual scientists, study suggests — but not science”**, przedruk stacji członkowskiej KVPR: https://www.kvpr.org/2026-02-17/ai-is-helping-individual-scientists-study-suggests-but-not-science ; ScienceNews.dk (Eliza Brown, 26.03.2026): https://www.sciencenews.dk/en/using-ai-gives-researchers-a-career-boost-while-quietly-reshaping-science-itself ; komunikat UChicago DSI (14.01.2026).
- **News a paper:** NPR opisuje badanie w Nature prowadzone przez Jamesa Evansa (University of Chicago), które przeanalizowało miliony prac; podaje kurczenie się tematów o prawie 5%. Tytułu papera nie przytacza, ale opis jest jednoznaczny. ScienceNews.dk podaje tytuł papera wprost.
- **Fakty:**
  - Tytuł, autorzy, Nature 649, 1237–1243, 14.01.2026, DOI 10.1038/s41586-025-09922-y, paywall → zgodne; preprint open access → zgodne (v1 10.12.2024 … v4 29.11.2025).
  - 41,3 mln prac (dokładnie 41 298 433, OpenAlex, 1980–2025); BERT, F1 = 0,875 → zgodne.
  - 3,02× prac, 4,84× cytowań, liderzy 1,37 roku wcześniej, −4,63% „obszaru” tematów, −22% interakcji → zgodne (komunikat UChicago zaokrągla do 4,85× i 1,4 roku).
  - **Teza wyszukiwacza, że „AI” to głównie klasyczne ML sprzed ChatGPT → potwierdzona i doprecyzowana:** paper dzieli dane na epoki: tradycyjne ML (1980–2014), deep learning (2015–2022) i generatywna AI (2023–); dla epoki LLM autorzy mówią tylko o „wstępnej zgodności” z wcześniejszymi okresami.
  - Przyczynowość: autorzy piszą, że nie mogą w pełni zidentyfikować związku przyczynowego; częściowo kontrolują selekcję dopasowaniem naukowców o podobnej pozycji na starcie kariery → zgodne z opisem wyszukiwacza.
  - News & Views: Veda C. Storey, „AI tools boost individual scientists but could limit research as a whole”, 14.01.2026 → tytuł zgodny (strona Nature); treści nie czytałem (paywall).
  - Kusumegi et al., „Scientific production in the era of large language models”, Science 390(6779), 18.12.2025: 2,1 mln preprintów (i 28 tys. recenzji), +23,7% do +89,3%, „językowo złożone, ale merytorycznie słabe” → zgodne (arXiv 2601.13187v1).
- **Kontrowersja:** NPR cytuje niezależnego krytyka: Steven Salzberg (Johns Hopkins) uważa, że narzędzia AI (np. AlphaGenome) często dają więcej pracy niż pożytku, i ostrzega przed nauką napędzaną narzędziem („when you have a hammer…”); NPR wprost zaznacza, że badanie obserwacyjne nie dowodzi przyczynowości. Spór o interpretację (korelacja, definicja „AI”) jest realny, ale opublikowanej krytyki naukowej nie znalazłem. Blog Quintarellego nie jest krytyką metodologiczną.
- **Retrakcje / korekty / krytyka / replikacje:** brak korekt na stronie Nature. Zapytania: „"Artificial intelligence tools expand scientists' impact but contract science's focus" news”, „Hao Xu Li Evans Nature 2026 AI contract science focus critique methodology…”, „Nature editorial 2026 AI narrowing science focus…”. Jeden blog (pebblous.ai) twierdzi, że dwa miesiące później redakcja Nature wezwała do zmiany metryk oceny; nie potwierdziłem tego (wyniki wskazują na edytorial Nature z 25.03.2026 o „AI scientists”, który może dotyczyć innego papera); niepewne.
- **Poprawki:**
  1. News: zamiast HPCwire (403) i 36Kr (promocyjny) proponuję NPR (Katia Riddle, 17.02.2026, przedruk KVPR) z niezależnym krytykiem.
  2. Doprecyzowanie epok AI w danych (1980–2025; LLM tylko od 2023, wyniki wstępne).
  3. Blog Quintarellego usunąć jako „krytykę” (to streszczenie po włosku).
- **Dodatkowe znaleziska:** Kusumegi et al. (Science, grudzień 2025) to mocny, osobny paper o LLM-ach w pisaniu prac (dotyczy także studentów); jeśli orchestrator szuka tematu „zalew tekstów AI w nauce”, warto poszukać do niego osobnego newsa (np. Cornell Chronicle; niesprawdzone).
- **Ocena niezależna:** 4/5 (wyszukiwacz: 3). Bardzo dobry paper w Nature z czytelnym paradoksem „dobre dla mnie, złe dla nauki”; teraz z otwartym newsem NPR i niezależnym krytykiem. Minusy: paywall papera (preprint otwarty), brak opublikowanej krytyki naukowej, „AI” w danych to głównie ML sprzed ChatGPT (co jednak jest dobrym punktem dla roli 1). Polecam warunkowo do piętnastki.
- **Do ręcznego sprawdzenia przez zespół:** HPCwire (403): https://www.hpcwire.com/2026/01/16/ai-for-science-study-good-for-the-goose-but-what-about-the-gander/ ; News & Views Storey (paywall Nature); czy edytorial Nature z 2026 rzeczywiście odnosi się do tego papera.
- **Opis po poprawkach:**
  - **Kategoria:** AI w nauce
  - **News:** „AI is helping individual scientists, study suggests — but not science”, Katia Riddle, NPR, 17 lutego 2026, przedruk KVPR: https://www.kvpr.org/2026-02-17/ai-is-helping-individual-scientists-study-suggests-but-not-science , paywall: nie. Opisuje badanie Jamesa Evansa (więcej publikacji i cytowań dla korzystających z AI, ale prawie 5% węższy zakres tematów), cytuje krytyka Stevena Salzberga (Johns Hopkins) i zaznacza, że badanie nie dowodzi przyczynowości.
  - **Paper:** „Artificial intelligence tools expand scientists' impact but contract science's focus”, Qianyue Hao, Fengli Xu, Yong Li (Tsinghua), James Evans (University of Chicago), *Nature* 649, 1237–1243, 14.01.2026, DOI 10.1038/s41586-025-09922-y, https://www.nature.com/articles/s41586-025-09922-y , open access: nie (preprint: https://arxiv.org/abs/2412.07727 ). Analiza 41,3 mln prac z nauk przyrodniczych (OpenAlex, 1980–2025); prace „wspomagane AI” wykrywane modelem BERT (F1 = 0,875). Korzystający z AI publikują 3,02× więcej, mają 4,84× więcej cytowań, zostają liderami 1,37 roku wcześniej; zbiorczo AI zawęża obszar tematów o 4,63% i zmniejsza interakcje między naukowcami o 22%.
  - **Trzecie źródło:** News & Views w Nature, Veda C. Storey, „AI tools boost individual scientists but could limit research as a whole”, 14.01.2026 (paywall, nieczytany); uzupełniająco Kusumegi et al., Science 390(6779), 2025, preprint https://arxiv.org/abs/2601.13187v1 (LLM-y zwiększają produkcję o 23,7–89,3%, ale rośnie liczba prac „złożonych językowo, a słabych merytorycznie”).
  - **Dlaczego fajne:** paradoks „dobre dla mnie, złe dla nauki” łatwo odnieść do studentów (oceny, publikacje vs różnorodność wiedzy).
  - **Kontrowersja / rozjazd:** „AI” w danych to głównie klasyczne ML i deep learning sprzed ChatGPT, a media czytają to jako efekt chatbotów; korelacja, nie przyczynowość; klasyfikator też się myli.
  - **Trudność techniczna:** średnia–wysoka (klasyfikacja tekstu BERT-em, embeddingi do mierzenia „obszaru wiedzy”, sieci cytowań, dopasowanie).
  - **Pytanie do dyskusji:** Jeśli AI sprawia, że każdy pojedynczy naukowiec (i student) wygrywa, ale nauka jako całość traci różnorodność, kto powinien to korygować: uczelnie, grantodawcy, czasopisma?
  - **Weryfikacja:** ⚠️ (zmiana newsa), pewność wysoka co do papera, średnia co do newsa.

## Lista do ręcznego sprawdzenia
- **Para 1:** Nature, Lin et al. (https://www.nature.com/articles/s41586-025-09771-9 , paywall): liczba dla zwolenników Harris (2,3 pkt wg MIT TR i PAP czy 1,51 pkt wg Cornell Chronicle) w Fig. 1; liczebność próby w Massachusetts.
- **Para 4:** 404 Media (https://404media.co/researchers-secretly-ran-a-massive-unauthorized-ai-persuasion-experiment-on-reddit-users , częściowy paywall): pełny tekst, czy omawia wyniki szkicu.
- **Para 5:** The Verge (https://www.theverge.com/report/763080/google-ai-gemini-water-energy-emissions-study , domena zablokowana dla narzędzia): tytuł, data, dokładne cytaty Rena i de Vries-Gao. Washington Post, 18.09.2024 (https://www.washingtonpost.com/technology/2024/09/18/energy-ai-use-electricity-water-data-centers/ , 403): czy „butelka wody na 100-wyrazowego maila” pochodzi z analizy z zespołem Rena i jakie były założenia.
- **Para 6:** 404 Media (https://www.404media.co/a-researcher-made-an-ai-that-completely-breaks-the-online-surveys-scientists-rely-on/): czy wymaga rejestracji, czy są głosy zewnętrzne. Listy w PNAS 123(8): e2535585123 (Van der Stigchel i in., Utrecht) i e2537420123 (Westwood i Frederick), open access, ale pnas.org blokuje narzędzie: przeczytać treść.
- **Para 7:** oryginały WSJ (paywall): https://www.wsj.com/economy/will-ai-help-hurt-workers-income-productivity-5928a389 (wczesny, entuzjastyczny tekst) i https://www.wsj.com/tech/ai/mit-says-it-no-longer-stands-behind-students-ai-research-paper-11434092 .
- **Para 8:** AusSMC/scimex (https://www.scimex.org/newsfeed/could-chatgpt-be-more-persuasive-than-people , HTTP 403): komentarze niezależnych ekspertów.
- **Para 9:** HPCwire (https://www.hpcwire.com/2026/01/16/ai-for-science-study-good-for-the-goose-but-what-about-the-gander/ , HTTP 403): czy nazywa paper i ma krytykę; News & Views Storey (paywall Nature); czy edytorial Nature z 2026 dotyczy tego papera.
