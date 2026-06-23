# sporttech.io public wiki

This repository contains public sporttech.io documentation for users,
competition organizers, operators, and partners.

## Purpose

- keep public documentation in one place;
- separate user-facing guides from internal engineering notes;
- store related assets next to the documents: screenshots, diagrams, images,
  and other supporting files;
- gradually build a polished sporttech.io knowledge base.

## Projects

### TRA Scoreboard Director

[Scoreboard Director + Manual scoreboard scenario overview](TRA-Scoreboard-Director.md)

A step-by-step guide for scoreboard operators who use the Manual scoreboard
scenario to control what appears on the display: routine intro, scores,
standings, group start lists, queued screens, and stage team results.

Related assets are stored in
[assets/scoreboard-director](assets/scoreboard-director).

### TRA Manual HD input

[Manual per-element HD input on the displacement judge tablet](TRA-Manual-HD.md)

A step-by-step guide for OCs and displacement judges (H1) at TRA and SYN events
when the stage uses **Allow manual per-element HD input**: enabling the option,
starting and finishing routines, and entering per-skill deductions on the judge
tablet.

Related assets are stored in
[assets/manual-hd](assets/manual-hd).

### AG Judge Score Confirmation

[Judge score confirmation (AG)](AG-Judge-Confirmation.md)

A step-by-step guide for artistic gymnastics events that use judge score
confirmation: enabling the event setting, entering a judge mark, confirming it
on the judge tablet, checking the locked state on the OC page, and resetting
confirmation when a judge needs to edit the mark.

Related assets are stored in
[assets/judge-confirmation](assets/judge-confirmation).

### AG Per-Apparatus Qualification and Advance

[Per-apparatus qualification and advance to apparatus final (AG)](AG-Apparatus-Advance.md)

A step-by-step guide for artistic gymnastics qualification stages: setting
per-apparatus limits (will qualify, in reserve, maximum from one region),
reviewing Q marks on apparatus results, and advancing qualified gymnasts to the
linked apparatus final.

Related assets are stored in
[assets/apparatus-advance](assets/apparatus-advance).

## Adding New Content

1. Add a new Markdown page at the repository root, or inside a topic directory
   once one exists.
2. Put images and other supporting files in `assets/<page-or-project-name>/`.
3. Use relative links so pages work in both GitHub and the public sporttech.io
   wiki.
4. Add the new page to this README.

Before publishing, make sure the document does not include internal passwords,
private URLs, temporary engineering notes, or customer-specific data that should
not be public.
