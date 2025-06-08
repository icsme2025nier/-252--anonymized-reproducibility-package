# Transcript Executive Summary: Jiri Otoupal (Senior Developer)
**Date:** May 9, 2025  
**Duration:** ~60 minutes (cut short due to technical issues)  
**Context:** Phenomenologically-informed interview about AI agent experiences in software development

## Opening & Context Setting
- Jiri is a senior developer with 8 years experience [6:46]
- Works in two companies:
  - Large corporation: Security monitoring for companies like Vodafone, banks [3:31]
  - Small startup (~5 people): Developing AI sales agent [3:31]
- Programming languages: Primarily Python, also C++, Java, Kotlin [6:46]
- AI experience: Started with training image recognition models before ChatGPT, using AI since GPT-3.5 [5:47]
- Uses Cursor AI agent and ChatGPT, avoids Copilot as "not useful enough" [5:14]

## Key Experiences with AI Agents

### Experience 1: Mobile App Development in Kotlin (Complex/Frustrating)
**Context:** Developing video compression app for Android in Kotlin - a language he'd never used [11:55]

**Initial Approach & Frustration:**
> "Začal jsem s tím, že jsem, když jsem vlastně začal té toho agenta používat jako poprvé, tak jsem se snažil udělat ten prompt jako sám. Což nějakým způsobem funguje. Jenomže pak člověk začne být jako velice frustrovaný s tím, že vlastně ten agent on dělá strašně moc short katů." [11:55]

**The Serialization Problem:**
- Asked to save videos to history
- Agent imported irrelevant Google libraries incompatible with Kotlin [16:08]
- Result: Project wouldn't compile, had to revert everything [17:21]

**Recovery Process:**
1. Used Sonnet 3.5 initially (via Cursor) [29:23]
2. Switched to GPT-4o assistant for research [23:53]
3. Googled to verify correct approach
4. Returned to agent with specific instructions

**Key Insight on Agent Behavior:**
> "Čím chytřejší model tím víc dělá hlouposti, ale zas může zas jakoby na generování toho 1. Řešení může být excelentní." [11:12]

### Experience 2: Form Field Removal (Simple/Successful)
**Context:** Removing document type and name fields from Django/Python upload form [32:23]

**Process:**
- Direct instruction: "Remove document type, remove name, not needed, preserve original functionality" [33:06]
- Agent made correct changes but also renamed variables unnecessarily
- Had to regenerate with stricter instructions

**Emotional Response to Agent Output:**
> "Já vždycky, když ono vlastně vytvoří ten výstup, tak já mám pocit jako nejistoty a vlastně trochu strachu toho, jestli náhodou neupravuje něco jinýho." [34:24]

**His Unique Approach:**
> "Já vždycky vlastně úplně zničím to, co on vygeneroval. A vlastně jako jako kdyby jsem to dav zadával tu tu stejnou otázku znovu, abych vlastně nerozšiřoval to kontakt s Windows." [35:40]

### Experience 3: Audio Waveform Visualization (Mysterious Success)
**Context:** Creating waveform visualization for voice recordings in note-taking app [47:04]

**Outcome:**
> "Fungovalo to, takže to je to je jakoby nějaká nějakými pocity, že je to super, že to funguje úplně. Nevím jak to, jak to, jak to jako udělal a nemám čas se dívat na to, jak to udělal." [47:34]

**Impact on Competence:**
> "Díky tomu, že často vidím, že on to udělá třeba jako napůl řešení... tak spíš mám pocit toho, že naštěstí jako pořád ještě nahranej nebudu." [48:51]

## Core Themes

### 1. Control Through Memory Erasure
> "Jakmile, jakmile on se vychýlí, vychýlil až moc ze směru, tak jsem musel zasít zpátky na začátek... smazat tu historii celou, co on psal a začít jinak." [50:24]

When asked about negotiation vs memory erasure:
> "V malejch procentech případů se to podaří, ale většinou většinou to opravdu dělám tak, že ho prostě vymažu paměť a pak to funguje." [51:55]

### 2. Risk Aversion in Professional Context
> "Ty žínky jsou strašně problematický v tom, že oni strašně rádi upravují něco, co nemají upravovat. AV práci si to nemůžu dovolit... Ten problém, a to riziko je příliš vysoký." [18:02]

Uses agents only for:
- Personal projects where risk is acceptable
- Frontend sketches in smaller company
- Never in large corporation with existing codebase

### 3. Productivity Enhancement Through Automation
> "Ten agent vlastně díky tomu, že on mi pomáhá dělat ty nudný a otravný věci rychleji, tak mám daleko větší... energii dělat projekty." [45:16]

> "Vlastně mít z toho rychleji ten dopamin toho, že funguje, mi to nějakým způsobem a můžu už dělat jakoby vlastní věci a to, co mě zajímá to, co mě baví." [45:16]

### 4. Agent as Directionless Junior Developer
> "Je tam je, je to vlastně nějakej stroj, kterej dělá nějakej nějakej úkol. Ale ten stroj nedokáže. To vlastně udělat sám, bez bez specifický pomoci specifickýho vedení." [44:28]

Comparing to human colleagues:
> "Opravím směr něco podobnýho, jak prostě juniorní programátor, když dělá nějaký věci. Tak taky se snaží udělat to nějakým způsobem. Abys to ulehčil a vlastně to jako zhorší jenom." [52:19]

### 5. Team Trust Erosion
> "Jakmile soud, jakmile jsou používaní v týmech. Tak je to obrovský problém... je tam většinou nedůvěra velká... V týmech vyvolává podle mě extrémní nedůvěru a extrémní vlastně pocit toho, že ten člověk neví, co dělá." [56:01]

## Emotional Landscape

**Frustration Management:**
> "Ano, jakoby já cítím určitou frustraci toho, že on nedělá to, co by úplně měl dělat... Může to být buďto frustrace, nebo nebo bez emoční." [52:19]

**Human vs AI Frustration:**
> "Když to dělám s tím lidským kolegou, tak můžu být jako víc frustrovaný kvůli tomu, že. On vlastně nechápe to, co je to, co jakoby chci... Ale tomu stroji se dá vysvětlit." [54:32]

## Professional Identity Impact

When asked about impact on developer identity:
> "Asi bych řekl, že žádný žádný jakoby jako asi asi nevidím. Asi nevidím žádný vlastně vlivy." [55:50]

## Key Characteristics of Jiri's AI Usage
1. **High control need** - erases memory rather than negotiates
2. **Risk-aware** - won't use agents in production/corporate code
3. **Efficiency-focused** - uses AI to skip boring setup, get to interesting work
4. **Technically sophisticated** - understands model limitations from training experience
5. **Emotionally detached** - treats as tool requiring specific management
6. **Trust concerns** - believes AI agents create distrust in teams

## Post-Interview Reflection
The interview was marked by significant technical difficulties with internet connection dropping multiple times. Despite this, Jiri provided rich phenomenological descriptions of his experiences, particularly around the emotional aspects of control, frustration, and the strategic use of "memory erasure" as a management technique. His perspective as someone who trained models pre-ChatGPT provides unique insights into the limitations and appropriate use cases for AI agents.

**Key Narrative:** Experienced developer who understands AI deeply from building models, uses agents strategically for personal projects while maintaining strict boundaries in professional work, managing them like "junior developers who make things worse trying to help."