# PostHog — TrillionAI engineering research reference

Dedicated source-code research for [PostHog](https://github.com/PostHog/posthog), focused on event analytics, product funnels, feature flags, activation, retention, and usage reporting for TrillionAI AppForge, Marketing, and Manager.

## Original source and licence boundary

PostHog's root `LICENSE` identifies the non-enterprise portions as MIT-licensed and the top-level `ee/` subtree as subject to a **separate commercial licence**. The commercial `ee/` files are **not being mirrored into this public reference repository**. The original root licence and copyright notices will remain in the retained community snapshot.

- Pinned upstream repository: `PostHog/posthog`, branch `master`
- Pinned original commit: `a081bda2be64e0520cec834fab22e1d66a670864`
- Unfiltered source tree: `f9042776f58f0d6e7bc01606ad4dc7a5d7c4078b`
- Destination branch: [`posthog-upstream-snapshot`](https://github.com/Anselm04/PostHog-Source-Code-Reference/tree/posthog-upstream-snapshot/upstream), containing `upstream/` after import
- [Import and verification workflow](https://github.com/Anselm04/PostHog-Source-Code-Reference/actions/workflows/import-posthog-source.yml)

**Only mark imported after the GitHub Actions run passes the remote filtered-tree integrity check.** Filtered Git trees do not match the original unfiltered tree, by design. An imported snapshot is not a full historical mirror, complete cloud backend, LFS payload or submodule checkout.

## Engineering use

Compare real instrumentation, conversion and retention data pipelines with the existing TrillionAI products. Independently engineer and test TrillionAI implementations. Never merge reference branches into commercial repositories or activate PostHog paid services simply for this source archive.
