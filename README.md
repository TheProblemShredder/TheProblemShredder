# TheProblemShredder

Verification-first engineering & research demos: preregistration → controls → ablations → blinded eval → PASS/FAIL → audit ledger.

## Proof-driven public demos (clone + run)
- **ScrollCert vΩ (Verification-First Research Demo)**  
  https://github.com/TheProblemShredder/ScrollCert_vOmega_PublicDemo  
  Reproducibility certificate harness: prereg thresholds, negative controls, ablations, blinded evaluation, deterministic IDs, append-only ledger.

- **ML Eval Harness vΩ (Public Demo)**  
  https://github.com/TheProblemShredder/ML_Eval_Harness_vOmega  
  Deterministic eval scaffold: prereg thresholds, delta gates, negative control gate, optional blinding + reveal, audit ledger.

- **Quant Backtest Harness vΩ (Public Demo)**  
  https://github.com/TheProblemShredder/Quant_Backtest_Harness_vOmega  
  Deterministic backtest scaffold: prereg parameters, delta/ablation gates, negative control gate, audit-friendly outputs.

- **CLI Tooling vΩ (Public Demo)**  
  https://github.com/TheProblemShredder/CLI_Tooling_vOmega  
  Production-style Python CLI scaffold: subcommands, config support, structured JSON logging, deterministic run IDs, tests + CI.

## Why this exists
Most “results” don’t ship with:
- preregistered thresholds  
- negative controls  
- ablation discipline  
- deterministic IDs + content-hash evidence spine  
- append-only audit ledger

These repos show the scaffolding to make that normal.

## What I’m open to
- Verification / evaluation infrastructure
- Reproducible research tooling
- ML/quant experiment harnesses
- Applied cryptographic provenance / audit trails
- Systems & automation around CI + artifacts

📍 UK — open to remote / relocation for the right role.
