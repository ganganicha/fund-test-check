- Create a proper test suite class to group smoke tests.
- Use `[TestPriority]` or `[ITestCaseOrderer]` to control execution order.
- Add retry logic for flaky tests.
- Parameterize test data for flexibility.

Long-Term

- Scale to 200+ tests with tagging and filtering.
- Integrate with CI/CD pipeline (e.g., GitHub Actions, Azure DevOps).
- Add visual regression testing.
- Implement API-level validations for faster feedback.
- Use environment configs for staging vs production.

Assumptions

- Robot detection bypass is allowed using the provided user agent.
- No contact/viewing requests are sent to real estate agents.
- Tests are run in a controlled environment (local or CI).

