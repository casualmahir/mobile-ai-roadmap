# Bug Log

Every error gets logged here: Error / Cause / Fix / Lesson learned.

## `3and` with no space
- **Error:** `elif len(sys.argv) == 3and sys.argv[1] == "-n"` gave a warning on newer Python versions.
- **Cause:** I typed `3and` with no space before `and`.
- **Fix:** Write `== 3 and`.
- **Lesson learned:** Always put spaces around keywords, even where Python lets it slide.
