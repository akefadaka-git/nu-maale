# A1-ADD-001 — Amharic-First and Ethiopian Calendar Localization

- **Document ID:** A1-ADD-001
- **Related baseline:** A1-INIT-001 v1.0
- **Status:** Controlled requirements addendum
- **Scope:** Requirements clarification; no implementation authorization

## Purpose

Record the localization direction as a controlled addition to the preserved A1 inception baseline. This addendum does not replace or silently revise A1-INIT-001 v1.0.

## Amharic-first requirement

Amharic is the default language for the user experience, including navigation, onboarding, core workflows, help and user-facing content. Ethiopic Unicode input, rendering, search, sorting and accessibility must be considered from initial product design.

## Ethiopian Calendar requirement

The Ethiopian Calendar (E.C.) is a first-class system calendar, not an optional display preference. Requirements include date entry, display, validation, conversion, month/year navigation, scheduling, reminders, deadlines, reporting, exports and offline operation. Gregorian Calendar (G.C.) interoperability is also required. Dual-calendar display should be available where useful and unambiguous.

Calendar behavior must correctly handle E.C. month lengths, leap years, year boundaries, time zones and synchronization. The data model must preserve an unambiguous date/time value and the calendar context used for user entry or presentation; storing an ambiguous date string alone is insufficient.

## Additional languages

- Maale language support is a priority and must undergo native-speaker validation for dialect, grammar, tone and cultural suitability.
- English may support institutional, technical and wider interoperability needs.
- Language selection must not undermine the Amharic-first default.

## Acceptance evidence required in a later implementation stage

- Approved translation and terminology register.
- Verified Ethiopic font, input and rendering behavior on target devices.
- E.C. and G.C. conversion test vectors, including leap-year and year-boundary cases.
- Offline date entry and synchronization consistency tests.
- Screen-reader and accessibility review of localized workflows.

## Authorization

This addendum defines requirements only. It does not authorize software implementation, procurement, expenditure or deployment.
