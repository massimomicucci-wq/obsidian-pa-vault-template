# Setup e Plugin Consigliati

## Plugin Obsidian essenziali

### Core (installare per primi)
| Plugin | Funzione | Configurazione chiave |
|--------|----------|----------------------|
| **Templater** | Template dinamici con variabili date/titolo | Cartella template: `05_Templates/` |
| **Dataview** | Query su note come database | Abilitare JS queries |
| **Tasks** | Task management con date e filtri | Formato: `- [ ] task 📅 YYYY-MM-DD` |
| **Calendar** | Vista calendario note giornaliere | Link a Daily Notes |
| **QuickAdd** | Capture rapida e automazioni | Configurare macro per ogni template |

### Workflow PA
| Plugin | Funzione |
|--------|----------|
| **Tag Wrangler** | Gestione gerarchica dei tag |
| **Folder Note** | Note indice per ogni cartella |
| **Strange New Worlds** | Visualizza backlink in anteprima |
| **Obsidian Git** | Backup automatico su GitHub |

---

## Integrazione Claude via MCP

Il vault è progettato per laccesso diretto da Claude tramite MCP (Model Context Protocol).

### Configurazione macOS
```
Percorso vault (iCloud):
~/Library/Mobile Documents/com~apple~CloudDocs/Ogi Knowledge Base/

MCP server: ogi-knowledge-base
Accesso: lettura + scrittura su tutto il vault
```

### Operazioni abilitate via MCP
- Lettura note e dossier attivi
- Scrittura nuove note da template
- Ricerca full-text nel vault
- Aggiornamento log attività

---

## Daily Note — struttura consigliata

```markdown
# {{date:dddd D MMMM YYYY}}

## Agenda
- 

## Dossier attivi oggi
- 

## Rassegna stampa
- 

## Follow-up
- [ ] 

## Note
```

---

## Workflow quotidiano tipo

```
07:30  Apertura vault → Daily Note
07:45  Lettura rassegna stampa Michele Cozzolino (Gmail)
08:00  Intelligence Briefing via Claude (Cowork automation)
08:30  Aggiornamento dossier attivi
09:00  Prima call / incontro
...
Fine   Log attività + aggiornamento follow-up
```

