Read .codex/patch-stack.yaml.

Create a new feature branch named feature/<name>.

Create a worktree under:

.codex/worktrees/<name>

Add the feature to patch-stack.yaml with the next available order.

Do not modify integration/latest.

Return:
- created branch
- worktree path
- patch-stack.yaml diff
