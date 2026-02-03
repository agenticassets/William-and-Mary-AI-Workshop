# William & Mary AI Workshop Module
## Most Critical Rule
All content must be **publicly shareable and standalone**; never include private credentials or client-specific secrets in JSON templates or markdown files. 

## Naming Patterns
- **Workflows**: JSON templates should be named by function (e.g., `Redfin_Market_Expert.json`).
- **Resources**: Markdown guides use `[Topic]-Best-Practices.md` or `[Action]-Checklist.md`.
- **Assets**: All images must reside in the local `Images/` folder for portability.

## Module Boundaries
- **Owned**: W&M specific curriculum, localized resources, and demo workflow JSONs.
- **Delegated**: Generic CRE ROI frameworks to `@Resources/`, root presentation logic to `@Presentations/`.

## Integration Points
- **n8n**: Workflows in `Workflow-Templates/` must use standard OpenRouter and Firecrawl credential patterns.
- **LaTeX**: Beamer source `AI-Agents-Real-Estate-Revolution.tex` uses local `Images/` for slides.
- **Setup**: Onboarding relies on `@Resources/Pre-Course-Setup-Checklist.md`.

## Folder Gotchas
- **Paths**: LaTeX and READMEs use relative paths (e.g., `Images/...`) for standalone repo compatibility.
- **n8n Credentials**: Students must manually reconnect credentials after importing JSON templates.

## 📚 References
- `@workshops/CLAUDE.md` - Workshop module standards
- `@Resources/Real-Estate-AI-Use-Cases.md` - Context for agents
