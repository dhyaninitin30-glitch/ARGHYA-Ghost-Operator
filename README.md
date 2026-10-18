# ARGHYA CTF — Ghost Operator Dossier

**Category:** Forensics · OSINT · Cryptography  
**Difficulty:** Insane

## Mission

A recovered archive contains several artifacts that appear unrelated at first glance. Reconstruct the chain of evidence and recover the final flag.

## Artifact Index

Open `challenge_files/` and download each artifact individually. The order below is a suggested investigation path, not a list of answers.

1. **`rf_waterfall_spectrum.png` — Signal Capture**  
   Examine the axes carefully. The most prominent signal is not, by itself, sufficient evidence.

2. **`ground_stations_and_tle.json` — Calibration and Timing**  
   Correlate measurements with compatible time windows. Do not rely on a single matching field.

3. **`darknet_financial_ledger.json` — Transaction Trail**  
   At the branching point, validate the candidate using evidence from another artifact. The amount alone is not decisive.

4. **`syndicate_pgp_keyring.json` — Trust Analysis**  
   Several entries are similar. Find the entry that satisfies all cryptographic and trust conditions together.

5. **`encrypted_zephyr_dossier.enc` — Final Dossier**  
   Work on this last. Reconstruct the required values from the earlier artifacts before attempting decryption.

## Working Notes

- Record intermediate values and the evidence supporting each choice.
- A single matching clue is not proof; corroborate it across artifacts.
- All station identifiers, satellite records, wallet-like strings, and transactions are fictional synthetic CTF data. Wallet-like strings are puzzle identifiers, not verified blockchain addresses. Satellite records are not intended for real-world orbital tracking.

Good luck, operator.
