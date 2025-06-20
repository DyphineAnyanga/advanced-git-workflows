# Rebasing vs Merging in Git

Managing changes across branches is a core part of Git-based workflows. Two primary strategies for integrating changes are **merging** and **rebasing**. Both have different effects on your project's commit history and collaboration flow.

---

## 1. Git Merge

**Definition**:  
Merging combines the histories of two branches. It creates a new "merge commit" that ties together the latest commits from each branch.

### Characteristics:
- Preserves full branch history.
- Adds a merge commit for traceability.
- Ideal for collaborative teams who want to retain the context of feature development.

### Example:
```bash
# Merge a feature branch into develop
git checkout develop
git merge feature/new-feature

