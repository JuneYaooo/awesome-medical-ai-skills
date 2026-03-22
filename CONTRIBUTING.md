# Contributing to Awesome Medical AI Skills

Thank you for your interest in contributing! This guide will help you add skills, update ratings, or improve the list.

## How to Contribute

### Adding a New Skill

1. **Fork** this repository
2. **Find the right category** in `README.md` (or propose a new one)
3. **Add your entry** following the table format:

```markdown
| [skill-name](https://link-to-repo) | Platform | ⭐⭐ B | 🟢 Active | Description in one sentence. |
```

4. **Submit a Pull Request** with:
   - A clear title (e.g., "Add FHIR-Analyzer skill to MCP Servers")
   - Brief description of the skill and why it's useful

### Updating an Existing Entry

- Fix broken links
- Update maintenance status (check last commit date)
- Adjust quality ratings with justification
- Add missing information

### Proposing a New Category

If a skill doesn't fit any existing category, suggest a new one in your PR description.

---

## Evaluation Criteria

When rating a skill, consider these dimensions:

### Quality Grade (A/B/C/D)

| Factor | Weight | What to Look For |
|--------|--------|-----------------|
| **Documentation** | 25% | Clear README, usage examples, API docs, installation guide |
| **Functionality** | 30% | Does it work? Feature completeness, error handling |
| **Code Quality** | 20% | Clean code, tests, CI/CD, proper packaging |
| **Community** | 15% | Stars, forks, issues activity, real-world usage |
| **Safety** | 10% | Clinical disclaimers, data privacy, security |

### Maintenance Status

| Status | Criteria |
|--------|----------|
| 🟢 Active | Commits or releases within last 30 days |
| 🟡 Moderate | Activity within last 90 days |
| 🔴 Stale | No activity for 90+ days |

---

## Guidelines

### DO ✅
- Include only skills related to medical/healthcare/health
- Provide accurate descriptions
- Test the skill before recommending grade A
- Include platform compatibility info
- Link to the primary source (not mirrors)

### DON'T ❌
- Add generic AI tools not specific to healthcare
- Include paid-only tools without mentioning the cost
- Add skills that are clearly spam or low-effort
- Submit self-promotional entries without quality justification
- Remove existing entries without discussion

---

## Skill Template

Use this template when adding a new skill:

```markdown
### [Skill Name](https://github.com/user/repo)

- **Platform**: Claude Code / OpenClaw / MCP Server / Multi-Platform
- **Grade**: ⭐⭐ B
- **Maintenance**: 🟢 Active
- **Stars**: X
- **Install**: `npx skills add user/repo -g -y` or `pip install skill-name`
- **Description**: One paragraph describing what the skill does, its key features, and any limitations.
- **Key Features**:
  - Feature 1
  - Feature 2
- **Limitations**:
  - Limitation 1
```

---

## Code of Conduct

- Be respectful and constructive
- Focus on skill quality, not personal opinions
- Follow the [Contributor Covenant](https://www.contributor-covenant.org/)

---

## Questions?

Open an [issue](../../issues) if you have questions about contributing.
