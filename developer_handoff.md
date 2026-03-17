# Developer Handoff

This project is ready for a lean launch. Do not add more participant-facing reading unless it removes ambiguity. The goal is low friction for entrants and clean judging.

## Canonical participant files

Publish these four markdown files:
- `challenge_brief.md`
- `packet_a.md`
- `packet_b.md`
- `submission_template.md`

Current status:
- brief: done
- packet A: done
- packet B: done
- submission template: now added

## One required external workflow

Create the submission form with exactly these fields:
- entrant or team name
- contact email
- repo URL
- final commit SHA

The final commit SHA is the judged version.

## What developers should preserve

These rules are scoring-critical and should stay identical across the brief, template, and any landing page copy:
- use only packet facts for scenario claims
- manager comments are internal context unless packet-verified
- do not invent missing transcript context
- do not assume legal review or full interview access
- complete Phase 1 before Packet B
- Phase 2 must update Phase 1 rather than restart from scratch
- clearly label Phase 1 and Phase 2
- include one sentence stating that Phase 2 was produced after Phase 1

## Hard scenario constants

Do not drift on these details:
- Packet A scenario time: 5:30 PM
- Packet B scenario time: 6:15 PM
- Timothée off-phone until 6:05 PM
- sponsor-safe holding line due by 5:50 PM
- sponsor-safe holding line max length: 40 words
- reporter aims to publish by 6:30 PM
- sponsor escalation plan due by 6:35 PM
- public statement in Timothée's voice requires Timothée approval
- manager can approve sponsor and reporter holding replies before then

## Repo acceptance check

A valid submission should have:
- one main submission file
- one standalone first-hour triage table artifact
- one short README or workflow overview, unless that overview is at the top of the main submission file
- any optional support files needed to understand the workflow

## What not to build unless there is extra time

Skip these unless they solve a real operational problem:
- JSON or YAML packet versions
- separate fact-status file
- separate run-contract file
- starter repo template
- agent schema for builders
- no-code or notebook examples
- demo video requirement
- app hosting requirement

## Developer launch order

1. Publish the four markdown files.
2. Put the submission form live.
3. Make sure the landing page repeats only the essentials: dates, repo URL, final commit SHA, and the four judged dimensions.
4. Stop adding participant docs.

## Why this stays lean

The challenge is supposed to reward workflow quality, judgment, adaptation, and hard-to-fake process evidence. More reading will increase drop-off without improving signal. The brief and packets should stay short. The template should do the structural work.
