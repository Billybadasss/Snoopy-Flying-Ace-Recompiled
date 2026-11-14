
# Snoopy Flying Ace — Native PC Recompilation

## Project Mission

Preserve Snoopy Flying Ace (Xbox 360 XBLA) by investigating
the feasibility of creating a native Windows and Linux port
through static recompilation.

Our ultimate goal is to restore the complete gameplay
experience, including online multiplayer if technically feasible.

This is an independent, educational preservation project.

## Phase 1 — Development Environment & Fundamentals

Status: IN PROGRESS

- [x] Install and verify development tools
- [x] Install GitHub CLI
- [x] Authenticate with GitHub
- [x] Create GitHub repository
- [ ] Establish project documentation
- [ ] Learn Xbox 360 PowerPC architecture
- [ ] Study static recompilation and ReXGlue
- [ ] Identify the tools needed for game analysis

Milestone: Understand the toolchain and have a documented
development environment.

## Phase 2 — Game Analysis

Status: NOT STARTED

- [ ] Identify the game's executable format
- [ ] Inspect a legally obtained XBLA package
- [ ] Identify imported functions and system dependencies
- [ ] Investigate graphics, audio, input, and networking
- [ ] Assess compatibility with ReXGlue
- [ ] Document technical risks and blockers

Milestone: Determine whether static recompilation is a
realistic approach.

## Phase 3 — Recompilation Proof of Concept

Status: NOT STARTED

- [ ] Configure an experimental recompilation toolchain
- [ ] Analyze PowerPC executable code
- [ ] Attempt recompilation of a small code region
- [ ] Investigate runtime and Xbox 360 API requirements
- [ ] Validate the generated native code

Milestone: Demonstrate a technically meaningful
recompilation result.

## Phase 4 — Native Single-Player

Status: NOT STARTED

- [ ] Investigate native executable startup
- [ ] Implement or adapt required runtime functionality
- [ ] Investigate graphics rendering
- [ ] Investigate controller and keyboard input
- [ ] Investigate audio playback
- [ ] Test gameplay and stability
- [ ] Evaluate Windows and Linux compatibility

Milestone: Achieve playable native single-player gameplay,
if technically feasible.

## Phase 5 — Multiplayer Restoration

Status: NOT STARTED

- [ ] Analyze the game's networking architecture
- [ ] Identify Xbox Live dependencies
- [ ] Investigate replacement networking services
- [ ] Test local multiplayer where applicable
- [ ] Investigate online session creation and joining
- [ ] Test synchronization and gameplay stability

Milestone: Restore functional multiplayer if technically
and legally feasible.

## Phase 6 — Testing, Documentation & Release

Status: NOT STARTED

- [ ] Establish reproducible builds
- [ ] Document installation and configuration
- [ ] Test supported operating systems
- [ ] Document known issues
- [ ] Establish a lawful asset-loading approach
- [ ] Prepare a public release if the project succeeds

Milestone: Deliver a documented, usable preservation
project without distributing proprietary game assets.

## Development Principles

1. Learn and document each major technical decision.
2. Work in small, testable increments.
3. Keep the repository free of copyrighted game assets.
4. Record blockers rather than hiding or bypassing them.
5. Prioritize technical feasibility before promising features.
6. Preserve progress through Git commits.

## Project Documentation

- ROADMAP.md — Goals, phases, and milestones
- DEVLOG.md — Chronological development progress
- BLOCKERS.md — Technical obstacles and investigations
- LEARNING.md — Concepts, commands, and lessons learned

## Current Focus

Complete Phase 1, then begin identifying the game's
executable format and evaluating the recompilation toolchain.
