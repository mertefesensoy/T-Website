# Force-push retention test

Scratch harness for an empirical test of what happens to a commit object
on GitHub after it is amended and force-pushed away.

Questions under test:
1. Does the original (pre-amend) commit object still exist on the remote?
2. Does merging the PR drag that commit's authorship into main or the
   repository contributor graph?
