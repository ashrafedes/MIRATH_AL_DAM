# AI Production Bible — ميراث الدم

**Version:** v0.1  
**Status:** Initial operating rules; tool-specific settings to confirm.

## Pipeline
Locked script → scene package → approved character/location/prop references → storyboard/keyframes → image-to-video candidates → voice/sound → edit → continuity and technical QC.

## Reference discipline
- Use clean, approved, individual references wherever supported.
- Keep the same identity and reference set across shots for the same character.
- Keep location and prop references attached to each relevant shot.
- Never treat a generated candidate as approved without review.

## Prompt record
For each generated shot, record:
- Shot ID and prompt version
- Character/location/prop reference IDs
- Positive prompt and negative constraints
- Model/tool and version
- Seed and settings when available
- Candidate file IDs and selected take
- QC result, reviewer, and approval date

## Rejection criteria
Reject identity drift, costume/accessory drift, inconsistent geography, prop-state errors, malformed anatomy, extra/duplicated characters, unintended camera movement, incorrect screen direction, and dialogue/lip-sync errors.

## Tool-specific settings
Model choice, resolution, aspect ratio, duration, motion controls, reference-conditioning options, and cost limits are **TO CONFIRM** against the tools actually used.
