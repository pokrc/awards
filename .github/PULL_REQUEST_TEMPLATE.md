## Submission type

- [ ] Mathematical solver information
- [ ] Lean proof or formalization author information

Select both when applicable and remove sections that do not apply. Submit only
complete solutions and proof references, following the
[submission requirements](https://github.com/TheJustinSunPrize/awards/blob/main/CONTRIBUTING.md#external-solver-and-lean-submissions).
For claims, public review and challenges, see the
[award process](https://github.com/TheJustinSunPrize/awards/blob/main/docs/award-process.md).

The complete mathematical solution and its proof or publication evidence may be
provided before the Lean formalization or together with it in this PR. The
mathematical solver and Lean formalization author may be different people.
**A Lean submission without the mathematical solution and its supporting evidence
is invalid and will not be accepted.** Link the earlier solution or provide it
and its evidence below.

We recommend checking open, merged and closed PRs for the same problem and
contribution type before submitting. Linking related PRs and explaining how your
contribution differs can help avoid duplicate work. See the
[pre-submission suggestions](https://github.com/TheJustinSunPrize/awards/blob/main/CONTRIBUTING.md#before-opening-a-pr).

## Problem

- Problem ID(s): JSP-______
- Original problem source and exact location (page, section or problem number): REPLACE_WITH_LINK_AND_LOCATION
- Current entry and proposed change: REPLACE_WITH_DETAILS
- Related issue, if any: REPLACE_WITH_LINK_OR_NONE
- Related PRs and how this contribution differs, including any issue found in an existing submission and supporting evidence (optional): REPLACE_WITH_DETAILS_OR_REMOVE
- For solver/publication updates: public proof or publication, relevant theorem/pages, version or date: REPLACE_WITH_LINK_AND_DETAILS

Solver-only submissions complete Problem and Attribution and remove the Lean-only
sections. No Lean repository or self-check is required for those submissions.

## Formal statement

For Lean contributions only. Repeat the theorem details for each problem.

- Complete mathematical solution (provided earlier or in this PR): public proof or publication, relevant theorem/pages, version or date: REPLACE_WITH_LINK_AND_DETAILS
- Mathematical review reference or current review status: REPLACE_WITH_REFERENCE_OR_STATUS
- Formal statement location, pinned to a full commit SHA: REPLACE_WITH_LINK
- Fully qualified target theorem name: REPLACE_WITH_THEOREM_NAME
- Statement origin (maintainer-approved reference and version, or proposed statement requiring review): REPLACE_WITH_DETAILS
- Correspondence to the original problem: definitions, assumptions, quantifiers, conclusion and all required cases; explain any differences from an approved statement: REPLACE_WITH_EXPLANATION

## Proof submission

For Lean contributions only. Use the original repository containing your
contribution, owned by your submitting account or an organization. For an
organization repository, supply verifiable contribution evidence under Attribution.
**Link the proof; do not commit Lean source here.**
Add an object for each additional repository/version.

```json
[
  {
    "repository": "https://github.com/OWNER/REPOSITORY",
    "branch": "REPLACE_WITH_BRANCH",
    "commit": "REPLACE_WITH_FULL_40_CHARACTER_COMMIT_SHA"
  }
]
```

- Proof file at the selected commit and fully qualified theorem name: REPLACE_WITH_PATH_AND_THEOREM
- How the proof establishes the formal statement above, including any separate verification entry: REPLACE_WITH_DETAILS

The statement and proof may share a file. `Challenge.lean`, `Submission.lean`
and `Solution.lean` are optional naming conventions; existing layouts are accepted.

## Reproduction

For Lean contributions only.

- Exact Lean version and `lean-toolchain` path: REPLACE_WITH_VERSION_AND_PATH
- Pinned dependencies (including mathlib, if used) and manifest path: REPLACE_WITH_DETAILS
- Build instructions pinned to the selected commit: REPLACE_WITH_LINK
- Commands for setup, clean build and checking each target theorem; include a separate statement-to-proof check if needed: REPLACE_WITH_COMMANDS
- Axiom audit command and output for each target (for example, `#print axioms Fully.Qualified.theoremName`): REPLACE_WITH_COMMAND_AND_OUTPUT

Report all axiom dependencies. Standard Lean axioms are not automatically
disqualifying. An unfilled challenge template may contain `sorry` or `admit`, but
the submitted proof must not depend on those placeholders or added unproved assumptions.

## Pre-submission Lean verification (optional)

We recommend the [`lean-verify` skill](https://github.com/TheJustinSunPrize/awards/blob/main/skills/lean-verify/SKILL.md)
for Lean proofs. You may use another method or omit this section. Reports and logs
are optional; see the [self-check guidance](https://github.com/TheJustinSunPrize/awards/blob/main/docs/verification.md#recommended-lean-pre-submission-check).

- Method/tool and version, if available: REPLACE_WITH_METHOD
- Checked repository and full commit SHA; identify any difference from the submitted version: REPLACE_WITH_VERSION
- Verification date, actual conclusion and limitations: REPLACE_WITH_DETAILS
- Summary of statement correspondence, coverage, Lean checks and trust dependencies: REPLACE_WITH_SUMMARY
- Report in this PR or external report/log/evidence links, if available: REPLACE_WITH_REPORT_OR_LINKS

## Attribution

- Mathematical solver(s) and contribution, if applicable: REPLACE_WITH_NAMES_AND_CONTRIBUTIONS
- Lean formalization author(s) and contribution, if applicable: REPLACE_WITH_NAMES_AND_CONTRIBUTIONS
- Independent verifier(s), if any: REPLACE_WITH_NAMES_AND_ROLES_OR_NONE
- Public authorship evidence; for an organization repository, link verifiable evidence connecting your account to the claimed proof files/theorems (such as merged PRs, attributable changes or project authorship records). Explain mismatches between authors, accounts and proposed credits: REPLACE_WITH_LINKS_AND_EXPLANATION

## Submission checklist

- [ ] I changed only the relevant catalog's solver attribution, Lean proof information or supporting sources and supplied the applicable evidence.
- [ ] The submitted result fully solves the original problem. Any submitted Lean proof is complete at the specified commit, with no `sorry`, `admit` or added unproved assumptions replacing proof steps.
- [ ] For Lean: I have linked the complete mathematical solution and its proof or publication evidence provided earlier, or supplied them in this PR, and identified the mathematical solver and Lean formalization author separately.
- [ ] For Lean: I am claiming my own contribution in the original personal or organization repository, with verifiable contribution evidence for an organization repository; the selected commit is in the named branch, and I supplied statement correspondence, reproduction commands and axiom audit results.
- [ ] This PR contains no Lean source files, archives, binaries, vendored dependencies or private identity/contact/payment information.
