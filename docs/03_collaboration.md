# Collaborative Workflows in Git

Effective collaboration in software development requires structured workflows that support teamwork, quality control, and clear communication. Git provides a variety of tools and conventions that make this possible.

---

## 1. Pull Requests (PRs)

**Definition**:  
A Pull Request is a request to merge changes from one branch into another (usually into `main` or `develop`) in a collaborative project.

### Key Benefits:
- Enables code review and discussion.
- Encourages accountability and knowledge sharing.
- Provides a clear record of what changed and why.

### Typical Workflow:
1. Create a feature branch:
   ```bash
   git checkout -b feature/login-form

