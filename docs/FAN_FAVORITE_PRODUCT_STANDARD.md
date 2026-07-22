# Fan-Favorite Product Standard

This standard applies to every flagship product in the Bobby’s Workshop and Blue Phoenix Studios portfolio. It does not require every product to look identical. It requires every product to feel intentional, trustworthy, memorable, and cared for.

## 1. Product identity

A flagship must have:

- one clear public name
- one sentence explaining who it serves and what it does
- a defined relationship to the rest of the ecosystem
- a recognizable visual and verbal identity
- an honest maturity label
- a documented list of what the product does not own

A repository fails this gate when its README contradicts another flagship’s ownership claims or presents an internal component as several different products.

## 2. First ten minutes

A new user must be able to:

1. understand the product from the repository landing page
2. see authentic screenshots or a working demo
3. install or launch it with a documented supported path
4. complete one meaningful task
5. understand where their data is stored
6. recover from the most common setup failure

No placeholder screenshots, dead download buttons, fictional installers, or undocumented environment requirements.

## 3. Interaction quality

Every user-facing flagship must provide:

- coherent navigation and information hierarchy
- keyboard support and visible focus states
- accessible labels and contrast
- responsive layouts for supported screen sizes
- useful empty, loading, error, offline, and permission states
- undo, confirmation, or rollback for meaningful mutations
- stable terminology across UI, docs, and release notes
- performance budgets for startup, interaction latency, and bundle size

Animation must clarify state or add character. It must not delay routine work or disguise missing functionality.

## 4. Reliability gates

Before a product may claim release readiness, its supported build path must include:

- locked dependency installation
- formatting and static analysis
- type checking where applicable
- unit tests
- integration or contract tests
- smoke tests for build artifacts and entry points
- end-to-end tests for critical user journeys
- forced-failure and recovery tests
- artifact checksums and retained CI logs

A formatting command is not a linter. A generated file is not proof that the generator works. A green job is not proof of hardware behavior unless hardware participated.

## 5. Safety, privacy, and security

Each flagship must document:

- data collected and stored
- permissions requested and why
- authentication and authorization boundaries
- secret-management rules
- update and rollback behavior
- vulnerability reporting
- dependency and software-bill-of-materials practices
- deletion and export paths for user data

Device, repair, recovery, identity, and personal-insight products must fail closed when authority, ownership, consent, target identity, or operation support cannot be proven.

## 6. Documentation set

Every maintained flagship repository should contain:

- `README.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `LICENSE`
- `CHANGELOG.md`
- `ROADMAP.md`
- `SUPPORT.md`
- `CODE_OF_CONDUCT.md`
- architecture and product-boundary documentation
- setup, development, test, build, release, and rollback instructions
- known limitations

Documentation must describe the current code, not an imagined future release.

## 7. Repository hygiene

A polished repository has:

- a deliberate default branch
- branch protection appropriate to risk
- required CI checks
- focused pull requests
- issue and pull-request templates
- dependency update policy
- release tags and changelogs
- no committed secrets, generated junk, pasted chat logs, duplicate source trees, or obsolete “COMPLETE” declarations in active documentation
- an archive area for historical material that still has value

Large assets must have a documented storage strategy and must not make normal cloning absurdly expensive.

## 8. Release evidence ladder

Use the highest level actually earned:

1. `DESIGNED`
2. `PROTOTYPE`
3. `UNIT_VALIDATED`
4. `INTEGRATION_VALIDATED`
5. `QEMU_VALIDATED` or equivalent virtual-environment proof
6. `HARDWARE_VALIDATED`
7. `SECURITY_REVIEWED`
8. `REPRODUCIBLE`
9. `PRODUCTION_CANDIDATE`
10. `PRODUCTION_RELEASE`

A higher level inherits every required lower-level proof.

## 9. Community readiness

A future fan favorite needs a path for people to care about it:

- public roadmap with near-term focus
- issue labels for bugs, accessibility, performance, onboarding, good first issues, and design
- discussion or feedback channel
- contribution guide with a small successful first contribution
- screenshots, short demonstrations, release notes, and meaningful version history
- respectful moderation and a code of conduct
- clear separation between canonical direction and community experiments

## 10. Delight and continuity

Polish is not only defect removal. Each flagship should have:

- one signature interaction or capability people remember
- consistent microcopy and tone
- thoughtful defaults
- fast repetition of frequent tasks
- continuity across updates
- migration paths that preserve user work
- easter eggs or personality only where they do not compromise accessibility or seriousness

## 11. Product-specific signature goals

- **ARCWYRE Native:** recovery-first sovereignty, verifiable operation, and graceful failure
- **PhoenixCore:** trustworthy device understanding and clear recommended actions
- **Phoenix Key / BootForge:** the safest and clearest path from diagnosis to approved boot media
- **Bobby’s Workshop:** a professional repair workspace that makes complexity manageable
- **Soul Codex:** beautiful, grounded personal insight with transparent confidence and privacy
- **Kai-Jax:** responsive combat, memorable heroes, emotional continuity, and replayable mastery
- **Phoenix Creator Studio:** the fastest path from scattered ideas to production-ready story assets
- **Ghost Writer:** frictionless capture, transformation, and publishing without losing the author’s voice
- **Rainstorms:** joyful guided creation that turns a child’s idea into a coherent story experience

## 12. Definition of fan-favorite readiness

A product reaches fan-favorite readiness when:

- new users can succeed without private guidance
- returning users trust updates not to destroy their work
- the product has a distinctive reason to exist
- critical journeys are fast, tested, accessible, and recoverable
- public claims match retained evidence
- community members can understand, use, discuss, and improve it
- the team can maintain it without heroics

Popularity cannot be guaranteed. The conditions for enduring affection can be engineered.
