# yotla/shared-workflows


This repository contains shared workflows to be used across the yotla project's different repositories 

This enables central control and versioning of workflows, without needing to manually copy+paste workflows to maintain consistency 

## `tag-version.yaml`
- computes new semver version based off of previous tag in direct git history 
- tags commit the workflow is called for with a tag containing that semver version
- 