# Lab 37 — Plan Keys and Constraints
<br>

## Key Choice

<br>

_____

Choose a primary key that uniquely identifies each row.

Common choice:
- Auto-generated surrogate key (ID)
- Primary keys must be unique and not null

<br>

## Constraint List

<br>

_____

Common constraints include:
- PRIMARY KEY
- NOT NULL
- UNIQUE
- CHECK
- FOREIGN KEY

Constraints help enforce data integrity.

<br>

## Foreign Key

<br>

_____

A foreign key links one table to another.

It ensures that referenced data exists and helps maintain referential integrity between related tables.

<br>

## Why in the Database

<br>

_____

Constraints should be enforced by the database because all applications and users access the same data.

Database constraints provide consistent validation and protect data integrity even if application code contains
