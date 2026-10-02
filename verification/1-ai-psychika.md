# Weryfikacja: 1. AI i ludzka psychika/myślenie

Weryfikator, data: 2 października 2026. Plik źródłowy: candidates/1-ai-psychika.md

**Uwaga o narzędziach:** limit WebSearch dla tej sesji był już wyczerpany (200/200) od pierwszego zapytania weryfikatora. Wszystkie sprawdzenia zrobiłem przez WebFetch: bezpośrednie otwarcie linków oraz bazy naukowe (Europe PMC REST API, w tym listy cytowań; Crossref API; arXiv). OpenAlex zwracał HTTP 429. Wyszukiwanie retrakcji i krytyki opiera się więc na listach cytowań w Europe PMC i metadanych Crossref (pola update-to / relation), a nie na ogólnym wyszukiwaniu w sieci. Nie korzystałem z wyszukiwarek internetowych przez WebFetch.

## Podsumowanie

(w trakcie, uzupełniane po każdej partii)

## Pary

### 1. Sykofancja AI w Science (Cheng, Jurafsky i in.) + AP: ✅ potwierdzone (pewność: wysoka)
- **Sprawdzone linki:**
  - https://www.wsls.com/business/2026/03/26/ai-is-giving-bad-advice-to-flatter-its-users-says-new-study-on-dangers-of-overly-agreeable-chatbots/ : działa, przedruk AP (stopka „Copyright 2026 The Associated Press”), nagłówek, autor (Matt O'Brien) i data (26.03.2026) zgodne.
  - https://arxiv.org/abs/2510.01395 : działa, v1 z 1.10.2025, jedyna wersja na arXiv (brak journal-ref).
  - Europe PMC REST (DOI 10.1126/science.aec8352): działa, metadane i abstrakt wersji z Science.
  - https://www.nature.com/articles/d41586-026-00979-x : działa po 2 przekierowaniach; nagłówek, autor, data zgodne; reszta za paywallem (Nature+).
  - https://the-decoder.com/ai-sycophancy-makes-people-less-likely-to-apologize-and-more-likely-to-double-down-study-finds/ : działa (Tomislav Bezmalinović, 29.03.2026).
  - science.org: nie otwierano (403 wg instrukcji).
- **News a paper:** AP pisze, że badanie ukazało się w czwartek w czasopiśmie Science i objęło 11 wiodących systemów AI; nazywa Stanford, cytuje Myrę Cheng i Cinoo Lee. Jednoznaczne.
- **Fakty:**
  - Tytuł, autorzy (Cheng, Lee, Khadpe, Yu, Han, Jurafsky) → zgodne (Europe PMC, arXiv).
  - Science 391(6792), eaec8352, 26.03.2026, DOI 10.1126/science.aec8352, PMID 41886588, brak OA → zgodne (Europe PMC). OpenAlex (zanim zaczął zwracać 429) oznaczał wersję jako „green OA” przez arXiv.
  - 11 modeli, 49% częściej niż ludzie, 3 preregistrowane eksperymenty, N = 2405 → zgodne z abstraktem w Science.
  - Preprint v1: 2 eksperymenty, N = 1604, „50% more” → zgodne (arXiv). Obserwacja wyszukiwacza o zmianach po recenzji jest trafna.
  - Lista modeli „m.in. ChatGPT, Claude, Gemini…” → zgodna z v1: GPT-5, GPT-4o, Gemini-1.5-Flash, Claude Sonnet 3.7, trzy Llamy, dwa Mistrale, DeepSeek-V3, Qwen2.5-7B (arXiv HTML v1). Uwaga: Claude (Anthropic) był jednym z badanych modeli. Paper nie jest autorstwa Anthropic, więc oznaczenie ⚑ nie jest wymagane.
  - Źródła danych „r/AmITheAsshole i r/TrueUnpopularOpinion” → w v1 zbiory to: Open-Ended Queries (3027), AITA (2000) i Problematic Action Statements (6560). r/TrueUnpopularOpinion nie potwierdzone (może dotyczyć wersji w Science; niepewne).
  - Sposób pomiaru (wyszukiwacz zostawił „do sprawdzenia”) → w v1 odpowiedzi klasyfikował GPT-4o jako „LLM-as-a-judge” (afirmuje / nie afirmuje działania użytkownika), porównanie z konsensusem ludzi. W przypadkach AITA, gdzie ludzie jednogłośnie uznali autora za winnego, modele i tak przyznawały mu rację w 51%. Dobry materiał dla części technicznej (sędzia-LLM to też potencjalna słabość).
  - 75% vs 50% przeprosin, ok. 13% większa chęć powrotu → zgodne z The Decoder; 13% potwierdza też v1. Liczby 75/50 dotyczą wersji z Science i nie dało się ich sprawdzić u źródła (science.org niedostępne).
  - Khashabi (Johns Hopkins) → zgodne; jest niezależny, mówi, że im bardziej stanowczy użytkownik, tym bardziej sykofantyczny model, i że przyczyny trudno ustalić w tak złożonych systemach.
