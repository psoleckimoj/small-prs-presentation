+++
title = "Why small PRs?"
outputs = ["Reveal"]

[reveal_hugo]
theme = "black"
+++

# Why small PRs?

Or are they just far away? <sup>1</sup>

{{% note %}}
1. [Cows: Small Or Far Away? | Father Ted](https://www.youtube.com/watch?v=MMiKyfd6hA0&ab_channel=Channel4)
{{% /note %}}

---

## Why small PRs?

- depends on your team
- increases understandibility (usually) 
- faster and better feedback
- break less, easier to spot bugs
- focus on one change

---

{{% section %}}
## It really depends on who is reviewing

- PR strategies are best discussed with your team
- larger PRs maybe acceptable due to much higher understanding of the code
- refactoring is understood and can lead to large PRs

---

## Increases understandability

- usually
- badly written code isn't made more understandable if it's done in small PRs
- well written code makes it easy to understand to outsiders
- large PRs are daunting if you don't know the code, possibly having to check out the project to understand the context for the PR

---

## Faster and better feedback

- less lines to read means there's less to check (obviously...)
- smaller problems are easier to understand
- takes less time to check and hence can write more meaningful feedback

---

## One change

- stick to one problem
- push other changes you need to make into separate PRs unless they abosolutely cannot

---

## Bug spotting

- again, less code, tend to pay more attention
- less lines so bugs tend to be more obvious


{{% /section %}}

---

## My experience

- some people will refuse to merge large PRs
- very dependent on your team, can be more forgiving
- took me a while to stop and break out other changes when doing a ticket, i.e. updating a module and it's methods

---

## Useful links

- [Why small merge requests are key to a great review](https://about.gitlab.com/blog/2021/03/18/iteration-and-code-review/)
- [Please write smaller Pull Requests!](https://blog.devgenius.io/please-write-smaller-pull-requests-5988da5e8e5f)
- [Strategies For Small, Focused Pull Requests](https://artsy.github.io/blog/2021/03/09/strategies-for-small-focused-pull-requests/)

---

# Questions? 🤔
