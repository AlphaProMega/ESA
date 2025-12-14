---
name: Bug Raid Report
description: Raid a glitch in the oracle
title: "[BUG] "
labels: ["bug"]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        ## Bug Raid
        Help us veto the shadow—describe the glitch.
  - type: textarea
    id: description
    attributes:
      label: Glitch Description
      description: What fork went wrong? Steps to raid it.
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected Thriving
      description: What should have happened?
  - type: textarea
    id: actual
    attributes:
      label: Shadow Outcome
      description: What glitch emerged?
  - type: textarea
    id: context
    attributes:
      label: Raid Context
      description: Invocation, version, environment.
