# Verification Matrix

| ID | Claim / topic | Status | Required evidence / action |
|---|---|---|---|
| V-01 | DAP exists and supports the intended creator/project profile | CONFIRMED | Microsoft publicly describes DAP and its mission; eligibility details for this specific application still require current program review |
| V-02 | Maximum grant amount is USD 400,000 | VERIFY | Current official program terms; do not describe as a limit until confirmed |
| V-03 | DAP has offered non-recoupable funding to offset porting costs | CONFIRMED | Microsoft DAP announcement supports this general statement |
| V-04 | Funding has no equity requirement | VERIFY | Current program terms / agreement |
| V-05 | Funding does not impose Xbox exclusivity | VERIFY | Current agreement / program documentation |
| V-06 | Xbox Play Anywhere is available for this title | VERIFY | Current publishing/program requirements and title eligibility |
| V-07 | Game Pass Day One is a realistic commercial option | VERIFY | Current business/deal process; treat as negotiation, not entitlement |
| V-08 | Current accessibility guidance version is XAG V3.2 | CONFIRMED | Current Microsoft Learn accessibility page |
| V-09 | XAG 101/102/105/106/107/108/123 descriptions match current guidance | VERIFY | Match each claim to the current guideline page before submission |
| V-10 | Exact font sizes 26/52/72/104 px are official requirements | DO NOT ASSERT | Replace with validated requirements or project-specific design targets |
| V-11 | Disabled UI contrast must be exactly 2.5:1 | DO NOT ASSERT | Replace with current accessible-design guidance and scoped project criteria |
| V-12 | Xbox certification checklist contains “400+” requirements | DO NOT ASSERT | Remove unsourced count; use current readiness/certification documentation |
| V-13 | Havok costs USD 25,000 per title | REMOVE / VERIFY | Vendor quote or current licensing terms required |
| V-14 | Xbox memory architecture is described precisely enough for implementation planning | VERIFY | Confirm against current GDK/hardware documentation |
| V-15 | Dev kits are provided on the exact terms described in the source draft | VERIFY | Current ID@Xbox onboarding documentation |
| V-16 | 60 FPS is guaranteed / achievable across all described scenarios | PROJECT TARGET | Use measured acceptance criteria on target hardware |
| V-17 | Launching Friday maximizes New Releases exposure | REMOVE | Unsupported causal claim; present launch timing as a strategy decision |
| V-18 | Microsoft Store traffic peaks on the proposed schedule | REMOVE / SOURCE | Require actual data or remove |
| V-19 | Avoiding launch discounts preserves algorithmic/store value | REMOVE | Speculative; replace with pricing rationale and measured KPIs |
| V-20 | Previous named DAP examples prove specific evaluation preferences | VERIFY | Use official descriptions only; do not infer hidden selection criteria |
| V-21 | Team has 18 members and stated representation profile | VERIFY INTERNALLY | Current roster and appropriate supporting evidence |
| V-22 | Studio is an active limited-liability company | VERIFY INTERNALLY | Current corporate documentation |
| V-23 | Studio has the claimed AAA experience | VERIFY INTERNALLY | CVs / credited releases |
| V-24 | Project uses Unreal Engine 5 | VERIFY INTERNALLY | Current project/build documentation |
| V-25 | Project can reach the proposed release state in 12 months | PROJECT CLAIM | Demonstrate current build state, velocity and critical-path dependencies |

## Current-source observations

Microsoft currently identifies XAG as V3.2 and describes it as best-practice guidance rather than a legal or general compliance checklist. citeturn140189search0

Microsoft's current publishing guidance includes technical capabilities and Xbox services in Partner Center and instructs developers to select only capabilities actually supported by the game. citeturn229269search12turn229269search13

Microsoft's current package documentation states that Xbox console games use XVC, PC games use MSIXVC, and Xbox Play Anywhere titles require both package types. citeturn229269search16

## Writing rule

A `VERIFY` item may appear in the final external submission only after evidence is checked. `DO NOT ASSERT` and `REMOVE` items must not be restored from the source draft unless replaced by precise, supported wording.
