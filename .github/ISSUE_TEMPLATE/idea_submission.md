---

name: "Wishlist Idea Submission"
description: "Propose a new idea or wishlist item for the Developer Hub."
title: "[Idea] <Your Idea Title Here>"
labels: ["wishlist", "idea"]
body:

- type: input
  id: contributor
  attributes:
  label: "Your Name or GitHub Handle"
  description: "Who is submitting this idea? (Optional)"
  placeholder: "@yourhandle or name"
  validations:
  required: false
- type: textarea
  id: description
  attributes:
  label: "Idea Description"
  description: "Describe your idea in detail. What is it? How would it work? Why is it valuable?"
  placeholder: "Describe your idea here..."
  validations:
  required: true
- type: textarea
  id: motivation
  attributes:
  label: "Motivation / Problem Statement"
  description: "What problem does this solve, or what opportunity does it create?"
  placeholder: "Explain the motivation or problem..."
  validations:
  required: true
- type: input
  id: tags
  attributes:
  label: "Tags (comma-separated)"
  description: "Add relevant tags (e.g., onboarding, docs, integrations)"
  placeholder: "onboarding, docs, integrations"
  validations:
  required: false
