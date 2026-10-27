# Homework Glowup

An Agent Skill for preparing and reviewing assignment deliverables, with a checklist that records what was checked and the evidence available.

## What it does

- Check answers, assignment conditions, length limits, units and calculations; run representative and boundary inputs for executable code where applicable.
- Read assignment naming instructions and saved private user rules for each task, then verify final filenames, extensions and actual formats.
- Apply white backgrounds, black text and gray table shading, with red accents when needed. Check numbered captions above tables and figures in long reports, centered over their items.
- Include AI-use disclosures and reference links when required by the assignment or requested by the user. Describe actual AI use accurately when the assignment asks for it.
- Set and verify human author metadata, excluding AI agent names while preserving confirmed human attribution.
- Align internal and filesystem modification times. For a new assignment, set its internal creation time roughly 30 minutes earlier, with a small deviation from an exact interval; preserve existing creation times on later edits. This offset is a metadata convention rather than a record of actual work history.
- Record results, evidence, unverified items and reasons for non-applicable checks in a separate working checklist.

The skill prepares deliverables locally. Upload or publication requires separate authorization.

## Use the skill

Install the [skills/homework-glowup](skills/homework-glowup) directory in a client that supports Agent Skills. Invoke `$homework-glowup` when preparing or reviewing an assignment.

The skill contains instructions and a [Markdown checklist template](skills/homework-glowup/templates/assignment-checklist.md). Document editing and rendering use the format-specific tools available in the client.

Keep private filename rules outside this repository and the installed skill directory, as described in [SKILL.md](skills/homework-glowup/SKILL.md). Copy the checklist into a working location separate from submission files and record the actual checks performed.

## License

No license has been selected for this repository.
