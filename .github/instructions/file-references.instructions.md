---
applyTo: "**/*.md"
---

# File references

For the causes of these rules, refer to [file-references.findings.md](file-references.findings.md).

* To refer to a file, write a Markdown link. Start the path in the folder of the file that contains the link.
* If you refer to a file in [src/R3.Stride/README.md](../../src/R3.Stride/README.md), write the absolute URL of the file on GitHub.
* To refer to a skill, write a Markdown link to its `SKILL.md` file. Use the name of the skill as the text of the link.
* Do not use `#file:'<path>'`.
* Do not write `@` before a path, except in an import in `CLAUDE.md`. Do not change an import in `CLAUDE.md` into a link.
* Do not put a link to a `*.instructions.md` file at the end of a line.

Examples in [README.md](../../README.md):

```markdown
[Directory.Build.props](Directory.Build.props) sets the parameters that all projects use.
```
