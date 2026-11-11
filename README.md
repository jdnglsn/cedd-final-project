# CEDD Air Mouse

Arduino project for an ESP32 and MPU6050 Bluetooth air mouse.

## Status

Repository setup only. `CEDD/CEDD.ino` is intentionally empty; firmware has
not been implemented, compiled, or tested on hardware.

## Project layout

```text
CEDD/
  CEDD.ino       Arduino sketch (empty placeholder)
.gitignore      Generated files and local configuration exclusions
.gitattributes  Consistent text line endings
AGENTS.md       Contributor/agent workflow
README.md       Project setup and status
```

## Open the project

1. Clone this repository and select the development branch:

   ```sh
   git clone --branch dev https://github.com/jdnglsn/cedd-final-project.git
   cd cedd-final-project
   ```

2. In Arduino IDE, open `CEDD/CEDD.ino` inside this repository.
3. Keep the sketch inside the `CEDD` folder so Arduino's sketch naming
   requirement remains satisfied.

The empty placeholder is not an uploadable program yet. Board settings,
library versions, and wiring will be documented when firmware is added.

## Planned hardware

- ESP32 development board based on ESP-WROOM-32
- MPU6050 motion sensor breakout
- Four momentary buttons for left click, right click, and scrolling
- Bluetooth-capable computer, USB data cable, and prototype wiring

## Development workflow

All changes must be committed to `dev` first. Do not commit directly to `main`.
Use small, coherent commits with Conventional Commit messages:

```sh
git switch dev
git pull --ff-only origin dev
# Make and review a coherent change.
git add <changed-files>
git commit -m "docs: update project setup"
git push origin dev
```

Use `feat:` for new functionality, `fix:` for corrections, `docs:` for
documentation, and `chore:` for repository maintenance. Integration into
`main` should happen through a reviewed pull request from `dev`.

Do not commit generated binaries, build directories, credentials, or local
machine configuration. Keep example configuration free of secrets.

## Reference

The planned design is informed by
[Circuit Forge's Air Mouse project](https://github.com/udit1567/Circuit_forge/tree/main/Air%20Mouse),
particularly its ESP32 BLE version. No upstream firmware is included at this stage.
