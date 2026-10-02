# Plan: pary „news + paper” (Research in Context, UCU)

Data startu: 2 października 2026.

## Decyzje

- 7 wyszukiwaczy (Faza 1) i 7 weryfikatorów (Faza 2), po jednym na grupę. Wszyscy to Opus 5.5 z effort xhigh (definicje w `.claude/agents/`).
- Weryfikator danej grupy rusza od razu, gdy skończy jej wyszukiwacz.
- News tylko po angielsku. Paywall oznaczamy, ale nie wykluczamy, bo news czyta tylko zespół, nie sala.
- Media blokujące narzędzie (Guardian, NYT, BBC itd.) są dozwolone. Blokady nie obchodzimy. Taka para dostaje najwyżej ⚠️ i trafia na listę do ręcznego sprawdzenia przez zespół.
- Papery Anthropic są oznaczane, a ich trzecie źródło musi być niezależne od Anthropic.
- Wcześniejsze prezentacje (integracja europejska, rośliny i ekologia) nie przecinają się z naszymi tematami.
- Pliki:
  - `candidates/<grupa>.md` i `verification/<grupa>.md`
  - `RAPORT.md`: 15 par, tabela punktów, rezerwa, lista do ręcznego sprawdzenia

## Grupy

Każdy wyszukiwacz dostaje w prompcie: opis swojej grupy, tropy startowe (niezweryfikowane) i krótką listę tematów innych grup, żeby się nie dublować.

### 1-ai-psychika: AI i ludzka psychika/myślenie
**Zakres:**
- „AI psychosis” i urojenia podsycane przez chatboty
- sycophancy (zarówno pomiar u modeli, jak i wpływ na użytkowników)
- samotność i relacje z chatbotami (companion apps)
- AI jako terapeuta
- wpływ AI na myślenie, pamięć, pisanie i uczenie się (cognitive offloading, edukacja)

**Tropy:**
- MIT „Your Brain on ChatGPT” (EEG, pisanie esejów, 2025) i medialne „ChatGPT ogłupia”
- chatboty a urojenia
- badanie Stanford o chatbotach-terapeutach
- badanie OpenAI/MIT o używaniu ChatGPT i samotności

### 2a-ai-od-srodka: AI od środka
**Zakres:**
- alignment: oszukiwanie, szantaż w scenariuszach testowych, udawanie posłuszeństwa (alignment faking), rozpoznawanie testów, scheming, reward hacking
- interpretability i introspekcja modeli
- świadomość AI i to, czy ludzie w nią wierzą
- możliwości i tempo postępu (benchmarki, test Turinga, spór o „rozumowanie”)

**Tropy:**
- modele szantażujące w scenariuszach testowych
- „alignment faking” (Anthropic i inni)
- GPT-4.5 przechodzi test Turinga (Jones & Bergen, 2025)
- od orkiestratora: Apple „The Illusion of Thinking” (2025) i odpowiedzi na ten paper
- od orkiestratora: nagłówek MIT Tech Review z 2 października 2026, „Don't be fooled—LLMs don't reason” (sprawdzić, czy omawia konkretny paper)

### 2b-ai-spoleczenstwo: AI a społeczeństwo
**Zakres:**
- rynek pracy i produktywność
- perswazja i polityka
- AI w nauce (AI-naukowcy, recenzje, zalew tekstów generowanych przez AI)
- etyka eksperymentów
- ślad środowiskowy AI

**Tropy:**
- METR: doświadczeni programiści wolniejsi z AI, choć przekonani, że szybsi (2025)
- spadek zatrudnienia młodych w zawodach narażonych na AI (Stanford, 2025)
- AI zmniejsza wiarę w teorie spiskowe (Science, 2024)
- nieetyczny eksperyment z botami AI na Reddicie r/changemyview (2025)
- ukryte prompty w paperach dla recenzentów-AI (2025)
- od orkiestratora: szacunki zużycia wody i energii przez AI i spór o te liczby

### 3a-umysl-mozg: Umysł i mózg
**Zakres:**
- wewnętrzny głos, afantazja
- interfejsy mózg-komputer i dekodowanie myśli
- stymulacja mózgu
- nauka o świadomości
- świadomość zwierząt
- organoidy mózgowe

**Tropy:**
- anendophasia (Nedergaard & Lupyan, 2024)
- implant dekodujący wewnętrzną mowę (2025)
- list nazywający IIT pseudonauką; „adversarial collaboration” teorii świadomości w Nature (2025)
- od orkiestratora: nagłówek MIT Tech Review z 2 października 2026, „An AI 'mind-reading' tool can reconstruct what you're looking at from a brain scan” (sprawdzić)

### 3b-geny-cialo: Geny i ciało
**Zakres:**
- edycja genów, selekcja zarodków
- mikroplastik w organizmie
- de-extinction
- syntetyczna biologia i ryzyko (mirror life)
- inne fascynujące tematy biomedyczne niezwiązane z psychiką

**Tropy:**
- mikroplastik w ludzkim mózgu (Nature Medicine, 2025) i krytyka metodologii
- spersonalizowana terapia CRISPR u niemowlęcia (NEJM, 2025)
- selekcja zarodków pod IQ
- od orkiestratora: „dire wolf” firmy Colossal (2025) i spór naukowców
- od orkiestratora: ostrzeżenie przed „mirror life” (Science, 2024)

### 4-psychika-substancje: Psychika i substancje
**Zakres:**
- choroby psychiczne i spory diagnostyczne
- trauma, w tym jej dziedziczenie
- psychodeliki i narkotyki
- ciemne strony medytacji
- placebo
- leki psychiatryczne

**Tropy:**
- przegląd Moncrieff o serotoninowej teorii depresji (2022)
- paracetamol w ciąży a autyzm (2025, nauka i polityka)
- epigenetyczne dziedziczenie traumy
- odrzucenie MDMA na PTSD przez FDA (2024)
- mikrodawkowanie a placebo
- niepożądane skutki medytacji, jawne placebo
- od orkiestratora: nagłówek Nature News z 2 października 2026, „Prozac use for childhood depression skewed by single flawed medical trial” (sprawdzić)

### 5-spoleczenstwo-metanauka: Społeczeństwo, metanauka, wildcard
**Zakres:**
- smartfony i media społecznościowe a nastolatki
- samotność społeczna (nie chatboty)
- kryzys replikacji, oszustwa naukowe, retrakcje
- wszystko fascynujące spoza pozostałych grup

**Tropy:**
- smartfony a psychika nastolatków (Haidt kontra krytycy; trzeba zakotwiczyć w jednym konkretnym paperze)
- afera z badaniami o amyloidzie i Alzheimerze
- od orkiestratora: sprawy Gino i Ariely'ego (oszustwa w badaniach o nieuczciwości, następstwa w latach 2025–2026)
- od orkiestratora: nagłówek PsyPost z 2 października 2026 o długofalowych skutkach samotności w dzieciństwie (sprawdzić)

## Faza 3 (orkiestrator)

1. Scalenie wyników, naniesienie poprawek, usunięcie odrzuconych par i duplikatów.
2. Punktacja 1–5 według kryteriów i wybór 15 par z dbałością o różnorodność.
3. Samodzielne sprawdzenie na wyrywki co najmniej 3 par z piętnastki.
4. Zapis `RAPORT.md`, commit i push na branch `claude/news-paper-presentation-pairs-xe0p6j`.
