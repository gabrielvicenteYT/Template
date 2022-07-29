name: Bug report
description: Report an issue with the Project
labels: bug
body:
- type: markdown
  attributes:
    value: |
      Before reporting an issue, [please search](https://github.com/gabrielvicenteYT/Template/issues) to make sure it has not already been reported. 

- type: textarea
  attributes:
    label: Describe the bug
    description: Describe your issue.
  validations:
    required: true

- type: input
  attributes:
    label: Version
    description: What version of the Project are you using?
    placeholder: Find it in the bottom right corner of the main menu
  validations:
    required: true

- type: checkboxes
  attributes:
    label: Other things
    description: Check if applicable.
    options:
      - label: I updated Project to a newer version (mention, what version to what version)
    
- type: textarea
  attributes:
    label: Additional context
    description: Screenshots, video or any other information. If it is a crash, please post it to [Pastebin](https://pastebin.com) and add a link here.
    placeholder: |
      Tip: You can attach images or log files by clicking this area to highlight it and then dragging files in.
  validations:
    required: false
