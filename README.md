<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/2baed06e-c708-471c-ad8b-2254f04247a7" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/7964da3e-e450-4984-9f29-e9373fc5b1c1" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9b817c61-c713-467f-8ccb-1513095f3cdf" />
## What I Changed

Added a new Project Features section to the webpage describing the main Git workflow features demonstrated by the project.

### Changes Made

* Added a new Features section to `index.html`
* Added navigation to the Features section
* Listed Git branching and merging practice
* Listed merge conflict resolution
* Listed collaborative GitHub workflow

## Why I Made This Change

This change makes the purpose of the project clearer to visitors and provides a quick overview of the Git concepts being demonstrated.

## Testing

I opened the webpage locally and verified that the new Features section and navigation link display correctly.

## Bonus Challenge: Rebase vs Merge

Git merge and git rebase are both used to integrate changes from one branch into another. I would use `git merge` when I want to preserve the complete history of how branches were developed and combined. Merge is especially useful for collaborative projects because it does not rewrite existing commits. I would use `git rebase` when I want to maintain a clean, linear project history and make the feature branch appear as though it was developed from the latest version of `main`. The main advantage of rebase is a simpler history that is easier to read and review. However, rebase rewrites commit history, so it should be avoided on commits that have already been shared with other developers. Merge creates an additional merge commit, which can make the history more complex, but it is safer for shared branches. Therefore, I would generally use rebase for cleaning up my own feature branch before integration and merge when preserving shared project history is more important.
