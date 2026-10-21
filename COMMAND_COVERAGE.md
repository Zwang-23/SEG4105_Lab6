# Lab 6 Command Coverage

Every command below is an explicit student operation in the handout. The spelling `stach` in the original list is corrected to `stash`.

| Pipeline | Required commands | Student steps |
| --- | --- | --- |
| Repository Setup | `init`, `clone`, `remote` | Exercise 1 creates an empty init demonstration, clones the shared starter, and sets source and submission remotes. |
| Local Staging | `status`, `diff`, `add`, `commit` | Exercise 2 inspects and records the v1 to v2 scope change. |
| Collaboration | `push`, `pull`, `fetch`, `merge` | Exercise 3 exchanges a team update; Exercise 4 supplies the shared integration operation. |
| Feature Lifecycle | `branch`, `switch`, `stash`, `merge`, `rebase` | Exercise 4 creates a branch, stores and restores its draft, rebases onto an advanced main, then merges. |
| Correction | `log`, `blame`, `revert`, `reset`, `restore` | Exercise 5 inspects attribution, discards an uncommitted edit, soft-resets an unpushed draft, and reverts a published error. |

`merge` occurs in two pipeline lists, giving 20 distinct required commands. It is practiced as one real integration in Exercise 4.

## Repository roles

- `main`: clean project starter to clone.
- `lab-guide`: instructions and student downloads.
- `worked-example`: the completed instructor rehearsal.

Students rename the cloned `origin` to `upstream` and add their own public repository as `origin`. They publish to their own `main`, leaving the shared starter intact.

The reference run uses a separate `worked-example` branch of the instructor repository as its publication target. Its source and publication URLs therefore match, unlike a student's personal submission URL. The full rehearsal executed all 20 commands and real GitHub push, fetch and pull; it checked that rebase changed the feature commit ID, soft reset retained the staged change and revert restored the clean final record.

Submission remains five short answers and five screenshots. No extra evidence file is required from students.
