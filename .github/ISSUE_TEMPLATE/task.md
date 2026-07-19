name: Task Assignment
about: Claim or report a task

title: '[Task] '
labels: ['task']
body:
  - type: textarea
    id: description
    attributes:
      label: Task Description
      description: What needs to be done?
      placeholder: Describe the task clearly...
    validations:
      required: true
  - type: select
    id: priority
    attributes:
      label: Priority
      options:
        - High
        - Medium
        - Low
    validations:
      required: true
  - type: textarea
    id: notes
    attributes:
      label: Notes
      description: Any additional context or links
      placeholder: Add context here...
