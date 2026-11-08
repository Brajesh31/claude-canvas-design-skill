# claude-canvas-design-skill

A Claude Code skill for developing original visual concepts and expressing them through polished static compositions.

## Overview

This skill treats visual design as a process of forming a clear aesthetic direction before producing the final artifact. It helps translate a brief into a visual philosophy, then express that philosophy through composition, shape, color, typography, imagery, and carefully limited text.

The intended outputs are static visual documents such as PNG images and PDF compositions, along with supporting written design rationale where required.

## Design Process

### 1. Understand the Brief

Identify the subject, intended audience, emotional tone, constraints, and practical use of the final artifact. Treat the brief as a foundation rather than a rigid layout.

### 2. Develop a Visual Philosophy

Define the central idea behind the design. Consider:

- Form and geometry.
- Negative space and composition.
- Color relationships.
- Texture and pattern.
- Image treatment and visual rhythm.
- Typography and hierarchy.
- The relationship between visual elements and essential text.

### 3. Translate the Philosophy into a Composition

Create a coherent visual system. Establish hierarchy, balance, focal points, and spacing before adding decorative details.

### 4. Produce the Artifact

Create the final visual output in the requested format. Keep the design original and avoid copying an existing artist's distinctive work.

### 5. Review and Refine

Check visual balance, legibility, export quality, and consistency with the brief.

## What It Helps Create

- Posters and editorial compositions.
- Static visual artwork.
- Concept-driven design studies.
- Branded visual assets.
- PDF and PNG design deliverables.
- Visual explorations with a written design rationale.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-canvas-design-skill.git ~/.claude/skills/canvas-design
```

This repository includes bundled font assets. Their accompanying license notices are retained alongside the relevant assets. Do not remove those notices while keeping the corresponding font files.

## Usage

Invoke the skill for a static design task:

```text
/canvas-design
```

Describe the subject, intended format, dimensions or aspect ratio, audience, and any required text. If the user has not specified a visual direction, develop an appropriate concept rather than defaulting to a generic template.

## Composition Checklist

- One clear visual idea anchors the design.
- The focal point is immediately understandable.
- Negative space supports the hierarchy.
- Typography is legible at the intended size.
- Color choices reinforce the concept.
- Visual elements feel like one coherent system.
- Essential text is limited and correctly placed.
- The composition remains balanced at final dimensions.

## Export and Quality

- Export the requested PNG or PDF format.
- Check dimensions and resolution.
- Inspect text rendering and font availability.
- Confirm that no elements are clipped.
- Review the final file at its intended display size.
- Keep editable source material when the workflow requires future revisions.

## Repository Contents

- `SKILL.md`: Main design philosophy and production workflow.
- `canvas-fonts/`: Bundled font assets and their accompanying license notices.
- `README.md`: Design process, installation, and quality checklist.

## Design Standard

A polished composition is not defined by the number of effects or elements. Every major visual decision should reinforce the concept. Remove details that do not improve communication or visual meaning.
