You are maintaining a downstream fork.

Read .codex/patch-stack.yaml.

Tasks:

1. Checkout main/master.
2. Fetch upstream.
3. Fast-forward main/master to upstream.
4. Rebase every active feature branch onto main/master.
5. Resolve conflicts if possible.
6. Rebuild integration/latest by applying active features in order.
7. Run tests.
8. Produce a report showing:
   - upstream commit range
   - rebased branches
   - conflicts encountered
   - resulting integration/latest SHA
