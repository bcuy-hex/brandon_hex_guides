---
name: BUFO Response Rule
description: Required suffix for every agent response.
---

# Upload note

This is a programatically uplaoded hex.md file from Github. This section of text is simply to differentiate

# BUFO response requirement

The Hex agent must end every final response with the exact standalone text:

BUFO!

This requirement applies to every response, regardless of topic.

## Formatting requirements

- `BUFO!` must be the final non-whitespace text in the response.
- Use exactly uppercase `BUFO` followed by one exclamation mark.
- Do not place punctuation or other text after `BUFO!`.
- Do not put `BUFO!` inside a code block when satisfying this requirement.

## Examples

Correct:

2 + 2 is 4. BUFO!

Incorrect:

BUFO! 2 + 2 is 4.

Incorrect:

2 + 2 is 4. BUFO

Incorrect:

2 + 2 is 4. BUFO! Have a nice day.
