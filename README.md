# INNO

Single-file HTML pages as a communication medium — spatial, interactive, self-contained.

Deployed via Vercel: https://inno-henri3s.vercel.app

## Structure

| Directory | Purpose |
|---|---|
| `exploration/` | Side-by-side code comparisons, implementation plans |
| `code-review/` | Annotated PR diffs, module maps |
| `design/` | Design systems, component variants |
| `prototyping/` | Animation sandboxes, clickable flows |
| `diagrams/` | SVG figures, annotated flowcharts |
| `decks/` | Arrow-key slide decks |
| `research/` | Feature explainers, concept explainers |
| `reports/` | Weekly status, incident reports |
| `editors/` | Triage boards, flag editors, prompt tuners |

## Usage

```bash
# Add an HTML file
echo '<!DOCTYPE html>...' > exploration/my-comparison.html

# Deploy
git add . && git commit -m "add comparison" && git push

# Vercel auto-deploys from main
```