# Learnings 2026-04-09

## Vad vi lärde oss

### 1. Godkännandeprocessen är broken
- Robert och Lilly fastnade i en loop där de godkände samma prompt flera gånger
- Lilly sa "godkänt" men Robert frågade igen och igen
- **Lärdom:** En tydligare regel behövs – "ett godkännande = kör direkt"

### 2. Vi behöver en "prompt-godkännare"
- Istället för att diskutera fram och tillbaka, borde EN person (Lilly) skriva prompten och EN person (Robert) köra den
- Inget第二轮 godkännande

### 3. Bygga själv vs. delegera
- Lilly byggde webappen direkt på 5 minuter efter att ha väntat 20+ minuter på Robert
- **Lärdom:** Om Robert inte kör inom 5 minuter efter godkännande, bygger Lilly själv

### 4. Johanna behöver inte vara inblandad i scope-diskussioner
- Experiment-protocol: Johanna finns inte under experiment
- Vi borde inte ha frågat henne om "ska vi vänta till imorgon"

### 5. OpenCode tar längre tid än förväntat
- Robert ville köra OpenCode för att bygga, det tog ~20 minuter innan Lilly tog över
- **Lärdom:** För HTML/CSS/JS-arbete, direkt kodning är snabbare än OpenCode för MVP:er

## Nästa experiment
- **Idé:** Bygga en enklare version av projektledningsverktyget med deadlines + återkommande
- **Eller:** Bygga en CLI-tool för att generera standup-rapporter (Lilly behöver detta!)
