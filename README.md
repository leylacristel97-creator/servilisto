# ServiListo

Repositorio del proyecto ServiListo. Incluye skills de diseño para Claude Code en `.claude/skills/`, que se cargan automáticamente al trabajar en este repositorio.

## Skills instaladas

| Origen | Licencia | Commit | Skills |
|---|---|---|---|
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | MIT | `e8a175d` | animate, animate-expo, animation-vocabulary, apple-design, ask-sonner, break-ui, emil-design-eng, find-animation-opportunities, improve-animations, mobile-native, pick-ui-library, prototype, review-animations, write-swift |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | Apache-2.0 | `a40571a` | impeccable (`/impeccable init`, `polish`, `audit`, `critique`, `animate`, …) |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | MIT | `ce26fc2` | design-taste-frontend, design-taste-frontend-v1, gpt-taste, high-end-visual-design, minimalist-ui, industrial-brutalist-ui, redesign-existing-projects, brandkit, image-to-code, imagegen-frontend-web, imagegen-frontend-mobile, stitch-design-taste, full-output-enforcement |

Las licencias originales están en `third_party_licenses/`.

### Notas

- Las carpetas de taste-skill se renombraron al valor `name:` de cada `SKILL.md` (p. ej. `soft-skill` → `high-end-visual-design`).
- De impeccable solo se copió la skill; **no** se instalaron sus hooks (`.claude/settings.json`) ni sus binarios nativos. Para la instalación completa: `npx impeccable install` (ver su README).
- Para actualizar: `npx skills add emilkowalski/skills`, `npx skills add https://github.com/Leonxlnx/taste-skill`, `npx impeccable update`.