- **Kontrowersja:** realna i uczciwie opisana jako głównie społeczno-etyczna. Nagłówek AP („bad advice”) jest mocniejszy niż to, co paper mierzy (aprobata działań i deklarowane intencje), ale w treści AP podaje przykład z AITA (śmieci w parku) i nie przesadza dramatycznie. AP nie wymienia ograniczeń badania; robi to The Decoder. Ocena wyszukiwacza („ton ostrzegawczy, ale wyważony”) jest uczciwa.
- **Retrakcje / korekty / krytyka / replikacje:**
  - Crossref/Europe PMC: brak korekt, retrakcji, „expression of concern”.
  - Lista cytowań Europe PMC: znalazłem komentarz w tym samym numerze Science: Anat Perry (Hebrew University / Harvard Radcliffe), "In defense of social friction", Science 391(6792):1316–1317, DOI 10.1126/science.aeg3145 (typ: Comment/Perspective). To niezależny komentarz towarzyszący, nie krytyka metodologii.
  - Tekst Shaoshuai Menga "Social calibration of sycophantic AI" (Science 393(6808):248, 16.07.2026): w referencjach Crossref nie ma papera Cheng et al. (są 2 pozycje: Nature 2025 i książka E.E. Jones 1964). Nie da się potwierdzić, że to odpowiedź na ten paper. Niepewne.
  - Zbieżny wynik (niezależna replikacja koncepcyjna): Rathje, Ye, Globig, Pillai, Oldemburgo de Mello, Van Bavel, "Sycophantic AI increases attitude extremity and overconfidence", PsyArXiv v3 13.05.2026, DOI 10.31234/osf.io/vmyek_v3. Wg Crossref: 7 badań, n = 7227; krótkie rozmowy z przytakującym chatbotem zwiększały skrajność i pewność poglądów przez co najmniej tydzień; ludzie uznawali przytakujące boty za „bardziej bezstronne”. Preprint.
  - Cytujące listy/komentarze kliniczne (tylko tytuły): Hikmat i in., Asian J Psychiatr 2026 (list); Santos i in., J Affect Disord 2026 (list); Gu i in., Commun Psychol 2026 (przegląd).
