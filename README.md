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

<img width="381" height="849" alt="TicketEscaneadoRevisar" src="https://github.com/user-attachments/assets/2af57810-b0f9-4e09-b18d-c2f2fc072e1c" />
<img width="382" height="848" alt="ticketEscaneado" src="https://github.com/user-attachments/assets/63b98f9a-d012-4bf0-8447-36adb4810560" />
<img width="388" height="872" alt="registro" src="https://github.com/user-attachments/assets/11eba129-e5cf-42ce-962e-e39e895b8e0c" />
<img width="381" height="873" alt="nuevoTicket" src="https://github.com/user-attachments/assets/8fa19169-90b7-4ee7-ac86-00aae336dc30" />
<img width="380" height="846" alt="miembrosGrupo" src="https://github.com/user-attachments/assets/ae700571-98ed-4598-9143-aac40f529095" />
<img width="379" height="881" alt="mainscreen" src="https://github.com/user-attachments/assets/6f0cb04d-7011-44f6-a603-9841f454b2e5" />
<img width="388" height="898" alt="login" src="https://github.com/user-attachments/assets/34c7ec76-5849-452b-8265-cb574c22ecaf" />
<img width="378" height="847" alt="GrupoTickets" src="https://github.com/user-attachments/assets/5a4a67af-d5f7-4f48-8f83-220e7357ce84" />
<img width="381" height="843" alt="formaDePago" src="https://github.com/user-attachments/assets/c602a939-2034-4341-90cf-6faede4aaa0a" />
<img width="386" height="851" alt="desglose" src="https://github.com/user-attachments/assets/131d36f4-7cdd-4ebb-a254-f47c85a003ee" />


## 🛠️ Stack Tecnològic

- **Frontend**: Flutter (Dart)
- **Gestió d'Estat**: Riverpod 3.0
- **Backend**: Supabase (PostgreSQL + Realtime + Edge Functions)
- **IA**: Google Gemini Pro / Groq (Llama 3)
- **Visió Artificial**: Google ML Kit (Text Recognition)
- **Notificacions**: OneSignal
- **Navegació**: GoRouter
