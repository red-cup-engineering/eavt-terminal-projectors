# @red-cup-engineering/eavt-terminal-projectors

<!-- 561-group-standards:badges:start -->
[![Red Cup Engineering](https://img.shields.io/badge/561%20Group-Red%20Cup%20Engineering-c0392b)](https://github.com/red-cup-engineering)
[![License: MIT](https://img.shields.io/badge/license-MIT-c0392b)](LICENSE)
[![Indigenous data: CARE](https://img.shields.io/badge/Indigenous%20data-CARE-4b6f44)](https://github.com/red-cup-engineering/.github/blob/main/GOVERNANCE.md)
[![Tips welcome](https://img.shields.io/badge/tips-welcome-d4a017)](https://github.com/561-group/.github/blob/main/TIPS.md)
<!-- 561-group-standards:badges:end -->

Domain projections from an EAVT settled section into terminal cell frames and raster framebuffers.

This package owns the EAVT-specific interpretation: affirmed, denied, contradicted, and pending
predications become visible rows or bands. It owns neither terminal lifecycle nor rendering:
`@red-cup-engineering/arnold` composes and renders cell scenes, while
`@red-cup-engineering/daleske` encodes and blits raster frames.

```js
import { projectFiber } from "@red-cup-engineering/eavt-terminal-projectors/cell";
import { project } from "@red-cup-engineering/eavt-terminal-projectors/raster";
```
