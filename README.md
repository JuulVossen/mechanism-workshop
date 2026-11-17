# The Mechanism Workshop

**[Compare Chapter 2 in Phaser](https://juulvossen.github.io/mechanism-workshop/puzzle-workshop/?puzzle=puzzle-02&engine=phaser)** with the **[original React/SVG version](https://juulvossen.github.io/mechanism-workshop/puzzle-workshop/?puzzle=puzzle-02&engine=react)**. Both use the same story artwork. The Phaser tabletop supports free placement, continuous rotation, explicit nearby-edge joining, movable partial assemblies, zoom, pan, undo/redo and a route reveal. Pieces remain where they are dropped. The two versions keep separate browser-local arrangements; use the switches above the puzzle to compare. This is a comparison of interaction designs, not an engine speed benchmark. Phaser's MIT notice is included in the workshop distribution.

[Open the workshop in your browser](https://juulvossen.github.io/mechanism-workshop/).

[Open the story puzzle workshop](https://juulvossen.github.io/mechanism-workshop/puzzle-workshop/) to play and refine all ten chapters of *The Street Between Maps*, inspect their artwork and clues, or import a pack for another story. The story workshop includes English and Dutch, a two-puzzle starter pack, JSON editing, and browser-local test saves. Export packs and sessions to share or transfer your work. Uploaded image attachments stay in the browser session.

The `puzzle-workshop/` directory is a separate static build with only its declared artwork and public story packs. Its `publication.json` records packaged file hashes. Both workshops link to each other. Updating one build should preserve the other directory and the navigation in the root `index.html`.

**[Try the illustrated Chapter 2](https://juulvossen.github.io/mechanism-workshop/puzzle-workshop/?puzzle=puzzle-02):** move and turn actual illustrated paper fragments on Mara's workbench, place the separate river strip, inspect the paper closely and trace a continuous passage. This is the first finished visual example; the other nine chapters retain the earlier authoring presentation. The original artwork is preserved, and the new fragments share one coherent illustrated master. Keyboard and tap alternatives, undo and isolated test saves remain available.

Thirty-five interactive puzzle prototypes, grouped into six related families. Choose a family to explore its mechanisms, use **Show all groups** for the complete overview, or search across all 35 by name, number or group.

## Locks & moving parts · 6 mechanisms

Turn, slide, combine and balance physical pieces.

- Combination locks with number and symbol wheels and a pull latch.
- Sliding bolts with movement limits, blockers, interlocks and undo.
- Mechanical construction with coupled gears, a counterweight, a catch and a drawer bolt.
- A tactile lock with linked pins, a locking collar and a pull handle.
- Object combinations with orientation rules, new composites and chained recipes.
- A rolling seal with optional phone tilt, an on-screen joystick and keyboard nudges.

## Paper & hidden layers · 6 mechanisms

Rearrange documents and uncover content beneath their surfaces.

- Transparent tracing alignment with rotation, scale and opacity controls.
- Document layers that can be lifted, turned, placed and replaced.
- Torn-document reconstruction with snapping, rotation and optional flipping.
- Folding and unfolding with previews, reversible layer order and face/orientation goals.
- Scratching to reveal with persistent masks and separate clue-region coverage.
- Hidden ink with a movable UV lamp and persistent heat development.

## Light & perspective · 6 mechanisms

Use optics, alignment and your viewing position to find a solution.

- Light, negative and filters with channel selection, exposure, contrast and inversion.
- Perspective correction with four movable corners and a live projective preview.
- Mirror simulation with real reflected ray paths and receiver goals.
- Perspective hunting with a movable, capturable viewpoint and projected reference landmarks.
- Parallax alignment between fragments at different depths.
- Embodied vectors with a simulated standing area and geometric alignment conditions.

## Patterns, codes & memory · 6 mechanisms

Recognise shapes, decode relationships and remember patterns.

- Rotating cipher rings with symbol seals and an alphabet decoder.
- Audio patterns with playable fragments, speed/filter controls and a sound-free pulse score.
- Visual memory with timed observation, ornament reconstruction and untimed/repeat aids.
- Visual grammar inferred from examples and applied to a new facade.
- Negative-space recognition with rotated and reflected silhouettes.
- Architectural rhythm anomalies supported by construction traces.

## Logic & routes · 4 mechanisms

Combine constraints to place objects, trace routes or locate a destination.

- Logical assembly with placement clues, draggable artifacts and reversible slot swaps.
- Topological routes with continuous loops, edge counts and broken joins.
- Architectural constraints with draggable seals and evaluated placement rules.
- Multi-location inference with collected constraints, map overlays and a movable pin.

## Evidence & interpretation · 7 mechanisms

Compare observations, reconstruct events and justify conclusions.

- Altered-image comparison with wipe/side-by-side views and revisable discrepancy marks.
- An evidence board with source excerpts, revisable judgments and alternative accepted proofs.
- Building stratigraphy with trace attribution and relative chronology.
- Evidence appraisal with a supported verdict and decisive citations.
- Forger signatures classified from recurring changes across locations.
- Delayed meaning with an unchanged saved observation and later context.
- Cross-facade analogy with paired before/after evidence.

## Testing and publication

Each document, paper, instrument, deduction/tactile, reveal/audio/combination, simulation/motion/memory and facade/location mechanic has two variations, explicit completion checks, undo/reset and test-solution aids. The prototypes support pointer and keyboard controls; interactive SVG canvases also support touch drags. Test state stays in memory across study tabs; reloading starts a fresh session. Artwork is original fiction. Audio patterns are generated in the browser and play only on request. Device tilt is opt-in; on-screen controls always remain available.

This repository contains only the compiled browser preview. GitHub Pages publishes the root of `main`; updating the generated files triggers a new deployment.

Current build: 35 studies in six related groups, 17 November 2026.

All 35 catalogue entries now have prototypes: six foundational interactions, 15 in-app mechanisms, and 14 facade/location mechanisms. The location studies use original fictional scenes and browser simulations; camera/GPS and real-site story integration are separate work. Physical phone sensors still need a device check; desktop and touch-emulated browser flows are verified.
