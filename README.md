# Nominal Date Types

A library of TypeScript types related to Javascript Date.

The types add type safety to various strings and numbers used to serialize or calculate with Date values.
This provides support for conversion and validation, but only minimal support for calculation.

This library has no runtime dependencies.

## Timestamp

This is a type for strings obtained from `Date.toISOString()`.

## EpochMs and DurationMs

EpochMs is a type for numbers like those obtained from `Date.now()`, and represents a number of milliseconds since the UNIX epoch (midnight, Jan 1, 1970, UTC).

DurationMs is a related type for represending a duration of a number of milliseconds.

## CalendarDay

CalendarDay is a type for strings of the form "YYYY-MM-DD", used to represent a particular day as a string.