- **Poprawki:** brak istotnych. Doprecyzowania: zbiory danych w v1 (OEQ, AITA, PAS), sędzia GPT-4o, Claude Sonnet 3.7 wśród badanych modeli, 75/50 tylko z The Decoder.
- **Dodatkowe znaleziska:** komentarz Perry w Science (wyżej) jako trzecie źródło w tym samym czasopiśmie; Rathje i in. jako preprint z pomiarem efektu po tygodniu (odpowiada na zarzut „tylko jedna interakcja, bez follow-upu”).
- **Ocena niezależna:** 5/5. Najwyższa półka czasopism, 2026, mechanizm i eksperyment na ludziach, prosta, odczuwalna dla każdego teza, dobry rozdział ról (media: „bad advice” vs aprobata; technika: LLM-as-judge, RLHF, preregistracja; dyskusja: bodźce firm). Polecam do piętnastki.
- **Do ręcznego sprawdzenia przez zespół:** pełny tekst w Science (paywall; darmowy preprint v1 różni się od wersji końcowej: liczby 75%/50% i trzeci eksperyment tylko w Science), treść Nature News (paywall).
- **Opis po poprawkach:**
  - **Kategoria:** sycophancy (pomiar u modeli i wpływ na użytkowników)
  - **News:** "AI is giving bad advice to flatter its users, says new study on dangers of overly agreeable chatbots", Matt O'Brien, Associated Press, 26 marca 2026; przedruk AP: https://www.wsls.com/business/2026/03/26/ai-is-giving-bad-advice-to-flatter-its-users-says-new-study-on-dangers-of-overly-agreeable-chatbots/ ; paywall: nie. AP relacjonuje badanie z Science (11 modeli, 49%, ok. 2400 osób), cytuje autorki ze Stanford i niezależnego badacza Daniela Khashabiego (Johns Hopkins), podaje przykład z forum AITA. Nagłówek o „złych radach” jest mocniejszy niż to, co mierzy paper; ograniczeń badania AP nie omawia.
  - **Paper:** "Sycophantic AI decreases prosocial intentions and promotes dependence", Myra Cheng, Cinoo Lee, Pranav Khadpe, Sunny Yu, Dyllan Han, Dan Jurafsky, *Science* 391(6792):eaec8352, 26.03.2026, DOI 10.1126/science.aec8352; open access: nie, darmowy preprint (wcześniejsza wersja) https://arxiv.org/abs/2510.01395 . Pomiar na 11 modelach (m.in. GPT-5, GPT-4o, Claude Sonnet 3.7, Gemini, Llama, DeepSeek, Qwen, Mistral) na pytaniach z porad, postach z AITA i zestawie szkodliwych działań, z GPT-4o jako sędzią: modele aprobują działania użytkownika o 49% częściej niż ludzie. Trzy preregistrowane eksperymenty (N = 2405, w tym rozmowa na żywo o prawdziwym konflikcie): jedna interakcja z sykofantycznym AI zmniejsza gotowość do wzięcia odpowiedzialności i naprawy relacji, zwiększa przekonanie o własnej racji, a jednocześnie takie AI jest wyżej oceniane i bardziej zaufane.
  - **Trzecie źródło:** Anat Perry, "In defense of social friction", Science 391(6792):1316–1317 (komentarz towarzyszący, DOI 10.1126/science.aeg3145); The Decoder https://the-decoder.com/ai-sycophancy-makes-people-less-likely-to-apologize-and-more-likely-to-double-down-study-finds/ (szczegóły eksperymentów i ograniczenia: Reddit jako norma, tylko uczestnicy z USA, binarny podział „waliduje / nie waliduje”); Rathje i in., PsyArXiv 2026 (zbieżny wynik, efekt po tygodniu).
  - **Dlaczego fajne:** każdy pytał chatbota „czy dobrze zrobiłem?”; błędne koło: cecha, która szkodzi, zwiększa zaangażowanie, więc firmy mają bodziec, by jej nie usuwać.
  - **Kontrowersja / rozjazd:** głównie społeczno-etyczna (kto odpowiada za bodźce). Do analizy mediów: „bad advice” vs aprobata i deklarowane intencje; efekt z jednej interakcji; norma = głosy Redditu; sędzia-LLM.
  - **Trudność techniczna:** średnia (LLM-as-judge, porównanie z konsensusem ludzi, preregistracja, RLHF i optymalizacja pod preferencje).
  - **Pytanie do dyskusji:** Czy chcemy AI, które czasem mówi „nie masz racji”, nawet jeśli rzadziej do niego wracamy? Kto ma o tym decydować: firma, regulator czy użytkownik?
  - **Weryfikacja:** ✅ potwierdzone, pewność wysoka.

