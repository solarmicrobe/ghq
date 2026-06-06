Read .codex/patch-stack.yaml.

Recreate integration/latest.

Process:

1. Reset integration/latest to main/master.
2. Apply active feature branches in order.
3. Resolve conflicts.
4. Run tests.
5. Produce a report showing:
   - applied features
   - resulting commit graph
   - resulting SHA
