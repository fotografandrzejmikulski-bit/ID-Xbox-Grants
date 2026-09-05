# Xbox / Windows Release Plan

## Release principle

The project will only claim platform capabilities that are implemented, tested and supported by the applicable current Microsoft publishing process.

## Capability matrix

| Capability | Plan | Evidence required before claim |
|---|---|---|
| Xbox Series X|S | Target | Successful target-hardware test set |
| Windows PC | Target | PC build and requirements matrix |
| Xbox Play Anywhere | Candidate | Confirm title eligibility + ship/test required packages |
| Cloud saves | Candidate | Implemented service + edge-case tests |
| Achievements | Candidate | Implemented achievement set + platform validation |
| Controller support | Target | Input and disconnect/reconnect test matrix |
| Accessibility features | Target | Feature inventory + test evidence |
| 4K / HDR / other visual capabilities | Optional | Measured and supported by actual build |

Microsoft's current Partner Center publishing guidance lists technical capabilities such as Optimized for Xbox Series X|S, 4K and Xbox Play Anywhere and Xbox services such as achievements and cloud saves. It explicitly advises configuring only the capabilities the game actually supports. citeturn229269search12turn229269search13

## Packaging

For Xbox Play Anywhere, current Microsoft documentation states that both an XVC console package and an MSIXVC PC package are created. citeturn229269search16

## QA gates

### Gate A — Platform prototype

- package creation succeeds,
- application boots reliably,
- controller input works,
- user state is stable,
- logging and diagnostics are available.

### Gate B — Feature complete

- all target platform services are integrated,
- accessibility feature inventory is complete,
- memory/performance targets are measured,
- critical save/error cases pass.

### Gate C — Release candidate

- no known release blockers,
- store metadata is accurate,
- supported capabilities match actual build behavior,
- test evidence is archived,
- submission package is reproducible.

## Store and marketing claims

Store copy must never promise features that are merely planned. The final product detail page should be generated from the verified capability matrix and final accessibility inventory.
