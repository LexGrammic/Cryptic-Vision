# Cryptic Vision Platform Map (V1)

---

## Purpose

This document defines the first verified architectural map of the Cryptic Vision platform.

It is an engineering specification describing the major platform layers, their responsibilities, and their relationships before graphical artwork is produced.

Future visual diagrams should be derived from this specification rather than created independently.

---

# Platform Architecture

```text
                    CRYPTIC VISION

                          USER
                           │
                   Presentation Layer
                           │
      GUI / Terminal / Chat / Avatar / ASCII
                           │
        ┌──────────────────┴──────────────────┐
        │                                     │
 Engineering Instruments            AI Orchestration
        │                                     │
 Pocket Runtime Doctor             Hybrid AI
 Med Bay                           Model Selection
 Surgery Room                      Prompt Routing
 Clone Center                      Memory
        │                                     │
        └──────────────────┬──────────────────┘
                           │
                      State Layer
                           │
             JSON / SQLite / Bridge Files
                           │
                     Runtime Layer
                           │
 Routing
 Permissions
 Ownership
 Events
 Snapshot
 Sandbox
 Compatibility
 Package
 Hotload
 Taste
                           │
                     OGP Governance
                           │
                Windows / Linux (Future)
```

---

# Status

Version:

1.0

Classification:

Draft Engineering Specification

Purpose:

Provide the verified architectural foundation for future platform diagrams.

Future graphical representation:

```
assets/platform_map_v1.png
```

This specification should be reviewed and verified before visual artwork is created.

---

# Layer Responsibilities

## User Layer

Represents the human operator.

The user interacts with Cryptic Vision through presentation systems rather than directly interacting with internal runtime services.

Responsibilities include:

- System operation
- Observation
- Decision making
- Engineering workflow
- Verification

---

## Presentation Layer

Provides every user-facing interface.

Current and planned presentation systems include:

- Graphical User Interface
- Terminal Interface
- Chat Interface
- ASCII Interface
- Animated Avatar
- ESP32 Field Terminal (planned)
- Portable Runtime Interfaces

Presentation remains separate from runtime logic.

Presentation should observe explicit platform state rather than directly controlling engineering systems.

---

## Engineering Instruments

Engineering instruments provide specialized engineering environments built on top of the runtime framework.

Current instruments include:

- Pocket Runtime Doctor
- Med Bay
- Surgery Room
- Clone Center

Future engineering instruments may include:

- Developer Diagnosis
- AI Prompt Machine
- Software Factory
- Additional diagnostic environments

Each instrument has a specific engineering purpose while sharing common platform infrastructure.

---

## AI Orchestration

Coordinates intelligence resources throughout the platform.

Responsibilities include:

- Hybrid AI
- Model selection
- Prompt routing
- Memory coordination
- Tool selection
- AI workflow management
- Future local AI coordination

The orchestration layer determines which intelligence resources should participate in a given engineering task.

---

## State Layer

Provides explicit platform state shared across engineering systems.

Responsibilities include:

- JSON state
- SQLite databases
- Bridge files
- Runtime state
- Patient state
- Persistent memory
- Configuration
- Snapshot metadata

The State Layer allows components to communicate through observable state rather than direct ownership of runtime logic.

This supports one of the core OGP principles:

State is explicit.

---

## Runtime Layer

Provides reusable engineering services shared throughout the platform.

Current runtime families include:

- Routing Runtime
- Permissions Runtime
- Ownership Runtime
- Event Runtime
- Snapshot Runtime
- Sandbox Runtime
- Compatibility Runtime
- Package Runtime
- Hotload Runtime
- Taste Runtime

Future runtimes may be added as the platform expands.

Engineering instruments consume runtime services rather than reimplementing them.

---

## Governance Layer

Provides engineering governance.

Current governance is based on:

Occult Grammar Protocol

OGP

Core Law

Environment

↓

Verify

↓

Execute

↓

Expand

Responsibilities include:

- Verification-first engineering
- Observation before modification
- Expansion control
- Stable system preservation
- Explicit engineering workflow
- Controlled experimentation

The Governance Layer influences every other platform layer.

---

## Operating Environment

Provides the underlying computing environment.

Current supported environment:

- Windows

Future direction:

- Linux-based Cryptic Vision operating environment

Operating environments provide:

- Hardware access
- Filesystems
- Process management
- Networking
- Device support

Cryptic Vision provides engineering capability on top of the operating environment.

---

# Architectural Principles

The platform follows several architectural principles.

Presentation remains separate from engineering logic.

Engineering instruments consume shared runtime services.

State remains explicit.

Runtimes remain modular.

Governance applies across every layer.

Expansion occurs only after verification.

New engineering instruments should reuse existing platform services whenever possible.

---

# Platform Flow

Conceptually the platform operates as:

```text
User

↓

Presentation

↓

Engineering Instrument

↓

AI Orchestration

↓

State

↓

Runtime Services

↓

Governance

↓

Operating Environment
```

Each layer performs a specific responsibility while remaining independent from presentation whenever practical.

---

# Verification Status

Current document status:

✔ Initial platform architecture defined

✔ Platform layers identified

✔ Layer responsibilities documented

✔ Runtime relationships documented

✔ Governance placement verified

Next milestone:

Produce

```
assets/platform_map_v1.png
```

using this specification as the canonical engineering reference.

---

LexGrammic

Alchemotype Division

Cryptic Vision

Platform Architecture Specification V1
