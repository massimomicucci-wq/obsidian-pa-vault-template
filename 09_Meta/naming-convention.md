# Naming Convention — OGI Knowledge Base

## Prefissi obbligatori

| Prefisso | Cliente / Ambito |
|----------|-----------------|
| `EDFE_`  | Environmental Defense Fund Europe |
| `SGI_`   | Società Gasdotti Italia |
| `OCTO_`  | OCTO Telematics |
| `Tempo_` | Project Tempo / Confagricoltura |
| `OGI_`   | Open Gate Italia (interno) |
| `Geo_`   | Analisi geopolitica trasversale |
| `Parl_`  | Monitoraggio parlamentare trasversale |

## Formato

```
PREFISSO_NomeDoc_MeseAnno.estensione

Esempi:
  EDFE_BriefingParlamentare_Mag2026.md
  SGI_NotaStrategica_Apr2026.docx
  Geo_AnalisiHormuz_Mar2026.md
  OGI_RassegnaStampa_20260515.md
```

## Regole

1. **Nessuno spazio** — usare CamelCase o underscore
2. **Data sempre in coda** — formato `MesAnno` (it) o `YYYYMMDD` per file giornalieri
3. **Versioning** — aggiungere `_v2`, `_v3` solo se coesistono versioni diverse
4. **Draft** — aggiungere `_DRAFT` prima della data per bozze non condivise
5. **Archivio** — spostare in `06_Archive/` con prefisso `ZZ_` quando chiuso

## Cartelle

```
00 - Inbox/          → capture rapida, non elaborata
01 - Clienti/        → un folder per cliente
02 - Dossier/        → tematici, trasversali ai clienti
03 - Parlamento/     → commissioni, DDL, contatti
04 - Prompt Library/ → prompt AI per Claude
05 - Templates/      → template Obsidian (Templater)
06 - Archive/        → materiale chiuso
09 - Meta/           → configurazione vault
```

