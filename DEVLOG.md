
# Project Snoopy — Development Log

This document tracks the development of Snoopy Flying Ace
Recompiled, including progress, discoveries, and challenges.

---

## Session 1 — November 13, 2026

### Objective
Establish the development environment and create the
foundation for the Snoopy Flying Ace recompilation project.

### Completed
- Installed and verified development tools on CachyOS.
- Verified GCC, Clang, CMake, Ninja, Python, GDB, and Git.
- Installed GitHub CLI.
- Authenticated GitHub CLI.
- Created the public GitHub repository.
- Configured Git author identity.
- Created ROADMAP.md with six development phases.
- Committed and pushed the initial roadmap.

### Technical Discoveries
- The original game was released for Xbox 360 XBLA.
- Xbox 360 uses a PowerPC-based CPU architecture.
- Modern Windows and Linux PCs typically use x86-64.
- Static recompilation may provide a path toward native
  execution, but compatibility has not been established.

### Current Status
Phase 1 — Development Environment & Fundamentals

Initial environment setup complete.

### Next Steps
1. Learn the fundamentals of Xbox 360 PowerPC architecture.
2. Understand how static recompilation works.
3. Investigate the ReXGlue toolchain.
4. Identify the format of the game's executable.
5. Establish the technical feasibility of recompilation.

### Known Challenges
- Game executable structure has not been analyzed.
- ReXGlue compatibility is unknown.
- Xbox 360 system dependencies have not been identified.
- Graphics, audio, input, and networking requirements
  remain unknown.

### Notes
This is an educational preservation project.

The repository will contain original project code,
documentation, and tooling, but no proprietary game files.

---
