# Issue-ready roadmap

## 1. Configurable campaign goals
- [ ] Add target ROAS, minimum sample thresholds, and business margin inputs.
- [ ] Show the chosen assumptions beside each recommendation.
- [ ] Test defaults, boundaries, and incompatible settings.

## 2. CSV import and report export
- [ ] Add explicit field mapping and preview before evaluation.
- [ ] Reject mixed currencies and incompatible attribution periods.
- [ ] Export a self-contained review without raw customer identifiers.

## 3. Optional AI explanation adapter
- [ ] Keep provider keys in a server-side environment only.
- [ ] Ground explanations in validated metrics and cite rule evidence.
- [ ] Add mocked provider tests, timeout handling, and prompt-injection fixtures.
- [ ] Fall back to deterministic explanations on failure.

## 4. Browser and accessibility verification
- [ ] Add browser integration tests for editing, reset, validation, and narrow layouts.
- [ ] Test keyboard navigation and screen-reader feedback.

## 5. Read-only ad connector experiment
- [ ] Select a documented public API with explicit user authentication.
- [ ] Add a local consent and data-retention design before integration.
- [ ] Preserve the no-spend-changes boundary in the portfolio MVP.
