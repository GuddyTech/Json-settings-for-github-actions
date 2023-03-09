This is the configuration I got as a way of enabling Github Actions from the VScode editor.

Simply type Ctrl + Shift + P

Type >settings JSON

Select Open User setting JSON

Add the code:
"yaml.schemas": {
    "https://json.schemastore.org/github-workflow.json": "/.github/workflows/*.yml",
  },

  Save
