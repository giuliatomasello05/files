# Documenti pubblici di Giulia Tomasello

Certificazioni e attestati pubblici collegati dal
[curriculum](https://github.com/giuliatomasello05/curriculum).

## Documenti disponibili

| Anno | Documento | File / collegamento pubblico |
| --- | --- | --- |
| 2025 | Certificazione di inglese | [2025-certificazione-inglese.pdf](https://github.com/giuliatomasello05/files/blob/main/2025-certificazione-inglese.pdf) |
| 2025 | Attestato webinar Basics and Principles of GC, Restek | [2025-basic-and-principles-of-gc-by-restek.pdf](https://github.com/giuliatomasello05/files/blob/main/2025-basic-and-principles-of-gc-by-restek.pdf) |

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

Non serve un processo di build in questa repository: i PDF sono documenti
originali da versionare. Il `.gitignore` esclude solo file temporanei.

Non rinominare o eliminare file già pubblicati senza aggiornare anche tutti i
collegamenti e considerare che gli URL potrebbero essere già condivisi altrove.
Il PDF generato del curriculum resta nella cartella locale `curriculum/build/`.
