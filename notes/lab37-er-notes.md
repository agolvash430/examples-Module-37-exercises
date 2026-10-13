# Lab 37 — Model the CRM Relationships
<br>

## Cardinalities

<br>

_____

Cardinality describes how many records in one table can relate to records in another table.

Common types:
- One-to-One (1:1)
- One-to-Many (1:N)
- Many-to-Many (M:N)

<br>

## Many-to-Many

<br>

_____

A many-to-many relationship should be implemented with a junction (bridge) table.

The junction table stores foreign keys that reference the related tables.

<br>

## Normalize

<br>

_____

Normalization reduces data redundancy and improves data consistency.

Store each fact once and use relationships between tables rather than duplicating data.

<br>

## When Not To

<br>

_____

Do not over-normalize when it makes queries unnecessarily complex or negatively affects performance.

In some cases, limited denormalization can improve efficiency.

<br>

## Scope

Pre-lab only — do not finish the full lab in this exercise.

<br aria-hidden="true">
