# Rationale for Rakuraku-Kii Layout

## Introduction

The Rakuraku-Kii layout is designed to alleviate wrist pain while maintaining productivity. It addresses frustrations with traditional keyboards by exploring ergonomic options, such as split designs and reduced key travel. The base layout uses Colemak-DH for less finger movement and strain compared to QWERTY. With fewer keys available than a full 100% keyboard, every placement is strategic, drawing initial inspiration from Miryoku's layered approach with custom tweaks.

This document explains the design decisions behind the 36-key configuration (3×5 matrix + 3 thumbs per side), focusing on ergonomics, practicality, and efficiency.

---

## Design Philosophy

### Ergonomics First
Wrist pain drove the core choices:
- **Split Design**: Separating the keyboard halves reduces ulnar deviation and promotes neutral wrist positioning.
- **Colemak-DH Base**: Prioritizes common letters on the home row with minimal travel, lowering strain compared to QWERTY's awkward stretches.
- **Compact Layout**: The 36-key setup eliminates unused keys, encouraging thumb and finger efficiency.

### Layer Efficiency and Practicality
With 36 keys, layers access the full character set without overcrowding the base. Inspired by Miryoku, functionality is divided into clear roles:
- **Thumb-Centric Access**: Layer-taps on thumbs keep the base layer letter-focused, reducing chord complexity.
- **Hand Balance**: Layer access from one hand places most keys on the opposite hand (except home rows), minimizing stretches.
- **Home-Row Mods (HRMs)**: Modifiers (Shift, Ctrl, Alt, Super) on home-row keys (A, R, S, T / N, E, I, O) ensure accessibility. Holding a letter applies the mod, eliminating awkward combos.
- **No Caps Lock**: Removed, as it's unused in modern typing.
- **Vim-Inspired Navigation**: Quick editing and movement without mouse reliance.

The goal is comfort and speed: less travel, predictable placements, and shortcuts for tasks like coding and navigation.

---

## Layer Breakdown

The layout uses 7 layers, accessed via layer-taps on thumbs. Here's the rationale for each:

### DEF (Default/Base Layer)
- **Purpose**: Primary typing layer.
- **Key Decisions**: Colemak-DH placement for letters. Easy access to quotes (single/double), comma, dot, question mark/forward slash. Thumbs: Esc, Tab, Enter, Space, Backspace, Delete for utilization.
- **Why?**: Keeps letters uninterrupted, with essentials nearby to avoid layer switches mid-word.

### NAV (Navigation Layer)
- **Purpose**: Movement, editing, and shortcuts.
- **Key Decisions**: H, J, K, L in standard QWERTY positions for vim navigation. Arrows mirror this (Left/Down/Up/Right), with Page Up/Down and Home/End for extended movement. Editing combos: Undo (Ctrl+Z), Paste (Ctrl+V), Copy (Ctrl+C), Cut (Ctrl+X), Redo (Ctrl+Y), Select All (Ctrl+A).
- **Why?**: Vim-style for efficient text editing without leaving the keyboard. Combos are "nice-to-have" for quick actions in editors/IDEs.

### NUM (Numbers Layer)
- **Purpose**: Numbers and math operations.
- **Key Decisions**: Numpad-style layout (7-9, 4-6, 1-3, 0 under thumb) with operators (+, -, *, /) and parentheses for calculations. Includes switch to FUN layer.
- **Why?**: Mimics physical numpads for familiarity. Math keys enable quick calculations without layer hopping (e.g., `1+2*3` directly). FUN access keeps related functions (F1-F12) tied to numbers.

### SYM (Symbols Layer)
- **Purpose**: Special characters and punctuation.
- **Key Decisions**: Aligned with NUM for consistency. Majority of used symbols on one layer for ease of access.
- **Why?**: Symbol placement matches numbers for muscle memory. Balances hand load without overcrowding.

### MOUSE (Mouse Layer)
- **Purpose**: Keyboard mouse control.
- **Key Decisions**: Directional movement (wheel left/up/right/down), clicks (1/2/3), and mods (Shift/Ctrl/Alt/Super for selections/drags).
- **Why?**: Backup for mouse-less work, though rarely used. Keeps layout complete for versatility.

### MEDIA (Media Layer)
- **Purpose**: Audio/visual controls.
- **Key Decisions**: Brightness up/down, volume controls, play/pause/stop, mute.
- **Why?**: Essential for media without external controls. Simple and intuitive.

### FUN (Function Layer)
- **Purpose**: F-keys and mods.
- **Key Decisions**: F1-F12 aligned with numbers (e.g., F7 where 7 is), with mods (LShift/Ctrl/Alt/Super) and access to other layers.
- **Why?**: Ties function keys to their numeric counterparts for consistency. Mods allow complex shortcuts.

## Key Placement Decisions

- **Hand Balance and Stretching Avoidance**: Layer access from left hand → right-hand keys (and vice versa) prevents cross-body reaches. HRMs enable one-handed mod + key combos, reducing strain.
- **Thumb Utilization**: Layer-taps (for layer access) and keys like Space, Enter, Esc, Backspace, and media controls leverage thumbs for repetitive actions without finger fatigue.
- **Workflow Fit**: Prioritized vim editing and calculations.
- **Predictability**: Symbols mirror numbers; navigation follows vim conventions; everything is "where the hands already are."

## Tradeoffs and Evolution

The 36-key setup simplified the layout by focusing on essentials, reducing clutter. Benefits: Less physical space, fewer unused keys, and clearer ergonomics. Downsides: More reliance on layers, potential for layer-hopping fatigue (mitigated by thumb access). This keeps the config universal and personal.

This layout prioritizes comfort, efficiency, and pain reduction. Adapt it as needed.</content>
<parameter name="filePath">docs/rationale.md