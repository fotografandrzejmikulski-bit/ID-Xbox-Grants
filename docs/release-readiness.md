# Release Readiness Checklist

## Product

- [ ] Core gameplay loop is complete.
- [ ] Vertical Slice represents final intended quality.
- [ ] Critical progression paths have no blocker defects.
- [ ] Save/load state is deterministic and resilient to failure.

## Xbox / Windows

- [ ] Current Microsoft publishing guidance reviewed.
- [ ] Target hardware matrix defined.
- [ ] Package types and packaging pipeline validated.
- [ ] Platform capabilities match actual implementation.
- [ ] User/profile states tested.
- [ ] Offline/online transitions tested where applicable.
- [ ] Controller disconnect/reconnect scenarios tested.
- [ ] Error states have user-facing recovery paths.

## Accessibility

- [ ] Accessibility feature inventory completed.
- [ ] Text display reviewed against current XAG guidance.
- [ ] UI focus behavior reviewed.
- [ ] Audio alternatives reviewed.
- [ ] Screen narration scope assessed.
- [ ] Input options assessed.
- [ ] Motion/photosensitivity settings reviewed.
- [ ] Accessibility playtests completed.
- [ ] Public accessibility feature documentation prepared.

## Performance

- [ ] CPU frame-time budget measured.
- [ ] GPU frame-time budget measured.
- [ ] Memory high-water marks recorded.
- [ ] Loading/stutter scenarios profiled.
- [ ] Long-session stability tested.
- [ ] Crash/hang telemetry reviewed.

## Store / publishing

- [ ] Basic info is accurate.
- [ ] Technical capabilities reflect the shipped build.
- [ ] Xbox services reflect the shipped build.
- [ ] PC minimum/recommended specifications are validated.
- [ ] Accessibility information matches the shipped product.
- [ ] Store media meets current requirements.
- [ ] Rating / legal / privacy materials completed.

## Grant close-out evidence

- [ ] Spend mapped to approved workstreams.
- [ ] Milestones have objective evidence.
- [ ] Major risks have disposition.
- [ ] Final build and release candidate are archived.
- [ ] Deviations from the original plan are documented.
