name: 🪲"Bug Report"
description: If you've found a reproducible bug
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to file a bug report!

        We're most likely to fix bugs that are easy to reproduce, so please try
        to provide enough information for us to understand how to reproduce the
        issue. 

  - type: textarea
    attributes:
      label: What is the issue?
      description: |
        A clear and concise description of what Airee is doing and what you
        would expect.
    validations:
      required: true

  - type: textarea
    attributes:
      label: How can it be reproduced?
    validations:
      required: true

  - type: textarea
    attributes:
      label: Logs, error output, etc
      description: |Please provide output of logs with an error message
    validations:
      required: true

  - type: textarea
    attributes:
      label: Environment
      placeholder: |Please describe used environment     
    validations:
      required: true

  - type: textarea
    attributes:
      label: Possible solution
      description: "If you have suggestions on a fix for the bug."
