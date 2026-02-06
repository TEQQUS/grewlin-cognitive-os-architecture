# Cognitive OS Kernel – Architecture Diagram

This repository contains the reference architecture diagram for the
**Grewlin Cognitive Operating System (Cognitive OS)**.

The diagram illustrates how external and internal inputs—originating from
models, agents, users, sensors, or services—are interpreted into **proposed
state deltas**, validated by a deterministic kernel, committed to an
authoritative **canonical cognitive state**, and used to authorize execution.

Reasoning components may propose change, but only the **Cognitive OS Kernel**
can validate and commit belief or action. Execution is strictly downstream of
validated state.

This separation between **reasoning and authority** enables predictable,
inspectable, and governable autonomy over long horizons, independent of
specific models or agents.

---

## Diagram files

- `cognitive-os-kernel.png` — raster version for broad compatibility
- `cognitive-os-kernel.svg` — vector reference version

The PNG is intended for direct embedding on websites and documents.
The SVG is provided as the canonical, high-fidelity reference artifact.

---

## Primary reference

- Grewlin homepage: https://grewlin.no

---

## Related material

- Cognitive OS Whitepaper  
  https://grewlin.no/onewebmedia/CognitiveOS_K_Martin_Lorentzon.pdf

- Mars lander state reasoning example  
  https://grewlin.no/research-publication/mars-lander

- Governance and regulated autonomy  
  https://grewlin.no/governance

- Research & publications index  
  https://grewlin.no/research-publication/

---

© Grewlin. All rights reserved.  
Provided for reference and discussion.
