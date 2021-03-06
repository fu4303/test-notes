# Label Templates

These are the templates I use for loading labels into a new repository.

## Default Labels

These are my default labels, present on ALL repositories. These are based on the [Creative Commons Labelling Standards](https://opensource.creativecommons.org/contributing-code/repo-labels/).

```json
[
  {
    "name": "๐ฅ priority: critical",
    "description": "Must be fixed ASAP",
    "color": "b60205"
  },
  {
    "name": "๐ง priority: high",
    "description": "Stalls work on the project or its dependents",
    "color": "ff9f1c"
  },
  {
    "name": "๐จ priority: medium",
    "description": "Not blocking but should be fixed soon",
    "color": "ffcc00"
  },
  {
    "name": "๐ฉ priority: low",
    "description": "Low priority and doesn't need to be rushed",
    "color": "cfda2c"
  },
  {
    "name": "๐ช priority: none",
    "description": "No priority, should only be performed when a developer is available",
    "color": "008672"
  },
  {
    "name": "๐ status: ready for dev",
    "description": "Ready for work",
    "color": "cccccc"
  },
  {
    "name": "๐ง status: blocked",
    "description": "Blocked and therefore not ready for work",
    "color": "999999"
  },
  {
    "name": "๐งน status: ticket work required",
    "description": "Needs more details before it can be worked on",
    "color": "666666"
  },
  {
    "name": "๐ท status: label work required",
    "description": "Needs proper labelling before it can be worked on",
    "color": "666666"
  },
  {
    "name": "๐ status: discontinued",
    "description": "Not suitable for work as repo is in maintenance",
    "color": "eeeeee"
  },
  {
    "name": "โ๏ธ status: discarded",
    "description": "Will not be worked on",
    "color": "eeeeee"
  },
  {
    "name": "๐ฆ status: awaiting triage",
    "description": "Has not been triaged & therefore, not ready for work",
    "color": "333333"
  },
  {
    "name": "โญ goal: addition",
    "description": "Addition of new feature",
    "color": "ffffff"
  },
  {
    "name": "โจ goal: improvement",
    "description": "Improvement to an existing feature",
    "color": "ffffff"
  },
  {
    "name": "๐? goal: fix",
    "description": "Bug fix",
    "color": "ffffff"
  },
  {
    "name": "๐ aspect: text",
    "description": "Concerns the documentation material in the repository",
    "color": "04338c"
  },
  {
    "name": "๐ป aspect: code",
    "description": "Concerns the software code in the repository",
    "color": "04338c"
  },
  {
    "name": "๐น aspect: interface",
    "description": "Concerns end-users' experience with the software",
    "color": "04338c"
  },
  {
    "name": "๐ค aspect: dx",
    "description": "Concerns developers' experience with the codebase",
    "color": "04338c"
  },
  {
    "name": "โ talk: question",
    "description": "Can be resolved with an answer",
    "color": "f9bbe5"
  },
  {
    "name": "๐ฌ talk: discussion",
    "description": "Open for discussions and feedback",
    "color": "f9bbe5"
  },
  {
    "name": "good first issue",
    "description": "New-contributor friendly",
    "color": "7f0799"
  },
  {
    "name": "help wanted",
    "description": "Open to participation from the community",
    "color": "7f0799"
  },
  {
    "name": "๐ staff only",
    "description": "Restricted to project staff members",
    "color": "7f0799"
  }
]
```

## Hacktoberfest Labels

These labels are applied when I opt in a project for the [Hacktoberfest event](https://hacktoberfest.digitalocean.com/).

```json
[
  {
    "name": "invalid",
    "description": "Inappropriate or invalid for Hacktoberfest contributions",
    "color": "eeeeee"
  },
  {
    "name": "Hacktoberfest",
    "description": "Good issues for Hacktoberfest participants",
    "color": "883255"
  }
]
```

## Skill Labels

This template is used to create `skill` labels, which help contributors identify the skills needed to resolve an issue so they can find issues that match their skillset.

To use this, replace `skillname` with the skill (i.e. `TypeScript` or `Angular`), then add this object to your `labels` array.

```json
{
  "name": "๐ช skill: <skillname>",
  "description": "Requires proficiency in <skillname>",
  "color": "5ff1f5"
}
```

## Miscellaneous Labels

This template is used for miscellaneous uncategorised labels. Miscellaneous labels should still follow the same standard naming conventions.

```json
{
  "name": "<emoji> <category> <name>",
  "description": "text here",
  "color": "000000"
}
```