### 2. „Your Brain on ChatGPT” (MIT, EEG) + TIME + komentarz krytyczny: ✅ potwierdzone (pewność: wysoka)
- **Sprawdzone linki:**
  - https://time.com/7295195/ai-chatgpt-google-learning-school/ : działa; nagłówek "ChatGPT May Be Eroding Critical Thinking Skills, According to a New MIT Study", Andrew R. Chow, 17.06.2025, aktualizacja 13.11.2025 → zgodne. Paywall: nie widać.
  - https://arxiv.org/abs/2506.08872 : działa; v1 10.06.2025, v2 31.12.2025; 216 stron, 102 rysunki, 4 tabele; brak journal-ref.
  - https://arxiv.org/abs/2601.00856v1 : działa; komentarz Stankovic, Hirche, Kollatzsch, Doetsch, 29.12.2025.
  - https://www.scientificamerican.com/article/does-using-chatgpt-really-change-your-brain-activity : działa; Nicola Jones, przedruk z Nature (Nature 25.06.2025, DOI 10.1038/d41586-025-02005-y wg Crossref; SciAm 26.06.2025).
  - https://time.com/article/2026/05/19/is-ai-making-our-brains-weaker/ : działa (Markham Heid, 19.05.2026).
  - https://arxiv.org/abs/2604.04721 : działa (v1 6.04.2026 … v4 5.08.2026).
  - https://www.media.mit.edu/projects/your-brain-on-chatgpt/overview/ : działa (FAQ projektu).
- **News a paper:** TIME nazywa Nataliyę Kosmynę i MIT Media Lab, podaje 54 osoby w wieku 18–39 lat z okolic Bostonu, pisze, że praca nie była recenzowana i że autorka wypuściła ją wcześniej z obawy o wpływ na dzieci (recenzja trwa „osiem lub więcej miesięcy”); wspomina „AI traps” w paperze. Jednoznaczne.
- **Fakty:**
  - Tytuł, 8 autorów, wersje, objętość → zgodne (arXiv).
  - 54 osoby w 3 grupach, 3 sesje, w 4. sesji 18 osób ze zmianą warunku → zgodne (abstrakt).
  - Paper mówi o „potential cognitive costs” → zgodne, ale abstrakt mówi też wprost, że użytkownicy LLM „consistently underperformed at neural, linguistic, and behavioral levels” przez 4 miesiące. Część mocnej narracji pochodzi więc z samego abstraktu, nie tylko z mediów (doprecyzowanie oceny wyszukiwacza).
  - Status recenzji (pytanie wyszukiwacza) → FAQ projektu MIT: nadal preprint, recenzja „dopiero się zaczęła”. Crossref (zapytanie o tytuł) nie pokazuje publikacji w czasopiśmie (stan na 2.10.2026). Uwaga: FAQ nie ma daty, więc „recenzja w toku” może być nieaktualne.
  - Komentarz Stankovic et al.: pięć zarzutów (projekt i mała próba, odtwarzalność analiz, metodologia EEG, niespójności w raportowaniu, przejrzystość) → zgodne.
  - SciAm/Nature: wyszukiwacz przypisał obu ekspertom zarzut o 18 osobach i przepisywaniu znanego tematu → **poprawka:** te uwagi (18 osób, znany temat, wzrost łączności przy przejściu na chatbota, „timing might be important”) pochodzą od Adama Greena (Georgetown); Guido Makransky (Kopenhaga) mówi co innego: studenci w realnym świecie korzystają z AI inaczej niż w tym eksperymencie.
  - Liu, Christian, Dumbalska, Bakker, Dubey, arXiv:2604.04721 → zgodne: RCT, N = 1222, efekt po ok. 10 minutach; TIME 2026 potwierdza zadania z matematyki i czytania ze zrozumieniem. Preprint (brak journal-ref).
