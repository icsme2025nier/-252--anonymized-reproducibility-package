# Transcript Executive Summary: Michael Hakl (Research-Developer)
**Date**: May 18, 2025  
**Duration**: ~150 minutes  
**Context**: Phenomenologically-informed interview about AI assistant experiences in software development

## Opening & Context Setting

- Optoelectronic engineer transitioning from fundamental research to industry [5:00]
- Specializes in image processing and machine vision systems [5:30-6:00]
- Working on infrared camera algorithms for people counting in enclosed spaces [6:00-7:00]
- 3-5 years experience with Python and Halcon; some background in C [12:44-13:00]
- Team structure: algorithm designers, embedded engineers, application engineers, coordinator [9:06-10:38]
- Uses AI assistants (mainly ChatGPT) for refactoring and avoiding "reinventing standard functions" [15:17-17:09]
- No experience with fully autonomous AI agents yet [17:09]

## Key Experiences with AI Assistants

### Experience 1: Linear Assignment Problem Implementation (Negative)
**Context**: Needed to implement object tracking algorithm in Halcon scripting language [17:32-18:30]

**Process**:
- Asked ChatGPT to refactor existing implementations into Halcon [18:30-19:30]
- Initial response seemed promising: "skoro to fungovalo" (it almost worked) [19:30]
- Spent 4-5 days total on implementation [23:13]

**Breakdown**:
> "občas ten výstup bez těch jednotlivejch pod funkcí byl trošičku zvláštní a musel jsem ho zrevidovat, protože tam byly chyby, který nebyly úplně evidentní" [19:30-19:57]

ChatGPT's limitations:
> "z nějakých 70% těch bylo ale z 30% a Čechy PT vlastně vůbec nevěděl... nebyl schopnej mi odpovědět" [20:10-20:30]

**Emotional Journey**:
- Initial: "měl jsem samozřejmě velký očekávání" [23:13]
- Frustration: "je to takový únavný... ztrácíš pomalu jakoby nadšení a trpělivost" [24:40-25:00]
- Decision point: "stojím před problémem. Buď tady budu něco zkoušet s chatem GPT... nebo si ty nasednu sám" [25:52-26:18]

**Outcome**: Abandoned ChatGPT, implemented manually over 3 days [26:18-26:48]

### Experience 2: Halcon to Python Function Conversion (Positive)
**Context**: Converting proprietary Halcon functions to Python/NumPy [39:49-41:44]

**Process**:
- Asked ChatGPT to convert high-level Halcon operators (convolution, Laplacian-Gaussian) to low-level Python [40:30-41:00]
- Single paragraph request → functional output [58:24-58:30]

**Result**:
> "tam jsem docela slavil úspěch. To se mi líbilo" [41:44]

**Limitation**: ChatGPT didn't provide step-by-step execution traces for testing [42:00-43:20]

### Experience 3: Convex Hull Algorithm (Learning Experience)
**Context**: Needed to understand and implement convex hull algorithm [51:12-52:00]

**Process**:
- Asked for explanation and refactoring of Graham's algorithm [51:30-52:00]
- ChatGPT provided clear, pedagogical explanation [52:30-52:51]

**Emotional Response**:
> "byl jsem pyšnej jako na sebe... jsem se vlastně naučil er ten algoritmus skrze toho tu jeho refaktorizace" [52:30-52:51]

**Unexpected benefit**:
> "fungovalo na 1 pokus bez toho, aniž bych tomu jakoby rozuměl do hloubky" [52:53-53:00]

## Core Themes

### 1. AI as Outsourced Labor, Not Magic
> "Já to ani tak neberu jako že by se zvýšil jakoby svoje svoji výkonnost... já to spíš beru vyloženě jako nádeníka" [1:21:12-1:21:30]

Describes ChatGPT as:
> "takovej interaktivnější stack overflow pro mě" [1:21:30]

### 2. Skeptical Realism About AI Capabilities
On AI-generated solutions:
> "navrhuje dobrý řešení, ale není úplně vědom si, proč to tak dělá" [20:30-20:43]

On verification needs:
> "úplně jako copy paste bezmyšlenkovitě nepoužívám to ne, to by nedopadlo dobře" [1:41:40-1:41:44]

### 3. Career Progression Alignment
Current identity:
> "Já pocházím z toho z té generace, kdy před chatem GPT, kde všichni programátoři museli vlastně spoléhat jenom na svojí vlastní skill" [2:10:50-2:11:00]

Future vision:
> "přesunu se do toho koncepční vrstvy a budu to víceméně operovat jenom v tý koncepční koordinační vrstvě... chceš jakoby stoupat v tý architekt ující vrstvu" [2:14:50-2:15:28]

### 4. Tool Integration vs. Hype Resistance
> "Pokud bude smysluplná integrace, která prostě bude zvyšovat tu účinnost... tak určitě já jsem otevřenej" [2:12:16-2:12:30]

But warns:
> "často se může stát, že to bude prostě nad používá... to povede naopak k negativním produktivitě" [2:12:43-2:12:49]

### 5. Increased Risk Appetite Through AI Support
> "Teďka můžu bejt trošičku, víc sebejistý a můžu se můžu naskočit na projekty, který jsou více výzva" [1:12:20-1:12:40]

On team efficiency:
> "snížit počet lidí v projektu, který na to musi pracovat... komplexita toho projektu může bejt vyšší" [1:14:00-1:14:21]

## Professional Identity Impact

### Research-Developer to Systems Architect
> "teďka jsem třeba řekněme senior a systém a developer a potom budou třeba architekt a nebo stav inženýr" [2:15:50-2:16:03]

