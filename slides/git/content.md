# Git It!

---

## Version Control System

- Version Control System (VCS): manage changes to data <!-- .element class="fragment" -->
- Centralize VCS: CVS, SVN, Perforce, etc.<!-- .element class="fragment" -->
- Distributed VCS: Git, Mercurial (Hg), Bazaar, etc.<!-- .element class="fragment" -->

note:
- Centralized VCS has a single source of failure
- Distributed VCS has multiple copies of the entire history of the code base

---

## Git Concepts

![git logo](/slides/git/git-logo.png) <!-- .element class="stretch" -->

note:
- created by Linus Torvalds
- used to manage the Linux source code
- encourages easy and performant branching and merging


## Remotes and References

- remotes: <!-- .element class="fragment" -->
  - `git remote add <name> <url>`
  - `git remote set-url <name> <url>`
- references:<!-- .element class="fragment" -->
  - `git tag <name> <reference>`
  - `git branch <name> <reference>`

---

## Operations

![git operations](/slides/git/git-operations.png) <!-- .element width="80%" -->


## Remote Operations

![git remote operations](/slides/git/git-remote-operations.png) <!-- .element width="80%" -->

- `git clone <url>`
- `git pull <remote name> <reference>`
- `git push <remote name> <reference>`


## Local Operations

![git local operations](/slides/git/git-local-operations.png) <!-- .element width="80%" -->

- `git add`
- `git commit`
- `git log`
- `git diff`
- `git show`

---

## More Remote Operations (That Xing Knows, FWIW)

- `git fetch`
- `git merge`
- `git rebase`
- `git pull --rebase`


## More Local Operations (That Xing Knows, FWIW)

- `git checkout -b <new branch> <old branch>`
- `git commit -m <message>`
- `git commit -am <message>`
- `git add --dry-run .`
- `git add -u .`


## More Operations (Google's Your Best Friend)

- `git show-branch`
- `git cherry-pick <reference>`
- `git clean -df`
- `git clean -di`

---

## Integration with IntelliJ

---

## Resources

- `man git-branch`, `man git-commit`, etc.
- [Official (Free) Git Book][git-book]
- [Atlassian Interactive Git][atlassian-git]
- [Learning Git Branching][learn-git-branching]
- [15 Git Commands You May Not Know][15-git-commands]

[15-git-commands]: https://dev.to/zaiste/15-git-commands-you-may-not-know-4a8j
[git-book]: https://git-scm.com/book/en/v2
[learn-git-branching]: https://learngitbranching.js.org/
[atlassian-git]: https://www.atlassian.com/git
