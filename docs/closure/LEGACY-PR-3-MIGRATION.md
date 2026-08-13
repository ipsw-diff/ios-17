# Legacy pull request 3 migration closure

Recorded: 2026-08-12

## Claim and scope

Question: can the 16 iOS 17 comparison subtrees submitted in
`blacktop/ipsw-diffs#3` be copied exactly from the contributor's immutable pull
request head into this archive shard, then cataloged without merging the stale
pull request into the legacy monolith?

- First lifecycle stage: select the exact iOS 17 root set added between pull
  request base `80869317ef5f4fc9e9cce6836e7f49b454bd11ac` and head
  `707bb335823a7869c2ec6f41f0ef88e6dc701183`.
- Last lifecycle stage: catalog entries independently verify the selected
  source subtrees against a merged `ios-17` default-branch commit.
- Supported claim after closure: the 16 named Git subtrees were faithfully
  migrated and cataloged with immutable source and destination provenance.
- Excluded: claiming which exact `ipsw` executable produced the rerun,
  regenerating diffs from IPSWs, merging or closing the legacy pull request,
  repairing its unrelated root README, and validating semantic correctness of
  the differ version used by the contributor.

## Authority map

| Property | Authority |
| --- | --- |
| Pull request base and head | GitHub pull request 3 and immutable Git commits |
| Exact migration membership | Added iOS 17 top-level roots between the pinned base and head |
| Versions, builds, and input filenames | Strictly parsed README in each selected head subtree |
| Device identity | Matching device token parsed independently from both IPSW inputs |
| Files, bytes, modes, and tree identity | Git objects at the pinned contributor head |
| Destination paths and manifests | Validated migration specs and deterministic staging |
| Release display labels | Exact records at the catalog's pinned AppleDB commit |
| Diff-generator version | Unresolved; comments establish a rerun but no exact final version |

## Review-time closure matrix

| Stage | Required evidence | Review status |
| --- | --- | --- |
| Selection and trigger | Diff-derived root set equals the reviewed 16-path allowlist | Closed |
| Inputs and resources | Every root has one valid two-IPSW README and matching device identities | Closed |
| Transformation | Atomic staging reproduces all 16 source trees and generated manifests | Closed |
| Advertisement and options | Generated archive README lists exactly the complete proposed shard inventory | Closed |
| Dispatch and transport | One unsigned shard commit contains only the bounded migration paths | Unresolved |
| State transition | Shard merge precedes catalog publication | Unresolved |
| Outcome oracle | All 16 catalog entries pass source-to-merged-destination audit | Unresolved |

The staged migration payload has Git tree
`113d6024b3efb0e67d43e22e57645625d4cce651`: 16 payloads, 42,315 source
files, 275,569,163 logical source bytes, and 42,331 staged payload and manifest
paths. The generated archive README contains the 16 proposed rows plus the 5
rows already on the shard's default branch, for 21 total comparisons.

## Expected inventory

The reviewed source set contains 16 payloads, 42,315 tracked files, and
275,569,163 logical bytes. All objects use mode `100644`.

- `17_0_21A329__vs_17_0_1_21A340`
- `17_0_1_21A340__vs_17_0_2_21A351`
- `17_0_2_21A350__vs_17_0_3_21A360`
- `17_0_3_21A360__vs_17_1_21B80`
- `17_1_21B80__vs_17_1_1_21B91`
- `17_1_1_21B91__vs_17_1_2_21B101`
- `17_1_2_21B101__vs_17_2_21C62`
- `17_2_21C62__vs_17_2_1_21C66`
- `17_2_1_21C66__vs_17_3_21D50`
- `17_3_21D50__vs_17_3_1_21D61`
- `17_3_1_21D61__vs_17_4_21E219`
- `17_4_21E219__vs_17_4_1_21E236`
- `17_4_1_21E236__vs_17_4_1_21E237`
- `17_4_1_21E237__vs_17_5_21F79`
- `17_5_21F79__vs_17_5_1_21F90`
- `17_5_1_21F90__vs_17_6_21G80`

## Negative-evidence audit

The contributor's statement that the diffs were rerun does not establish an
exact generator version. GitHub's current zero-file pull-request comparison is
also not evidence that the contribution is empty: the pinned base-to-head Git
comparison contains the 16 roots above. README-only payloads remain valid Git
subtrees but do not prove that the underlying firmware had no other semantic
changes. The three README-only payloads are
`17_0_21A329__vs_17_0_1_21A340`,
`17_0_1_21A340__vs_17_0_2_21A351`, and
`17_4_1_21E236__vs_17_4_1_21E237`. Some copied Markdown contains trailing
whitespace from the immutable source tree; it is preserved because normalizing
it would invalidate exact source-tree identity. Generated and
migration-authored files are checked separately.

## Stop conditions

Stop if the base, head, path set, inventory totals, README metadata, source
trees, staged trees, manifest facts, destination merge commit, or catalog audit
differs. Do not substitute a current fork branch for the pinned pull-request
head, and do not infer the missing generator version.

## Review-time bounded conclusion

Selection, source-input validation, atomic staging, and proposed archive
advertisement are closed. The unsigned commit and pull request, merged
destination state, and catalog publication remain unresolved. The exact final
`ipsw` generator version is explicitly unavailable and is outside the faithful
Git subtree migration claim.
