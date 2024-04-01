# git reflog

### Overview
`git rebase` 또는 `git reset` 등으로 삭제된 commit 이력을 복구할 수 있다.

### git history 복구
1. Commit 복구
* `git reflog` 로 삭제된 commit id 확인
* git reset —hard <commit_hash_id>

2. Branch 복구
* `git reflog` or `git reblog |grep <branch_name>` 로 history 확인
* `git checkout -b <deleted_branch_name> <commit_hash_id>