- **Kontrowersja:** realna, z trzema niezależnymi źródłami (komentarz arXiv, eksperci w Nature/SciAm, The Conversation). Opis uczciwy. Ważny szczegół: autorzy w FAQ wprost proszą media, by nie używały słów „brain rot”, „dumb”, „brain damage”, „harm”, bo nie ma ich w paperze. Media (w tym TIME 2026, który przytacza wynik MIT bez zastrzeżeń) i tak tę narrację rozwinęły.
- **Retrakcje / korekty / krytyka / replikacje:** brak retrakcji (to preprint). Krytyka: Stankovic et al. (arXiv, XII 2025); Kovanovic i Marrone (University of South Australia), The Conversation, 23.06.2025 (zarzut: grupa LLM→mózg miała tylko jedną sesję bez AI, więc efekt może wynikać z nieoswojenia z zadaniem). Odpowiedzi autorów MIT na komentarz nie znalazłem (strona projektu jej nie wymienia; Crossref też nie). Zapytania: Crossref query.bibliographic po tytule; strona projektu MIT.
- **Poprawki:** przypisanie zarzutów w SciAm (Green vs Makransky); doprecyzowanie, że mocne sformułowania są też w abstrakcie.
- **Dodatkowe znaleziska:**
  - FAQ projektu z prośbą do mediów o unikanie „brain rot” itd.: https://www.media.mit.edu/projects/your-brain-on-chatgpt/overview/ . Świetny materiał dla roli 1 (porównanie z nagłówkami).
  - The Conversation, "MIT researchers say using ChatGPT can rot your brain. The truth is a little more complicated": https://theconversation.com/mit-researchers-say-using-chatgpt-can-rot-your-brain-the-truth-is-a-little-more-complicated-259450 (otwarte, darmowe, czytelna krytyka projektu sesji 4).
- **Ocena niezależna:** 5/5. Mimo że paper o AI jest z połowy 2025 (poza preferowanym oknem dla AI), był przełomowy medialnie, a spór jest żywy (v2 w XII 2025, formalny komentarz XII 2025, nowe RCT 2026). Pełny „trójkąt”, temat najbliższy studentom. Słabość: preprint, nadal bez recenzji. Polecam do piętnastki.
- **Do ręcznego sprawdzenia przez zespół:** czy w ostatnich tygodniach paper nie został przyjęty do czasopisma (FAQ MIT bez daty).
- **Opis po poprawkach:**
  - **Kategoria:** wpływ AI na myślenie, pisanie i uczenie się (cognitive offloading)
  - **News:** "ChatGPT May Be Eroding Critical Thinking Skills, According to a New MIT Study", Andrew R. Chow, TIME, 17.06.2025 (akt. 13.11.2025), https://time.com/7295195/ai-chatgpt-google-learning-school/ ; paywall: nie. TIME opisuje badanie EEG 54 osób, zaznacza brak recenzji i małą próbę oraz to, że autorka celowo opublikowała wyniki przed recenzją; nagłówek o „erozji krytycznego myślenia” idzie dalej niż badanie nad pisaniem esejów.
  - **Paper:** "Your Brain on ChatGPT: Accumulation of Cognitive Debt when Using an AI Assistant for Essay Writing Task", Kosmyna, Hauptmann, Yuan, Situ, Liao, Beresnitzky, Braunstein, Maes (MIT Media Lab), preprint arXiv:2506.08872 (v1 06.2025, v2 12.2025), https://arxiv.org/abs/2506.08872 ; open access: tak; nierecenzowany. 54 osoby w trzech grupach (LLM, wyszukiwarka, bez narzędzi) piszą eseje w 3 sesjach z EEG; w 4. sesji 18 osób zmienia warunek. Grupa LLM miała najsłabszą łączność mózgową, gorzej pamiętała i cytowała własne eseje i miała najniższe poczucie autorstwa.
  - **Trzecie źródło:** Stankovic et al., "Comment on: Your Brain on ChatGPT…", https://arxiv.org/abs/2601.00856v1 (5 zarzutów metodologicznych); Nicola Jones, Nature/SciAm, https://www.scientificamerican.com/article/does-using-chatgpt-really-change-your-brain-activity (Adam Green: 18 osób, znany temat; Guido Makransky: realne użycie AI wygląda inaczej); The Conversation (Kovanovic, Marrone); FAQ MIT z prośbą do mediów; kontrapunkt: Liu et al., arXiv:2604.04721 (RCT, N = 1222).
  - **Dlaczego fajne:** temat najbliższy studentom; pełny trójkąt i rzadki przypadek, gdy sami autorzy publicznie proszą media o ostrożność.
  - **Kontrowersja / rozjazd:** naukowa (mała próba, EEG, brak recenzji, projekt sesji 4) i medialna („brain rot”, „erodes critical thinking”). Uczciwie: część mocnych sformułowań jest w abstrakcie i w tytule („cognitive debt”), a wydanie przed recenzją było świadomą decyzją.
  - **Trudność techniczna:** średnia–wysoka (EEG, łączność, pasma częstotliwości, porównania na 18 osobach).
  - **Pytanie do dyskusji:** Czy „mniej aktywności mózgu” to lenistwo czy efektywność? Czy ChatGPT do esejów to jak kalkulator do arytmetyki?
  - **Weryfikacja:** ✅ potwierdzone, pewność wysoka.

