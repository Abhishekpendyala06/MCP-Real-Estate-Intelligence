name: 📋 Bug Report
description: Report a bug in the MCP Real Estate Intelligence Server
title: "[BUG] "
labels: ["bug"]

body:
  - type: markdown
    attributes:
      value: |
        Thanks for reporting a bug! Please provide as much detail as possible.

  - type: textarea
    id: description
    attributes:
      label: Description
      description: Clear description of the bug
      placeholder: "What happened?"
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: Steps to reproduce the bug
      placeholder: |
        1. ...
        2. ...
        3. ...
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      description: What should happen?
    validations:
      required: true

  - type: textarea
    id: actual
    attributes:
      label: Actual Behavior
      description: What actually happens?
    validations:
      required: true

  - type: textarea
    id: error
    attributes:
      label: Error Message/Stack Trace
      description: Include full error message and stack trace
      render: shell

  - type: input
    id: node_version
    attributes:
      label: Node.js Version
      placeholder: "20.0.0"
    validations:
      required: true

  - type: input
    id: os
    attributes:
      label: Operating System
      placeholder: "macOS, Linux, Windows"
    validations:
      required: true

  - type: textarea
    id: additional
    attributes:
      label: Additional Context
      description: Any other relevant information