### Maintained Independence
> "Beru to spíš jako nice to have než must have... nebude mě to úplně invalidovna" [2:11:15-2:11:37]

### Adaptation as Natural Evolution
> "ta tvoje ten tvůj background se vyvíjí s časem AS těma technologiema" [2:14:07-2:14:20]

### Competitive Awareness
> "Ten, kdo to neudělá, tak ten prohraje ve finále... tam bude vždycky někdo jinej, kdo to zakomponuje" [2:12:30-2:12:43]

## Notable Insights

### On Code Ownership
When asked about code authorship:
> "Nepotřebuju, nepotřebuju tam, tvrdí... své prvenství... oni to taky používaj, takže oni ví, že to ušetří práci" [1:00:59-1:01:07]

### On Junior vs. Senior Dynamics
> "Junior zvládne líp než prostě super senior, protože bude mít vedle sebe a super asistenta" [2:18:18-2:18:25]

### On Teaching and AI
Advocates for strong fundamentals:
> "mít určitě silnej background v tý věci... dobrej background dobrej základ dobrej kořen... nemůže bejt nikdy jakoby nazmar" [2:29:12-2:29:34]

### On Management Misunderstandings
> "jsou lidi, který nemají zas takovou takovej technickej přehled... pro tyhlety lidi a já je trošičku buzzword" [1:46:30-1:47:00]

Management expectations vs. reality:
> "oni chtějí oni žijou prostě v nějaký trošičku detašovaný od reality" [2:02:31-2:02:40]

## Key Narrative Arc
From fundamental researcher → to pragmatic tool user → maintaining critical distance while embracing productivity gains → envisioning natural career progression to systems architecture enhanced (not replaced) by AI.

## Post-Script: Researcher's Live Notes

### Pre-Interview Context
- Optoelectronic engineer from academic/research background
- Transitioning from fundamental research to industry
- Specializes in machine vision, infrared sensors, embedded systems
- Works on algorithms for microcontrollers with limited resources
- Project phases: 1) Algorithm skeleton (Halcon), 2) Python demonstrator, 3) C implementation
- Role: Architect designing algorithms and system architecture
- 3-5 years Python/Halcon experience, some C background

### Key Experiences

**Experience 1 - Linear Assignment Problem (Negative)**
- Used reasoning mode ~2 months ago, ChatGPT failed
- Object tracking between camera frames in Halcon
- 4-5 days total work, major setback with milestones
- Process: Primed ChatGPT → explained problem → specified language/IO
- Phase 1: High expectations, relief when solution appeared, felt like critical point became banal
- Phase 2: Frustration with error corrections, ChatGPT kept reformulating same errors
- Phase 3: Depression about workload → pride in old-fashion solution → increased confidence
- Abandoned ChatGPT, found GitLab implementation, 3 days manual translation
- "Got angry at ChatGPT" - wanted his original style, not internet-frequency variable names

**Experience 2 - Function Conversions (Positive)**
- Halcon proprietary functions → Python/NumPy
- Single paragraph request → functional output
- "Celebrated success"
- Wished for interactive testing with AI showing step-by-step execution

**Experience 3 - Convex Hull Algorithm (Learning)**
- Graham's algorithm implementation
- AI explained clearly, learned algorithm through refactoring
- Worked first try without deep understanding
- 80% expectations met
- Didn't explicitly ask to learn, but code was so clear he understood

### Core Themes from Notes

1. **AI as Labor, Not Magic**: Views AI as "laborer" and "more interactive StackOverflow"
2. **20% Time Savings**: Estimates 20% daily time savings through AI use
3. **Delegation Planning**: Now includes "extra delegation phase" when approaching problems
4. **Risk Appetite**: Takes on more challenging/risky projects knowing AI support available
5. **Identity Evolution**: Comfortable with progression from developer → architect → senior architect
6. **Critical Realism**: "Nice to have, not must have" - wouldn't be invalidated if AI disappeared

### Social Dynamics
- **R&D Colleagues**: Share AI experiences during lunch, all technical enthusiasts, brings them together
- **Management Tensions**: 
  - Some managers are "dreamers" detached from reality
  - Want AI integration "yesterday in production, today"
  - One PM wants dual algorithm versions (traditional + neural network)
  - Participant diplomatically navigates unrealistic expectations
  - Management pressure comes from above, has ambitions
- **AI Team Collaboration**: Informal cooperation outside main project line
- **Flat Hierarchy**: Company has flat structure, no juniors under seniors

### Professional Development
- Winter DIY projects planned with AI assistance (Flask web server)
- Learning rate unchanged - depends on time invested, not tools
- 90% of projects are challenges (>6 months each)
- Sees natural progression with technology evolution
- Already preparing for ML integration despite current skepticism

### Post-Interview Observations
- Interview lasted 2.5 hours, participant remained energetic throughout
- Continued for another hour post-recording with AI agent demonstrations
- Responses were deeply structured with references to complex concepts
- AI viewed as rational tool with emotional impacts
- Anthropomorphizes AI despite knowing they're tools
- Sees AI as "gift" he could lose
- Very curious about AI agents, started using them immediately after interview

### Key Quotes on Future
- "Good foundation, good roots can never be wasted"
- "Whoever doesn't adapt will lose in the end"
- "I'm prepared for AI-augmented phase solving more complex problems, but not piloted/replaced"
- On juniors: "They skip the critical phase" - recommends strong fundamentals

### Final Assessment
Uses AI assistants very rationally, expects AI-progressive career path. Comfortable with coming changes as natural evolution of developer tools, similar to move from assembly → C → high-level languages. Maintains critical distance while embracing productivity gains.