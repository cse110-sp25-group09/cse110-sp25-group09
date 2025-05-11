# Use of JSDoc for Automated Documentation


## Context
> Writing and maintaining manual documentation for JavaScript files would be inefficient and prone to inconsistency. To prevent this, we need an automated tool that can generate documentation directly from comments in the source code.
## Decision
We have decided to use **JSDoc** for documentation automation. JSDoc allows us to embed documentation directly within our JS files using specially formatted comments. We will include a script in our CI pipeline to automatically generate HTML documentation files whenever we push changes to the repository.
This decision ensures:
- Developers write documentation as they code
- Our docs remain updated with minimal manual work
- Non-developers and new team members can get up to pace with the generated HTML docs
## Consequences
### Positive
- Easy to keep documentation consistent with code
- Reduces onboarding time for new developers
- Part of the CI pipeline, so changes are always reflected
### Negative
- Requires developers to learn basic JSDoc syntax
## Alternatives Considered
- **Manual Markdown docs** – time-consuming, likely to become outdated
## Decision Date
2024-05-10
