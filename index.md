# Job-hunt sheet sync

A small personal tool that collects public job postings for one job seeker and keeps them in a Google Sheet that
the account owner controls.

It asks for one Google permission: to read and edit Google Sheets (`https://www.googleapis.com/auth/spreadsheets`).
It uses that permission only on the spreadsheet the owner configures, to add new job postings and to update their
status. It never deletes rows, never touches other files, and is not offered to anyone else.

[Privacy policy](privacy.html)
