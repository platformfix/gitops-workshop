# Setting Up the GitHub Classroom

This repo is the **template** for the GitOps workshop's GitHub Classroom assignment. When an attendee accepts the assignment, GitHub generates a private copy of this repo for them. This is the maintainer guide for constructing that Classroom.

## When you need this

Create a new assignment before each cohort. An assignment is bound to this repo at a point in time, so after a rename (this repo was `gitops-workshop`, now `gitops-workshop-labs`) or for a fresh cohort, build a new one.

## Steps

1. Go to [classroom.github.com](https://classroom.github.com) and open or create a Classroom under the **platformfix** organisation.
2. **New assignment** → **Individual assignment**.
3. Title it for the cohort, e.g. `gitops-fundamentals-<event>`. The title becomes the per-student repo prefix.
4. **Starter code**: select this repo, `platformfix/gitops-workshop-labs`.
5. **Repository visibility**: Private. Each student gets their own private copy.
6. Give students **admin** access to their repo. They need to push and manage it during the labs.
7. Open deadline, no autograder.
8. Create it, then copy the **invite link** (looks like `https://classroom.github.com/a/XXXXXXXX`).
9. Put that invite link into the workshop site's `access.md` (Step 5), and share it on screen on the day.

## The gotcha (call this out)

When a student accepts the assignment, their repo is **created asynchronously, and the page after accepting does not always show it**. In past cohorts several people thought it had failed.

The fix: have them **browse directly to their repo** in the browser:

```
https://github.com/platformfix/<assignment-prefix>-<their-github-username>
```

It's there within a few seconds even when the accept page looks stuck. Say this out loud and put it in the access instructions so nobody burns lab time on it.

## After creating the assignment

- Update the invite link and the per-student clone-URL prefix in `gitops-workshop-site/docs/access.md` (Step 5).
- Test it end to end with a throwaway account or a co-organiser before the workshop.

## The alternative: the fork model

The Kubernetes workshop deliberately skips Classroom and uses a **fork model** instead (`k8s-workshop-labs`: attendees fork the repo and clone their fork). It sidesteps this gotcha and the private-clone auth friction entirely, at the cost of per-student isolation. Worth considering for future workshops if Classroom overhead outweighs the benefit.
