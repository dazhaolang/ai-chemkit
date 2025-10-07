---
description: Custom molecular analysis workflow for my project
tools: [read_file, codebase_search]
---

# My Custom Analysis Workflow

This is an example of a project-specific command that extends ChemAgent.

## Analysis Steps

1. Load molecule from file
2. Run standard ChemAgent analysis
3. Apply my custom filters:
   - MW must be < 400
   - LogP between 1-3
   - No toxic fragments
4. Generate custom report format

This demonstrates how users can create their own commands!
