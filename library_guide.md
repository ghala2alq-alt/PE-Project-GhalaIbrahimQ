# Library Guide

Owner: GhalaAlQahtani · Version: v1 · Date: 2026_10_15

## What is in the library

This library supports a Learner Support Desk at a training center. It has 5 approved prompt templates (templates/), one Facts block (blocks/), one rules file (rules/), an index (library_index.md) and a Test Results Report (Test_Results_Report.pdf). All data in it is invented.

## How to copy a template

1. Open library_index.md and find the template for your task.
2. Open the template file and copy everything inside the box under "Template".
3. Paste it into your approved AI tool.

## How to fill the variables

Replace each [VARIABLE] with a value from the Variables table in the file. If you leave a variable empty, the template uses its default. [FACTS] must be replaced with the full text of TC-Facts-v1_2026_10_15.md. [INPUT_TEXT] must be masked first: no real names, phone numbers, emails or ID numbers. Replace any real details with codes such as Learner-1, Phone-1 and Email-1 before using the text. The fixed safety rules stay in the template and must not be deleted.

## How to check an output

Before anything is sent, a person checks the output with the Day 4 checklist:

* Every fact is in the Facts block, and the block is up to date.
* Numbers, dates and names match the source exactly.
* No promised date and no "I did this".
* No sensitive data repeated; only codes such as Learner-1.
* Every question is answered and the wording reads naturally.

If one check fails, fix the template once and run it again. If it still fails, write the reason and the proposed fix in the report.

## Who owns each file

GhalaAlQahtani owns every file in this library. Changes need a new version number, a new date and a change log line. Old versions move to _archive/.
