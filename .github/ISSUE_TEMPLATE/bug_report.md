---

name: "Bug Report"
description: "Report a bug or issue with the Developer Hub."
title: "[Bug] <Short Description>"
labels: ["bug"]
body:

- type: input
  id: summary
  attributes:
  label: "Bug Summary"
  description: "Briefly describe the bug."
  placeholder: "A short summary of the bug..."
  validations:
  required: true
- type: textarea
  id: steps
  attributes:
  label: "Steps to Reproduce"
  description: "List the steps to reproduce the bug."
  placeholder: "1. Go to ...\n2. Click on ...\n3. See error..."
  validations:
  required: true
- type: textarea
  id: expected
  attributes:
  label: "Expected Behavior"
  description: "What did you expect to happen?"
  placeholder: "Describe the expected behavior..."
  validations:
  required: true
- type: textarea
  id: environment
  attributes:
  label: "Environment"
  description: "Provide details about your environment (OS, browser, etc.)."
  placeholder: "e.g., macOS 14.4, Chrome 123, Node 20..."
  validations:
  required: false
