# Ethiopian Calendar (E.C.) Requirements

## Requirement

The Ethiopian Calendar is a first-class system calendar across NÚ MAALE. Gregorian Calendar interoperability is required.

## Functional scope

- E.C. date entry, display, validation and navigation.
- Correct E.C. month and year handling, including leap years.
- E.C.-to-G.C. and G.C.-to-E.C. conversion.
- Dual-calendar presentation where useful.
- Calendar-aware deadlines, reminders, events and schedules.
- Reports, exports, search and filtering.
- Offline date entry and deterministic synchronization.
- Clear handling of time zones and date/time boundaries.

## Data integrity

Do not rely on ambiguous free-text date strings as the sole persisted representation. A future data model must preserve an unambiguous date/time value and the relevant calendar context, while supporting consistent conversion and display.

## Verification requirements

A future implementation must include independently reviewed conversion test vectors covering:
- Month starts and ends.
- E.C. New Year boundary.
- Leap-year behavior and Pagume.
- Conversion in both directions.
- Time-zone and midnight boundary behavior.
- Offline capture followed by synchronization.
- Import/export round trips.

## Implementation status

No calendar library, algorithm, database representation or UI component has been selected or implemented. Selection and verification belong to a separately authorized implementation stage.
