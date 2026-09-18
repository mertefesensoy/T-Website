# Force-push retention test — controlled run 3

Baseline commit for an independently instrumented run of the force-push
retention experiment, isolated on its own branch so it does not collide
with a concurrent run using `orphan-test`.

Every SHA in this run is recorded at the step that produced it, so the
fate of the pre-amend commit object can be measured exactly.
