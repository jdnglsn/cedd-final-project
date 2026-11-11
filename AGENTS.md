# Repository workflow

- Make and commit all changes on `dev` first. Do not commit directly to `main`.
- Use Conventional Commits, such as `chore: configure Arduino repository`,
  `docs: update wiring guide`, `feat: add mouse controls`, or `fix: correct button handling`.
- Commit completed, coherent changes regularly. Do not commit unrelated user changes.
- Keep the Arduino sketch at `CEDD/CEDD.ino`; the sketch and its containing folder must share the name.
- Keep build artifacts, local settings, and secrets out of version control.
- Do not add firmware until the user requests implementation.
- Report actual validation performed; never imply a hardware test or compilation occurred if it did not.
