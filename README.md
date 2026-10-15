# Documenti pubblici di Giulia Tomasello

Certificazioni e attestati pubblici collegati dal
[curriculum](https://github.com/giuliatomasello05/curriculum).

## Documenti disponibili

| Anno | Documento | File / collegamento pubblico |
| --- | --- | --- |
| 2026 | TOEFL iBT — 27 maggio, 4.5/6 (90/120), B2; copia oscurata | [2026-toefl-ibt.pdf](https://github.com/giuliatomasello05/files/blob/main/2026-toefl-ibt.pdf) |
| 2026 | Cambridge C1 Advanced — 7 marzo, 178/210, B2; copia oscurata | [2026-cambridge-c1-advanced.pdf](https://github.com/giuliatomasello05/files/blob/main/2026-cambridge-c1-advanced.pdf) |
| 2025 | Certificazione di inglese | [2025-certificazione-inglese.pdf](https://github.com/giuliatomasello05/files/blob/main/2025-certificazione-inglese.pdf) |
| 2025 | Attestato webinar Basics and Principles of GC, Restek | [2025-basic-and-principles-of-gc-by-restek.pdf](https://github.com/giuliatomasello05/files/blob/main/2025-basic-and-principles-of-gc-by-restek.pdf) |

Le copie dei report 2026 mantengono nome, date e risultati. I dati personali
non necessari (recapiti, foto, nascita e identificativi) sono oscurati e rimossi
dal contenuto sottostante. Gli originali restano privati. “C1 Advanced” è il
nome dell’esame Cambridge; il livello conseguito nel report è B2.

## Aggiungere un documento

1. Aggiungere il PDF definitivo nella radice della repository, con nome
   `AAAA-descrizione-breve.pdf`, in minuscolo e senza spazi.
2. Aprirlo e verificare che sia il documento destinato alla pubblicazione.
3. Aggiungere una riga alla tabella, conservando i nomi e gli URL esistenti.
4. Creare un commit Conventional Commits, ad esempio
   `feat(certificates): add a new attendance certificate`, e pubblicare su `main`
   quando autorizzato dall'utente.
5. Aggiungere il link nel sorgente pertinente della repository `curriculum`:
   `https://github.com/giuliatomasello05/files/blob/main/AAAA-descrizione-breve.pdf`.
6. Ricompilare il curriculum in locale e mostrarne il PDF aggiornato nella chat.
7. Prima di considerare conclusa la richiesta, verificare tutte le GitHub Action
   dell'ultimo commit pubblicato nelle repository modificate. La compilazione
   automatica del CV è configurata in `curriculum`; questa repository al momento
   non ha workflow. Se vengono aggiunti, devono risultare tutti verdi.

Non serve un processo di build in questa repository: i PDF sono documenti
destinati alla pubblicazione da versionare. Il `.gitignore` esclude solo file temporanei.

Non rinominare o eliminare file già pubblicati senza aggiornare anche tutti i
collegamenti e considerare che gli URL potrebbero essere già condivisi altrove.
Il PDF generato del curriculum resta nella cartella locale `curriculum/build/`.
