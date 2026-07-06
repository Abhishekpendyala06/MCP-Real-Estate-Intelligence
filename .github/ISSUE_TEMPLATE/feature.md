name: ✨ Feature Request
description: Suggest an improvement or new feature
title: "[FEATURE] "
labels: ["enhancement"]

body:
  - type: markdown
    attributes:
      value: |
        Thanks for suggesting a feature! Help us understand your request.

  - type: textarea
    id: problem
    attributes:
      label: Problem Statement
      description: Describe the problem this feature would solve
      placeholder: "I want to be able to..."
    validations:
      required: true

  - type: textarea
    id: solution
    attributes:
      label: Proposed Solution
      description: Describe how this feature should work
    validations:
      required: true

  - type: textarea
    id: alternatives
    attributes:
      label: Alternative Solutions
      description: Other ways to solve this problem?

  - type: textarea
    id: use_cases
    attributes:
      label: Use Cases
      description: |
        Describe specific use cases for this feature
        - Use case 1
        - Use case 2
    validations:
      required: true

  - type: checkboxes
    id: checklist
    attributes:
      label: Is this related to...
      options:
        - label: Property search functionality
        - label: Market analysis
        - label: Property valuation
        - label: Investment analysis
        - label: Neighborhood analysis
        - label: Financial planning
        - label: Performance/caching
        - label: Security
        - label: Documentation
