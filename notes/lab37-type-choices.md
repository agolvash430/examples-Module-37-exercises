# Lab 37 — Choose Column Types Deliberately
<br>
## Column Table
<br>
_____

Choose column types based on the data being stored.

- VARCHAR → names, emails, titles
- TEXT → long descriptions
- INTEGER → counts and whole numbers
- NUMERIC/DECIMAL → money values
- DATE → calendar dates
- TIMESTAMP or TIMESTAMPTZ → date and time values

<br>
## Money Rule
<br>
_____

Never store money using FLOAT or DOUBLE.

Use a fixed-precision type such as:

NUMERIC(10,2)

This avoids rounding errors and preserves financial accuracy.

<br>
## Time Zones
<br>
_____

For timestamps that may be used across different regions, store time zone information.

Preferred PostgreSQL type:

TIMESTAMPTZ

This ensures timestamps are interpreted correctly regardless of location.

<br>
## JSONB Limit
<br>
_____

Use JSONB for flexible or semi-structured data only.

Do not use JSONB as a replacement for normal relational columns when:
- Data is queried frequently
- Constraints are needed
- Relationships should be enforced
- Indexing is important

Keep structured data in dedicated columns whenever possible.

## Scope
Pre-lab only — do not finish the full lab in this exercise.
