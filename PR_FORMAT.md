# Pull Request Format

A pull request (PR) is how you ask the repository maintainers to review and
include your changes. Open one after your team has finished its meme
submission.

## Title

Use this title format:

```text
Add meme: <team name>
```

Replace `<team name>` with your team's name. For example:

```text
Add meme: git-ninjas
```

## Description

Copy this template into the pull request description and replace the values in
angle brackets:

```markdown
## Meme Submission (PR format)

- Team: `<team name>`
- Submission directory: `submissions/<team-name>/`
- Template: `<memegen.link slug>`
- Description: <one sentence describing the meme>

## Checklist

- [ ] The submission directory is named after the team.
- [ ] `meme_name.txt` contains the exact meme name provided by the website on
      one line.
- [ ] The caption files match the number and order required by the template.
- [ ] Team members contributed through branches and pull requests.
- [ ] Captions are short, readable, and do not contain `/`, `?`, or `#`.
- [ ] The meme follows the submission guidelines.
- [ ] No generated images or unrelated files are included.
```

Before submitting, review the checklist and select each item that is true.
Then click **Create pull request**.
