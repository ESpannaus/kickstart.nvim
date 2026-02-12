# Neovim Kickstart Cheatsheet

Leader = `<Space>`

## Navigation

| Taste | Aktion |
|-------|--------|
| `h j k l` | links, runter, hoch, rechts |
| `w` / `b` | Wort vorwärts / zurück |
| `gg` / `G` | Anfang / Ende der Datei |
| `<C-o>` | Zurück in der Jumplist |
| `<C-i>` | Vorwärts in der Jumplist |
| `öd` / `äd` | Vorheriger / nächster Diagnostic |
| `öc` / `äc` | Vorheriger / nächster Git Hunk |
| `{` / `}` (Ö / Ä) | Vorheriger / nächster Paragraph |

## Dateien & Buffer

| Taste | Aktion |
|-------|--------|
| `<Space>sf` | Datei suchen (Telescope) |
| `<Space>sg` | Text im Projekt suchen (Grep) |
| `<Space><Space>` | Offene Buffer wechseln |
| `<Space>s.` | Zuletzt geöffnete Dateien |
| `<Space>sn` | Neovim-Config-Dateien suchen |
| `:vs datei` | Vertikaler Split |
| `:sp datei` | Horizontaler Split |
| `<C-h/j/k/l>` | Zwischen Splits wechseln |

## LSP (Code Intelligence)

| Taste | Aktion |
|-------|--------|
| `grd` | Go to Definition |
| `grr` | Go to References |
| `gri` | Go to Implementation |
| `grt` | Go to Type Definition |
| `grD` | Go to Declaration (C: Header) |
| `grn` | Rename (über alle Dateien) |
| `gra` | Code Action (Quickfix etc.) |
| `gO` | Symbole im aktuellen File |
| `gW` | Symbole im Workspace |
| `<Space>th` | Inlay Hints ein/aus |
| `<Space>q` | Diagnostic-Liste öffnen |

## Autocomplete (blink.cmp)

| Taste | Aktion |
|-------|--------|
| `<C-n>` / `<C-p>` | Nächster / vorheriger Vorschlag |
| `<Enter>` | Vorschlag annehmen* |
| `<C-space>` | Menü manuell öffnen |
| `<C-e>` | Menü schließen |
| `<C-k>` | Signatur-Hilfe (Parameter) |
| `<Tab>` / `<S-Tab>` | Snippet-Felder durchgehen |

*falls preset auf `'enter'` gesetzt

## Suche

| Taste | Aktion |
|-------|--------|
| `/` | Suche im Buffer |
| `n` / `N` | Nächster / vorheriger Treffer |
| `<Esc>` | Highlight entfernen |
| `<Space>/` | Fuzzy-Suche im aktuellen Buffer |
| `<Space>s/` | Grep in offenen Dateien |
| `<Space>sw` | Wort unter Cursor suchen |
| `<Space>sh` | Hilfe durchsuchen |
| `<Space>sk` | Keymaps durchsuchen |
| `<Space>sd` | Alle Diagnostics durchsuchen |
| `<Space>sc` | Commands durchsuchen |
| `<Space>sr` | Letzte Suche fortsetzen |

## Editieren

| Taste | Aktion |
|-------|--------|
| `i` / `a` | Insert vor / nach Cursor |
| `o` / `O` | Neue Zeile darunter / darüber |
| `dd` | Zeile löschen |
| `yy` | Zeile kopieren |
| `p` / `P` | Einfügen nach / vor Cursor |
| `u` / `<C-r>` | Undo / Redo |
| `.` | Letzte Aktion wiederholen |
| `gcc` | Zeile (un)kommentieren |
| `gc` + Motion | Block (un)kommentieren |
| `<Space>f` | Buffer formatieren |

## Surround (mini.surround)

| Taste | Aktion |
|-------|--------|
| `saiw)` | Wort mit `()` umschließen |
| `sd'` | Surrounding `'` löschen |
| `sr)'` | Surrounding `)` durch `'` ersetzen |

## Text Objects

| Taste | Aktion |
|-------|--------|
| `va)` | Visuell selektieren Around `)` |
| `ci'` | Change Inside `'` |
| `di"` | Delete Inside `"` |
| `yap` | Yank Around Paragraph |

## Sonstiges

| Taste | Aktion |
|-------|--------|
| `:w` | Speichern |
| `:q` | Schließen |
| `:wq` | Speichern & schließen |
| `:Lazy` | Plugin-Manager öffnen |
| `:Mason` | LSP/Tool-Manager öffnen |
| `:checkhealth` | Setup prüfen |
| `<Space>ss` | Telescope-Picker auswählen |