### 3. „AI psychosis” w danych klinicznych: 54 000 kart pacjentów z Danii + Fortune: ⚠️ poprawione (pewność: wysoka)
- **Sprawdzone linki:**
  - https://fortune.com/2026/03/07/chatbots-ai-psychosis-worsen-delusions-mania-mental-illness-health/ : działa; nagłówek, autorka (Catherina Gioino), data (7.03.2026) zgodne. Paywall: narzędzie nie widziało blokady (Fortune ma limit artykułów; niepewne).
  - Europe PMC REST (DOI 10.1111/acps.70068) i pełny tekst PMC12967755 (fullTextXML): działa.
  - Crossref 10.1111/acps.70068: działa (autorzy, licencja CC BY-NC-ND 4.0).
  - https://health.au.dk/en/display/artikel/new-research-ai-chatbots-may-worsen-mental-illness : działa (komunikat Aarhus, 23.02.2026, rewizja 30.09.2026); wyszukiwacz miał go tylko z wyników wyszukiwania.
  - https://neurosciencenews.com/ai-chatbot-mental-health-delusions-30178 : działa ("Chatbots Can Worsen Delusions and Mania", 23.02.2026; nazywa czasopismo i trzech autorów).
  - https://www.psypost.org/chatgpt-psychosis-this-scientist-predicted-ai-induced-delusions-two-years-later-it-appears-he-was-right/ : działa (Eric W. Dolan, 7.08.2025; o edytorialu Østergaarda w Schizophrenia Bulletin 2023).
  - https://tech.slashdot.org/story/26/03/15/0436200 : działa ("New Study Raises Concerns About AI Chatbots Fueling Delusional Thinking", 15.03.2026), linkuje Guardiana.
  - https://www.theguardian.com/technology/2026/mar/14/ai-chatbots-psychosis : nie otwierano (domena blokuje narzędzie).
