# Accessibility Plan — „Pieśń Zapomnianych”

## Source position

Microsoft currently publishes Xbox Accessibility Guidelines (XAG) as best-practice guidance. The current Microsoft Learn page identifies the material as **XAG V3.2**, with the page updated in 2026. The guidelines are explicitly described as guidance for designers, developers and test teams, not as a legal-compliance checklist. citeturn140189search0

## Project strategy

Accessibility must be designed into the gameplay and UI architecture from the prototype stage. The project's music- and rhythm-driven mechanics require particular attention because critical information may otherwise depend on timing and audio perception.

## Planned feature groups

### Text and UI

- configurable text size,
- readable typography and spacing,
- clear focus treatment,
- consistent UI hierarchy,
- high-contrast presentation where appropriate,
- avoid communicating critical state by color alone.

Microsoft's XAG material covers text display under XAG 101 and UI focus handling under XAG 113. citeturn140189search2turn140189search4

### Audio and visual alternatives

- subtitles and captions,
- visual alternatives for critical audio/tempo cues,
- independent audio mixing controls where useful,
- screen narration for appropriate UI flows,
- consideration of players who cannot rely on hearing.

Microsoft identifies screen narration under XAG 106 and audio accessibility under XAG 105. citeturn140189search5turn140189search0

### Input and motor accessibility

- configurable input where technically appropriate,
- sensible remapping architecture,
- reduced reliance on simultaneous or highly time-sensitive input,
- adjustable timing windows for rhythm-based actions,
- support for appropriate controller accessibility features.

XAG 107 addresses input and XAG 108 addresses game difficulty options. citeturn140189search0

### Motion and photosensitivity

- camera shake reduction,
- motion effects controls,
- photosensitivity safeguards,
- avoidance of unnecessary flashing or high-frequency visual effects,
- pause/resume behavior designed around accessibility needs.

Microsoft identifies visual distractions/motion settings under XAG 117 and photosensitivity under XAG 118. citeturn140189search0

### Cognitive accessibility

- explicit objectives,
- persistent progress context,
- understandable feedback,
- reversible settings where feasible,
- predictable UI navigation,
- difficulty and timing options that reduce unnecessary cognitive load.

Microsoft's current XAG catalog includes objective clarity, UI navigation, UI context, time limits and mental-health best practices among the numbered guidelines. citeturn140189search0turn140189search6

## Testing

Accessibility testing will be treated as a continuous QA stream rather than a final audit. Test cycles should include:

1. internal design review,
2. implementation review,
3. playtesting with disabled players where feasible,
4. regression after major UI/gameplay changes,
5. final documentation of supported accessibility features.

XAG 121 specifically addresses accessible feature documentation, including communicating available accessibility features to players before and after purchase. citeturn140189search7

## Claims that are intentionally removed from the application

The previous draft stated specific text sizes, contrast ratios and other numerical values as if they were mandatory Microsoft requirements. Those values are not retained here without a direct source. The application should use measured project targets and current official guidance rather than inventing a universal Xbox requirement.
