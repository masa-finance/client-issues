name: General Inquiry
description: Ask a general question about Masa products
title: "[INQUIRY]: "
labels: ["question", "triage"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for reaching out with your question about Masa products!
  - type: dropdown
    id: product
    attributes:
      label: Masa Component
      description: Which Masa component is your question about?
      options:
        - Miner
        - Validator
        - Subnet
        - Protocol
        - Other (please specify in your question)
    validations:
      required: true
  - type: input
    id: version
    attributes:
      label: Component Version
      description: If applicable, provide the version or commit hash of the component
      placeholder: e.g., v1.2.3, commit hash, or N/A
  - type: textarea
    id: question
    attributes:
      label: Your Question
      description: Please provide as much detail as possible about your inquiry.
      placeholder: I'd like to know more about...
    validations:
      required: true
  - type: textarea
    id: context
    attributes:
      label: Additional Context
      description: Add any additional context or background information that might help us answer your question.
  - type: textarea
    id: environment
    attributes:
      label: Environment Details
      description: If relevant, please provide details about your environment.
      placeholder: |
        - Operating System: [e.g., Ubuntu 22.04, macOS 12.6, Windows 10]
        - Python version (if applicable): [e.g., 3.11.2]
        - Docker version (if applicable): [e.g., 20.10.21]
        - Other relevant software versions:
