# 🗂️ Obsidian PA Vault Template

Template di un vault **Obsidian** progettato per consulenti di Public Affairs, lobbying e comunicazione strategica.
Struttura testata in produzione su dossier energetici, parlamentari e geopolitici.

---

## Struttura del vault

```
Ogi Knowledge Base/
├── 00 - Inbox/              # Capture rapida, note non elaborate
├── 01 - Clienti/            # Un folder per cliente, con naming convention
│   ├── EDFE/
│   ├── SGI/
│   ├── OCTO/
│   └── _template_cliente/
├── 02 - Dossier/            # Dossier tematici trasversali ai clienti
│   ├── EUMR/                # EU Methane Regulation
│   ├── Piano_Mattei/
│   ├── Geopolitica_Gas/
│   └── Nomine_Enti/
├── 03 - Parlamento/         # Monitoraggio parlamentare
│   ├── Commissioni/
│   ├── DDL_Tracking/
│   └── Contatti_Istituzionali/
├── 04 - Prompt Library/     # Prompt per AI (Claude, GPT)
├── 05 - Templates/          # Template note, brief, report
├── 06 - Archive/            # Materiale storico e chiuso
└── 09 - Meta/               # Configurazione vault, workflow
```

---

## Naming convention

```
PREFISSO_NomeDoc_MeseAnno.estensione

Prefissi:
  EDFE_   → Environmental Defense Fund Europe
  SGI_    → Società Gasdotti Italia
  OCTO_   → OCTO Telematics
  Tempo_  → Project Tempo
  OGI_    → Open Gate Italia (interno)
  Geo_    → Analisi geopolitica
```

---

## Plugin consigliati

| Plugin | Uso |
|--------|-----|
| Dataview | Query su note e dossier attivi |
| Templater | Template dinamici per clienti e brief |
| Calendar | Vista temporale scadenze parlamentari |
| Tasks | Tracking azioni e follow-up |
| QuickAdd | Capture rapida da qualsiasi contesto |

---

## Integrazione con Claude (MCP)

Il vault è configurato per l'accesso via **MCP (Model Context Protocol)** su macOS,
permettendo a Claude di leggere e scrivere note direttamente nel vault.

```
Percorso iCloud: ~/Library/Mobile Documents/com~apple~CloudDocs/Ogi Knowledge Base/
```

---

## Licenza

MIT — libero utilizzo con attribuzione.
