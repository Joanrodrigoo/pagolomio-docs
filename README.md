# PagoLoMio 🧾

> **La forma més ràpida i intel·ligent de dividir el tiquet del restaurant sense drames ni calculadores.**

PagoLoMio és una aplicació multiplataforma (iOS/Android) dissenyada per a resoldre el problema clàssic de "qui ha pres què" en els sopars de grup. Mitjançant l'ús de visió artificial (OCR) i intel·ligència artificial (LLM), l'app digitalitza el tiquet físic en segons i permet una divisió col·laborativa en temps real.


## 🎯 Objectiu
L'objectiu de PagoLoMio és transformar un procés analògic tediós en una experiència digital fluida, justa i transparent. L'app no només suma preus, sinó que entén el tiquet i optimitza els deutes entre els amics per a minimitzar el nombre de transferències necessàries.

## ✨ Funcionalitats Principals

- **Escaneig Híbrid (OCR + IA)**: Combina Google ML Kit (local) per a l'extracció ràpida de text amb models de llenguatge al núvol (Gemini/Groq) per a estructurar dades complexes automàticament.
- **Sincronització en Temps Real**: Gràcies a Supabase, tots els comensals veuen qui està reclamant cada producte a l'instant.
- **Algoritme de Liquidació Greedy**: Calcula el balanç net del grup i genera la llista mínima de transferències (N-1) per a tancar el compte.
- **Gestió de Grups i Historial**: Crea grups per a viatges o sopars recurrents i mantingues la traçabilitat de qui deu què a qui.
- **Notificacions Push**: Avisos instantanis quan un amic crea un tiquet nou o tanca una liquidació.

## 🛠️ Stack Tecnològic

- **Frontend**: Flutter (Dart)
- **Gestió d'Estat**: Riverpod 3.0
- **Backend**: Supabase (PostgreSQL + Realtime + Edge Functions)
- **IA**: Google Gemini Pro / Groq (Llama 3)
- **Visió Artificial**: Google ML Kit (Text Recognition)
- **Notificacions**: OneSignal
- **Navegació**: GoRouter

## 🚀 Instal·lació i Configuració

1. **Clonar el repositori**:
   ```bash
   git clone https://github.com/usuari/pagolomio.git
   ```
2. **Instal·lar dependències**:
   ```bash
   flutter pub get
   ```
3. **Configurar variables d'entorn**:
   Crea un fitxer `.env` a l'arrel amb:
   - `SUPABASE_URL`
   - `SUPABASE_ANON_KEY`
   - `GEMINI_API_KEY`
   - `GROQ_API_KEY`
4. **Executar l'aplicació**:
   ```bash
   flutter run
   ```

---
*Projecte desenvolupat íntegrament per **Joan Rodrigo** de forma voluntària.*
