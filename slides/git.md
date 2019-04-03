## Git It!

---

## Version Control System

- Version Control System (VCS): manage changes to data <!-- .element class="fragment" -->
- Centralize VCS: CVS, SVN, etc.<!-- .element class="fragment" -->
- Distributed VCS: Git, Mercurial (Hg), Bazaar, etc.<!-- .element class="fragment" -->

note:
- Centralized VCS has a single source of failure
- Distributed VCS has multiple copies of the entire history of the code base

---

## Git Concepts

![git logo](/slides/git-logo.png) <!-- .element class="stretch" -->

note:
- created by Linus Torvalds
- used to manage the Linux source code
- encourages easy and performant branching and merging


## Operations

![git operations](/slides/git-operations.png) <!-- .element width="80%" -->


## Remote Operations

![git remote operations](/slides/git-remote-operations.png) <!-- .element width="80%" -->

- `git clone`
- `git pull`
- `git push`


## Local Operations

![git local operations](/slides/git-local-operations.png) <!-- .element width="80%" -->

- `git add`
- `git commit`

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


## More Esoteric Operations (Google's Your Best Friend)

- `git show-branch`
- `git cherry-pick <reference>`
- `git clean -df`
- `git clean -di`

---

## Integration with IntelliJ

---

## Resources

- [Official (Free) Git Book][git-book]
- [Atlassian Interactive Git][atlassian-git]
- [Learning Git Branching][learn-git-branching]

[git-book]: https://git-scm.com/book/en/v2
[learn-git-branching]: https://learngitbranching.js.org/
[atlassian-git]: https://www.atlassian.com/git
