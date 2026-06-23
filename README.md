# skill-humanizer

A Claude skill that removes AI writing patterns from prose to make text sound naturally human-written.

## Trigger
Say: `humanize this`, `make it real`, or `clean the slop`.

## What it does
- Detects and fixes: inflated symbolism, promotional language, em dash overuse, rule-of-three, AI vocabulary, filler phrases, vague attributions
- Based on Wikipedia's 'Signs of AI writing' guide
- Runs a two-pass audit: draft → identify AI tells → final revision
- Leaves code blocks untouched

## Files
- `SKILL.md` — skill instructions
- `WARP.md` — supplementary patterns
