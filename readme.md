# Outstanding Git Practices

- [Commit Messages](#commit-messages-)
- [Commit Commits](#git-commits-)

## Commit messages 📝

Commit messages play a big role in the understanding of every change. They should be short, clear and explicit. They should say clearly what happened and what changed. Ideally, adding a ticket number of the issue as prefix would help in case we need further information. Sometimes, we need to know the reason why a piece of code has been changed and need to dig into the story ticket to have a full understanding of the feature requirements.
When possible, mention the ticket number at the beginning of your commit message makes things much easier. In that way, if we need further details, we can click on the story ticket and get a better summary of what that commit does.

---

## Git commits 🎨

✅ Each commit should be small and fix only one thing per commit, not more.
Following this good rule, if your commit message contains the word `and` or `+`, that means you try to commit multiple changes in one commit and you shouldn’t ❌
This rule is not just there to be nice. When you need to revert or cherry-pick a commit from your git history, the fact that one commit only contains one specific update really helps.
