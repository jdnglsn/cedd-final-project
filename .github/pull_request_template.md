## Summary

<!-- Describe the problem, what changed, and the expected behavior. Link related issues if applicable. -->

## Validation

<!-- List checks actually performed and their results. For firmware changes, include board model, ESP32 core version, library versions, and compilation result. Describe hardware tests separately. State "Not tested" with a reason where applicable. -->

## Pull request checklist

<!-- Check items only after verifying them. For an inapplicable item, leave it unchecked and add "N/A" with a short reason. -->

- [ ] Changes were committed to `dev` first; a release PR targets `main` from `dev`.
- [ ] Commit messages follow Conventional Commits (`feat:`, `fix:`, `docs:`, `chore:`, etc.).
- [ ] The diff contains only intended changes and has been reviewed by the author.
- [ ] No secrets, local configuration, or generated build artifacts are included.
- [ ] The Arduino sketch remains at `CEDD/CEDD.ino`.
- [ ] Relevant README, wiring, setup, and dependency documentation is updated.
- [ ] Compilation results are recorded above, or explicitly marked not run / N/A.
- [ ] Hardware test results are recorded above, or explicitly marked not run / N/A.

## Hardware checks (when applicable)

- [ ] Sensor detection, calibration, and stationary cursor behavior checked.
- [ ] Cursor movement and direction checked on both axes.
- [ ] Left click, right click, and click-and-drag checked.
- [ ] Scroll up and scroll down checked.
- [ ] Bluetooth pairing and reconnection after restart checked.

## Known limitations

<!-- Describe remaining problems, untested behavior, or follow-up work. Write "None known" if appropriate. -->
