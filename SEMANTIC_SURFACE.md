# Orbital Construction

Orbital Construction is an executable investigation into how a small vocabulary of semantically meaningful construction parts can compose into rich orbital facilities.

The project is not primarily a station model, a kitbash library, or a procedural station generator.

It is a laboratory for discovering **construction vocabulary through executable evidence**.

The current artifact asks:

> Can a small set of semantic construction families produce materially different, rich orbital facilities, while every component is complete when unattached and every connection remains explicit?

## Start With the Artifact

`index.html` is the authoritative executable and the deepest semantic record of the project.

Run it. Inspect it. Manipulate it.

The artifact contains its own current semantic contract as well as the archaeology that records how earlier mechanisms were discovered, revised, rejected, or preserved.

This document is an orientation surface. It does not replace the artifact's embedded semantics.

## What Exists

The current E2 construction vocabulary contains **37 named module kinds across seven realization families**:

- junctions
- pressure modules
- habitation
- work platforms
- structure
- machines
- terminations

Three larger compositions exercise the same vocabulary in substantially different ways:

- an accreted habitation complex
- an orbital construction yard
- a radial junction network

A single-module bench allows every catalog kind to be inspected independently.

The earlier Orbital Construction lineage also remains present as archaeology, including the original station, Room 001, Pallet Lander 001, its cargo and containment machinery, and Orrery Seed 001.

These older systems are not dead prototypes to be cleaned away. They are evidence.

## The Central Construction Rule

A module should be meaningful and physically legible **before another module is attached to it**.

A pressure module therefore owns its own finished pressure boundary. An unused pressure interface has an intrinsic isolation hatch rather than requiring an anonymous cap to hide an unfinished hole.

Connections are explicit semantic interfaces.

Ports carry position, orientation, interface family, size, occupancy, and a canonical local frame. Connections are produced by aligning those interfaces—not by discovering topology from overlapping meshes.

The exterior assembly graph describes sealed physical construction relationships. It does **not** claim to be an interior floor plan, pressure-flow simulation, or generalized structural solver.

## What the Project Has Learned

Several mechanisms have earned significance beyond any particular station composition.

### Envelope before decoration

Construction detail follows the geometry and function of the thing it belongs to.

Round pressure vessels and rectangular workshops do not receive the same framing grammar. Service routes, frame bands, mounting offsets, windows, and detail placement consume the module's actual envelope.

When a representation fails structurally, replace the representation rather than disguising the failure with additional detail.

### Interfaces own their space

A connection is more than a point.

Ports, collars, fastening hardware, exclusion regions, platform openings, and receiving geometry together define an interface corridor. Generated detail is not allowed to occupy that space merely because an exposed surface happens to be available.

### Detail has frequency

Useful visual complexity appears at several scales:

**Primary:** pressure volumes, frames, open spans, major machinery.

**Middle:** ribs, braces, window bays, rails, routed services.

**Fine:** panels, fasteners, material variation, wear and directional marks.

Optional detail should enrich an already meaningful object. Turning Detail off must not destroy the object's structural or functional reading.

### Surface is not form

Procedural surface treatment is independent of physical construction.

Texture may provide panel rhythm, seams, plate variation, fastener fields and restrained wear, but beams remain beams, windows remain geometry, cables remain cables, and pressure envelopes remain physical form.

Turning Texture off should reveal a simpler manufactured object—not reveal that the object was an illusion.

### Ownership matters

Modules remain semantic objects even when their render geometry is batched.

Generated geometry retains module ownership, material region, and construction layer. Selection and inspection operate on semantic owners rather than anonymous triangles.

Optimization should not erase meaning.

### Composition is a test

The supplied stations are not privileged authored scenes.

They are programs that assemble the same vocabulary.

Their value is evidence that the vocabulary can produce materially different organizations without requiring a bespoke generator for every desired station.

## Interaction Is Part of the Experiment

The exterior is meant to be inspected directly.

Orbit, pan, pinch, selection, isolation, attachment, detachment, rolling and branch movement allow construction relationships to be examined rather than merely viewed.

Observer state and world state remain distinct. Moving the camera does not move the world. Assembly edits preserve the observer where possible.

`Home` is an explicit request to reframe.

The interior preserves its own earlier situated-camera experiment rather than being generalized into the new module system without evidence.

## Deliberate Non-Capabilities

Orbital Construction currently does **not** claim:

- global collision-aware station layout
- automatic service routing
- structural load simulation
- pressure-flow simulation
- cyclic or multi-anchor constraint solving
- generalized interiors for every pressure module
- articulated crane operation
- physically simulated cargo handling
- unlimited assembly scale

A locally valid connection may still cause one branch to intersect unrelated nearby architecture.

That is a known boundary, not evidence that a hidden general solver exists.

## How to Extend It

Prefer the smallest executable change that can answer a question.

Do not expand the catalog merely because another station part can be imagined.

Instead ask what current construction cannot express.

Use the single-module bench and unfamiliar recombinations to expose missing vocabulary. If several objects independently require the same concept, that may be evidence that the concept deserves promotion.

If only one object needs peculiar behavior, let that behavior remain local.

Preserve successful mechanisms while remaining willing to replace weak implementations.

Most importantly:

**let behavior earn architecture.**

## Semantic Authority

There are two useful layers of project truth.

**This Markdown surface** explains what the project is, how to approach it, and the principles needed to continue it coherently.

**The executable artifact** contains the detailed present-tense implementation contract, ownership rules, measured constraints, validation evidence, failure diagnostics, and the complete retained development archaeology.

When implementation changes materially alter what the project means, update the present-tense semantic record rather than allowing obsolete descriptions to accumulate as current truth.

Preserve consequential failures and earlier discoveries as archaeology.

## Current Frontier

The current artifact suggests several possible next investigations without choosing one in advance:

stronger local surface routing, collision-aware branch placement, more consequential articulated machinery, or unfamiliar compositions that expose vocabulary the existing catalog cannot express.

The next abstraction should come from executable pressure.

Not from anticipation.

---

**Build evidence. Promote what earns meaning. Preserve enough of the path that the next human or model can continue the investigation rather than reconstruct it.**