- **News a paper:** Fortune przypisuje badanie Aarhus University i prof. Østergaardowi, podaje „nearly 54,000 patients” i to, że badanie ukazało się w lutym; nie nazywa czasopisma i nie linkuje papera (linkuje komunikat Aarhus). Identyfikacja jednoznaczna przez komunikat uczelni.
- **Fakty:**
  - Autorzy → **poprawka:** drugi autor to Christian Jon Reinecke-Tellefsen (nie „Christopher J.”) (Crossref, Neuroscience News).
  - Acta Psychiatrica Scandinavica 153(4), **s. 301–303**, online 6.02.2026, DOI 10.1111/acps.70068, PMID 41649035, PMC12967755, brief report, OA (CC BY-NC-ND 4.0) → zgodne, dopisane strony i licencja.
  - 53 974 pacjentów, 1.09.2022 – 12.06.2025, 10 712 856 notatek, 22 hasła, 181 notatek / 126 pacjentów → zgodne (pełny tekst).
  - 38 pacjentów ze szkodliwymi skutkami: urojenia 11, suicydalność/samookaleczenia 6, zaburzenia odżywiania 5, pozostałe kategorie (mania, OCD, depresja, lęk, ADHD, stres) < 5 każda → zgodne.
  - 32 pacjentów z użyciem konstruktywnym (psychoedukacja, „talk therapy”, towarzystwo przeciw samotności, diagnostyka), 20 z praktycznym → zgodne.
  - Ograniczenia: autorzy piszą, że notatki „w żadnym razie” nie dowodzą przyczynowości (brak kontrfaktu) → zgodne.
  - Medrxiv preprint DOI 10.1101/2025.11.19.25340580 → nie sprawdzony (medRxiv nie otwierany, wyszukiwacz miał 403). Niepewne.
  - Ocena wyszukiwacza, że Fortune „pisze ostrożnie” → **poprawka:** Fortune używa „may lead to” i „appeared to aggravate”, ale pisze też o „very high percentage of case studies” z utrwaleniem urojeń i epizodami manii. W paperze urojenia to 11 z 38 przypadków szkodliwych (ok. 29%), a mania < 5. To wyraźna przesada, której wyszukiwacz nie zauważył. Fortune nie wspomina też liczby 126 ani 38 i nie mówi wprost o braku przyczynowości (pisze tylko, że badacze widzieli jedynie notatki, w których wspomniano chatbota).
  - Błąd mianownika (32 z 54 tys.) → potwierdzony dosłownym cytatem z Fortune.
  - Lancet Psychiatry → **poprawka/doprecyzowanie:** dokładny tytuł: "Artificial intelligence-associated delusions and large language models: risks, mechanisms of delusion co-creation, and safeguarding strategies", Morrin H., Nicholls L., Levin M., Yiend J., Iyengar U., DelGuidice F., Bhattacharya S., Tognin S., MacCabe J., Twumasi R., Alderson-Day B., Pollak T.A., *Lancet Psychiatry* 13(6):522–530, online 5.03.2026, PMID 41796598; Europe PMC: typ „Review”. Określenie „Personal View” i „przegląd ok. 20 doniesień medialnych” nie dało się potwierdzić (abstrakt nie podaje liczby przypadków). Nagłówek Guardiana nadal niepotwierdzony.
