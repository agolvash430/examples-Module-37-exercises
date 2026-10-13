# Lab 37 — Plan the Role and Connection
<br>

## JDBC URL

<br>

_____

The JDBC URL identifies the database location and connection details.

Example format:

jdbc:postgresql://host:port/database

<br>

## App Role

<br>

_____

Create a dedicated database role for the application.

The application should connect using its own account rather than an administrator account.

<br>

## Least Privilege

<br>

_____

Grant only the permissions the application requires.

Avoid giving administrative privileges when the application only needs to read and write application data.

<br>

## Secret Handling

<br>

_____

Do not hard-code usernames, passwords, or other secrets in source code.

Store secrets in configuration, environment variables, or a secure secret-management solution.

<br>

## Scope

Pre-lab only — do not finish the full lab in this exercise.

<br aria-hidden="true">
