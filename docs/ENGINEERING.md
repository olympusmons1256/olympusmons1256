# Engineering Guide

## Pull Requests & Workflow
- **Branching Strategy**: Format new branches as `[Project Management ID]-[FeatureName]-dev`.
  - Example: `ODY2-108-PaymentStripe-dev`
- **Commit Methodology**: Use imperative mood with Project Management ID prefix. 
  - Example: `ODY2-108: Fix- payment stripe issue fix`
- **Descriptions**: Provide a clear "why" behind the change in the PR body.

## CLI Execution
- **Creating PRs**: `gh pr create --title "Add feature [JIRA-123]" --body-file .github/PULL_REQUEST_TEMPLATE.md`
- **Review Requests**: `gh pr edit <PR-number> --add-reviewer <username>`

## Jira Structure
- **Epic / Child / Sub-Task**
- **Epic**: Top-level parent.
- **Child**: Feature.
- **Sub-Task**: Individual work items within a feature.

## Documentation & Wiki Model
- **Standards**: High-level standards 
- **Project Wikis**: Reserved strictly for issue tracking and specific dev-logs.
- **Docs-as-Code**: Technical specifications live in the `/docs` folder of each repo.

## Spatial Computing & 2x22 Standards
- **Performance**: Frame-rate consistency (60/72/90Hz) is critical for user comfort.
- **Physics**: Standardizing on Cannon.js for deterministic spatial interactions.
- **Optimization**: Use Draco compression for GLTF/GLB assets.
