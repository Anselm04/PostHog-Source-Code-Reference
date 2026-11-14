# PostHog — TrillionAI engineering research reference

Dedicated source-code research for [PostHog](https://github.com/PostHog/posthog), focused on event analytics, product funnels, feature flags, activation, retention, and usage reporting for TrillionAI AppForge, Marketing, and Manager.

## Verified source and licence boundary

PostHog's root `LICENSE` identifies the non-enterprise portions as MIT-licensed and the top-level `ee/` subtree as subject to a **separate commercial licence**. The commercial `ee/` files are **not being mirrored into this public reference repository**. The original root licence and copyright notices will remain in the retained community snapshot.

- Pinned upstream repository: `PostHog/posthog`, branch `master`
- Pinned original commit: `a081bda2be64e0520cec834fab22e1d66a670864`
- Unfiltered source tree: `f9042776f58f0d6e7bc01606ad4dc7a5d7c4078b`
- Destination branch: [`posthog-upstream-snapshot`](https://github.com/Anselm04/PostHog-Source-Code-Reference/tree/posthog-upstream-snapshot/upstream), containing `upstream/` after import
- **71,145 community Git-tracked files retained**, from **71,984 upstream files**; **839** files in the separately licensed `ee/` directory excluded.
- Verified filtered Git tree: `012523f26af8f806b43d98a24387b430154721ef`
- [Successful import and integrity verification](https://github.com/Anselm04/PostHog-Source-Code-Reference/actions/runs/43538138742)

**The GitHub Actions job passed remote filtered-tree integrity verification.** Filtered Git trees do not match the original unfiltered tree, by design. An imported snapshot is not a full historical mirror, complete cloud backend, LFS payload or submodule checkout.

## Engineering use

Compare real instrumentation, conversion and retention data pipelines with the existing TrillionAI products. Independently engineer and test TrillionAI implementations. Never merge reference branches into commercial repositories or activate PostHog paid services simply for this source archive.
