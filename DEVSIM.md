# LearnSpace Student Portal

Business brief: Students need one place to discover courses and track their learning. Build a React interface with accessible navigation, course filtering, loading/empty states and a progress dashboard. Milestones: 1. Responsive course listing; 2. Validated enrollment form; 3. Dashboard and component tests. Create a TypeScript React project, use fixture data initially and document setup. Deliver implementation, tests and README. No pre-existing repository is bundled.

## DevSim ticket workflow
Clone this repository. Create a feature branch using the exact ticket key below. Push changes and open a PR against the default branch. DevSim links PRs authored by your connected GitHub account automatically.

### LEA-BC92-101: Build the first resource listing
Branch: `feature/lea-bc92-101`

- Return the resource list with a predictable data shape.
- Handle an empty dataset without crashing.
- Add tests for normal and empty results.

### LEA-BC92-102: Validate resource creation
Branch: `feature/lea-bc92-102`

- Reject blank required fields with a clear error.
- Create a record for valid input.
- Add tests for valid and invalid input.

### LEA-BC92-103: Handle missing resources
Branch: `feature/lea-bc92-103`

- Return a clear not-found result for unknown IDs.
- Preserve the successful retrieval behavior.
- Test existing and missing IDs.

