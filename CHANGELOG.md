# Changelog

Storia delle regressioni sintetiche Android di NOVA, dalle più recenti.

## 2026-11-14

- Rimossa la copia obsoleta del workflow widget finita per errore in
  `.github/workflows/.github/workflows/`: GitHub non la eseguiva, ma restava
  una seconda versione non allineata del controllo.
- SUPPORT.md: politica di supporto (sole segnalazioni di bug) e come segnalare.
- Template issue per bug e richieste di funzione.
- README: link aggiornati dopo la rinomina dell'account GitHub in `federicotaar`.
- Documentazione Javadoc in testa a ogni harness di regressione.

## 2026-10-28

- Release Android 17 (`v2026.10.28.android.17`): widget verificati (6-ParityVerified) con rendering di contenuti lunghi.

## 2026-10-24

- Primo harness: sorgente bridge in regressione con soli test sintetici.
- Workflow CI `android-check` su Ubuntu 22.04 con platform-tools per installare l'APK.
