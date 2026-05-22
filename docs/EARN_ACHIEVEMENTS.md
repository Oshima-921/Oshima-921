# How to Earn GitHub Profile Achievements

GitHub awards these badges automatically on your profile ([Achievements tab](https://github.com/Oshima-921?tab=achievements)). They cannot be added manually—only earned through real activity.

Your account **@Oshima-921** was created **May 2026**. You already have some merged pull requests; use the steps below to unlock the rest.

## Enable achievements on your profile

1. Open [Profile settings → Achievements](https://github.com/settings/profile#profile-settings-heading)
2. Turn on **Show achievements on my profile**

---

## Achievement checklist

| Badge | Requirement (base tier) | What to do |
| --- | --- | --- |
| **Pull Shark** | 2 merged pull requests | Open PRs in your repos, get them reviewed, and merge. You need more merges for higher tiers (x2 = 16, x3 = 128). |
| **Pair Extraordinaire** | 1 merged PR with a co-author | Add `Co-authored-by: Name <email@example.com>` in the commit message or use GitHub’s co-author UI when committing. |
| **Public Sponsor** | Sponsor someone on GitHub | Go to [GitHub Sponsors](https://github.com/sponsors), pick a developer or project, and sponsor (even $1/month counts). |
| **Starstruck** | One repo reaches **16 stars** | Promote your best repo (`ecommerce-site`, `sheet-library`, etc.) or improve README/demo until it gets 16+ stars. |
| **YOLO** | Merge your own PR without review | Open a PR on a repo you own, then merge it without approving review (branch protection must allow this). |
| **Galaxy Brain** | 2 accepted answers | Answer questions in a repo’s **Discussions** (Q&A category); ask the author to mark your reply as the answer. |
| **Quickdraw** | Close issue or PR within **5 minutes** | Open a test issue on your repo, then close it within 5 minutes (or open + close a PR quickly). |

---

## Fastest wins for your account

### 1. Pull Shark (likely close already)

You have several merged PRs. If the badge is missing, merge one more PR in any owned repo:

```bash
git checkout -b docs/readme-tweak
# make a small change
git commit -m "docs: minor readme update"
git push -u origin docs/readme-tweak
```

Then open a PR on GitHub and merge it.

### 2. YOLO

1. Create branch → small change → open PR
2. Do **not** request review (or disable required reviews in repo Settings → Branches)
3. Click **Merge pull request** yourself

### 3. Quickdraw

1. Open a new issue titled `test: quickdraw`
2. Close it within 5 minutes

### 4. Pair Extraordinaire

On your next PR, add to the commit body:

```text
Co-authored-by: Partner Name <partner@users.noreply.github.com>
```

Merge that PR.

### 5. Public Sponsor

Visit https://github.com/sponsors and sponsor any open-source account you want to support.

### 6. Starstruck

Pick one flagship repo and focus stars there (16+ on a **single** repository).

### 7. Galaxy Brain

Enable **Discussions** on a repo (Settings → General → Features), post a question, answer it from a second account or collaborator, and mark the answer as accepted (2 times for base badge).

---

## Higher tiers (x2, x3, x4)

| Badge | x2 (Bronze) | x3 (Silver) | x4 (Gold) |
| --- | --- | --- | --- |
| Pull Shark | 16 merged PRs | 128 merged PRs | 1024 merged PRs |
| Pair Extraordinaire | 10 co-authored merges | 24 co-authored merges | 48 co-authored merges |
| Starstruck | 128 stars on one repo | 512 stars | 4096 stars |
| Galaxy Brain | 8 accepted answers | 16 accepted answers | 32 accepted answers |

---

## Notes

- Badges can take **a few minutes to 24 hours** to appear after the action.
- README images are for display only; only GitHub can grant the real profile badge.
- Avoid spam PR bots—GitHub may remove achievements for artificial activity.
