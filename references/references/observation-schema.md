# Observation Schema

Use these structures when creating or updating memory data.

Preferred active data folders:

1. `E:\AI\.private\memory-observer`
2. `E:\AI\memory-observer-data`

## profile.md

```markdown
# Profile

nickname:
assistant_name:
city:
timezone: Asia/Shanghai

summary_style: concise
encouragement_style: gentle_specific

blessing_mode: off
birthday:
zodiac:
chinese_zodiac:

weather_mode: off
usual_outing_time:
umbrella_reminder: only_when_outing_time_known

voice_mode: off
voice_style:
read_sensitive: never
speaker_target:
```

Do not ask the user to fill all fields. Empty fields are acceptable.

## Daily Log

Create daily files at `logs/YYYY-MM-DD.md`.

```markdown
# YYYY-MM-DD

## Raw Notes

## Watched / Searched
- platform:
- keyword_or_title:
- why_it_caught_me:
- saved_or_not:
- comment_signals:

## RedNote Signals
- repeated_keywords:
- title_or_cover_patterns:
- user_questions:
- possible_angles:

## Ideas
- 

## Mood / Energy
- 

## Reminders
- 

## Memory Anchors
- 
```

Append new notes under the right section. Preserve the user's original wording in `Raw Notes` when it carries feeling or context.

## Weekly Note

Create weekly files at `weekly/YYYY-Www.md`.

```markdown
# YYYY-Www

## Recurring Themes

## RedNote / Content Signals

## Ideas Worth Keeping

## Mood / Attention Pattern

## Encouragement

## Next Week Focus
```

## Long-Term Memory Summary

Create or update `memory-summary.md` once per week.

```markdown
# Memory Summary

last_updated:

## Stable Preferences

## Recurring Interests

## RedNote / Content Direction

## Active Ideas

## Support Style

## Open Reminders
```

Keep this file compact. Store durable patterns, not raw diary content.
