---

name: "Feature Request"
description: "Request a new feature for the Developer Hub."
title: "[Feature] <Feature Title Here>"
labels: ["feature-request"]
body:

- type: input
  id: summary
  attributes:
  label: "Feature Summary"
  description: "Briefly summarize the feature you are requesting."
  placeholder: "A short summary of the feature..."
  validations:
  required: true
- type: textarea
  id: motivation
  attributes:
  label: "Motivation / Use Case"
  description: "Why is this feature needed? What problem does it solve?"
  placeholder: "Describe the motivation or use case..."
  validations:
  required: true
- type: textarea
  id: acceptance
  attributes:
  label: "Acceptance Criteria"
  description: "What are the requirements for this feature to be considered complete?"
  placeholder: "List acceptance criteria..."
  validations:
  required: false
