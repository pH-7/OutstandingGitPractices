# Outstanding Git Practices

### The 2 Most Important Guidelines When Committing Your Code

- [Commit Messages](#commit-messages-)
- [Git Commits](#git-commits-)
- [About the Author](#about-the-author-)

## Commit Messages 📝

Commit messages play a big role in the understanding of every change. They should be in present tense, short, clear and explicit. 

They should clearly say **what happened** as well as the **reason**/**motivation** behind the change. 

Ask yourself, “*What are the changes done for?*” In other words, *“Why did you do what you did?”* - In short, it is the explanation that we don't necessarily see in the code diff of the commit.

Additionally, add the ticket ID at the beginning of your commit message. Sometimes, we need to know the reason why a piece of code has been changed and need to dig into the ticket to have a full understanding of the feature requirements.

---

## Git Commits 🎨

✅ Each commit should be small and fix only one thing per commit, not more. Following this important rule, if your commit message contains the word `and` or `+` sign, that means you are trying to commit multiple changes in one commit and you shouldn't ❌

This rule is not just there to be nice. When you need to `git revert` or `cherry-pick` a commit from your git history, the fact that one commit only contains one specific update really helps.

## About the Author 👨‍🍳

**[Pierre-Henry Soria](https://ph7.me)**. A super passionate and enthusiastic software engineer, and a true cheese & chocolate lover 💫 

[![@phenrysay](https://img.shields.io/badge/x-000000?style=for-the-badge&logo=x)](https://x.com/phenrysay "Follow me on X") [![pH-7](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pH-7 "Follow me on GitHub") [![YouTube Tech Videos](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@pH7Programming "Subscribe to my YouTube Tech Channel")

[![Pierre-Henry Soria](https://s.gravatar.com/avatar/a210fe61253c43c869d71eaed0e90149?s=200)](https://ph7.me "Pierre-Henry Soria personal website")
