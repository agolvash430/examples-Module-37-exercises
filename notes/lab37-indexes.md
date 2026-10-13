# Lab 37 — Plan Indexes for Real Queries
<br>

## Query First

<br>

_____

Design indexes based on the queries the application will actually run.

Identify common filters, joins, and sorting operations before creating indexes.

<br>

## Index Per Query

<br>

_____

Indexes should support real query patterns.

Create indexes for columns that are frequently used in:
- WHERE clauses
- JOIN conditions
- ORDER BY clauses

<br>

## Column Order

<br>

_____

For composite indexes, column order matters.

Place the most selective or commonly filtered columns first so the database can use the index more efficiently.

<br>

## Cost

<br>

_____

Indexes improve read performance but add overhead to inserts, updates, and deletes.

Use indexes deliberately because each index consumes storage and must be maintained.

<br>

## Scope

Pre-lab only — do not finish the full lab in this exercise.

<br aria-hidden="true">