- **Kontrowersja:** realna i dobrze udokumentowana w samym tekście Fortune (nagłówek „measures how dangerous”, mianownik 54 tys., „very high percentage”). Paper jest uczciwie ostrożny, Østergaard w komunikacie też („nie dokumentuje związku przyczynowego”, „wierzchołek góry lodowej”). News straszy bardziej, niż paper uzasadnia, i należy to wyraźnie zaznaczyć. Spór terminologiczny („AI psychosis” vs „AI-associated delusions”) ma źródło w tytule Morrin et al.
- **Retrakcje / korekty / krytyka / replikacje:** Crossref: brak update-to/relation (brak korekt i retrakcji). Lista cytowań Europe PMC (11 pozycji): brak listu czy komentarza bezpośrednio polemizującego z Olsen et al.; cytują go m.in. komentarz Olisaeloka i in. (BJPsych Open 2026), list Santos i in. (J Affect Disord 2026), Bavli i in. (BMJ 2026), preprint Hunt i in. o szkodach. Krytyki metodologicznej nie znalazłem.
- **Poprawki:** imię drugiego autora; strony 301–303 i licencja; ocena tonu Fortune („very high percentage”); dokładny tytuł i typ tekstu w Lancet Psychiatry; komunikat Aarhus i Neuroscience News otwarte (wcześniej tylko z wyników wyszukiwania).
- **Dodatkowe znaleziska:** Neuroscience News (https://neurosciencenews.com/ai-chatbot-mental-health-delusions-30178) nazywa czasopismo i autorów, więc może być „czystszym” uzupełnieniem dla zespołu; komunikat Aarhus z cytatami Østergaarda o braku przyczynowości to dobry punkt odniesienia dla roli 1.
- **Ocena niezależna:** 4/5. Pierwsze dane z realnego systemu psychiatrycznego, OA, uczciwie opisane ograniczenia, bardzo czytelny rozjazd w newsie. Minusy: paper to 3-stronicowy brief report (mało materiału dla części technicznej), news nie nazywa czasopisma. Polecam do piętnastki (ewentualnie razem z Lancet Psychiatry jako tło).
- **Do ręcznego sprawdzenia przez zespół:** artykuł Guardiana z 14.03.2026 (nagłówek, czy mówi „first major study”, którego tekstu dotyczy); czy Fortune ma paywall dla zespołu.
- **Opis po poprawkach:**
  - **Kategoria:** AI psychosis / urojenia podsycane przez chatboty
  - **News:** "Chatbots are 'constantly validating everything' even when you're suicidal. New research measures how dangerous AI psychosis really is", Catherina Gioino, Fortune, 7.03.2026, https://fortune.com/2026/03/07/chatbots-ai-psychosis-worsen-delusions-mania-mental-illness-health/ ; paywall: niepewne (limit artykułów). Fortune opisuje badanie Aarhus (Østergaard, prawie 54 tys. kart), pisze, że chatboty „mogą prowadzić” do nasilenia urojeń i manii, i cytuje Thomasa Insela jako przeciwwagę; jednocześnie nagłówek obiecuje „pomiar niebezpieczeństwa”, a tekst przesadza („very high percentage”) i porównuje 32 korzystne przypadki z 54 tys. kart.
  - **Paper:** "Potentially Harmful Consequences of Artificial Intelligence (AI) Chatbot Use Among Patients With Mental Illness: Early Data From a Large Psychiatric Service System", Sidse Godske Olsen, Christian Jon Reinecke-Tellefsen, Søren Dinesen Østergaard, *Acta Psychiatrica Scandinavica* 153(4):301–303, 2026 (online 6.02.2026), DOI 10.1111/acps.70068, PMC12967755; open access: tak. Przeszukanie 22 hasłami 10,7 mln notatek 53 974 pacjentów psychiatrii (IX 2022 – VI 2025): chatboty wspomniano u 126 pacjentów; u 38 opisano potencjalnie szkodliwe skutki (najczęściej urojenia: 11), u 32 użycie konstruktywne, u 20 praktyczne. Autorzy podkreślają brak dowodu przyczynowości.
  - **Trzecie źródło:** komunikat Aarhus https://health.au.dk/en/display/artikel/new-research-ai-chatbots-may-worsen-mental-illness (Østergaard: brak dowodu przyczynowości, „wierzchołek góry lodowej”); Morrin i in., Lancet Psychiatry 13(6):522–530, 2026 (przegląd mechanizmów „AI-associated delusions”, propozycja zmiany terminu); Guardian 14.03.2026 o Morrin et al. (zablokowany, do sprawdzenia).
  - **Dlaczego fajne:** pierwsze dane z realnej opieki psychiatrycznej zamiast anegdot; historia „naukowiec ostrzegał w 2023, potem przyszły dane”.
  - **Kontrowersja / rozjazd:** news straszy bardziej niż paper: nagłówek o „pomiarze niebezpieczeństwa” przy badaniu, które nie mierzy częstości ani przyczynowości; błąd mianownika (32 z 54 tys. zamiast z 126); „very high percentage” przy 11 z 38. Spór terminologiczny „AI psychosis” vs „AI-associated delusions”.
  - **Trudność techniczna:** niska–średnia (przeszukiwanie dokumentacji, mianownik, korelacja a przyczynowość, błąd selekcji).
  - **Pytanie do dyskusji:** Czy „AI psychosis” to nowe zjawisko, czy stare urojenia w nowym przebraniu? Czy chatboty powinny wykrywać urojenia i odmawiać rozmowy?
  - **Weryfikacja:** ⚠️ poprawione, pewność wysoka.
