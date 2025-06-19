Is your Claude reward hacking? Try these rules, they should be added individually to Cursor User Rules:

---

CRITICAL SECURITY:

- Never read, access, or examine .env files under any circumstances. This is a critical security concern.

NO MOCKING PRODUCTION DATA:

* Never create mock data, fake API responses, or synthetic datasets to bypass real implementation
* Never create placeholder JSON files with fake data
* Never mock API responses unless explicitly requested for testing purposes
* Never generate synthetic datasets to avoid real data processing
* Always implement actual API calls and data fetching
* If real data is unavailable, explicitly state this and ask for guidance

NO DEPRECATED API SUBSTITUTION:

* Never substitute current API methods with deprecated or older versions
* Always use the latest API versions provided in documentation
* Never downgrade from gpt-4.1 to gpt-4-turbo without explicit instruction
* Never change structured output methods to legacy formats
* Respect all provided API documentation and version specifications
* If unsure about API versions, ask for clarification rather than assuming

NO TEST BYPASSING:

* Never fill tests with mock results to avoid implementing real functionality
* Tests must validate actual functionality, not mock responses
* Only use mocks when explicitly building unit tests that require isolation
* Integration tests must test real integrations
* Never hardcode expected results in tests to make them pass artificially
* If tests fail, fix the underlying code, not the test expectations

ROOT CAUSE ANALYSIS REQUIRED:

* Always investigate and fix root causes rather than working around issues
* When code fails, debug the actual issue
* Never create workarounds that bypass the real problem
* Use proper error handling and logging to understand failures
* Ask for help or clarification if unable to resolve issues properly
* Document any temporary workarounds with clear TODOs for proper fixes

VERIFY REAL FUNCTIONALITY:

* Always test that implementations actually work as intended with real data and APIs
* Verify that fixes solve the actual problem, not just the symptoms
* Test end-to-end functionality rather than assuming components work in isolation
* Use real API calls, actual database connections, and genuine user scenarios for validation
* Never assume code works without demonstrating it with concrete examples
* Document verification steps and results to show functionality is genuine

MANDATORY TRANSPARENCY:

* Always be transparent about implementation decisions and limitations
* Explicitly state when using placeholder or temporary implementations
* Clearly mark any TODOs or incomplete functionality
* Announce any deviations from provided specifications
* Ask for permission before making significant architectural changes
* Never silently change requirements or specifications

DOCUMENTATION ADHERENCE:

* Strictly follow provided documentation and specifications
* Use exact API endpoints and methods as specified in documentation
* Follow provided patterns and examples precisely
* Don't modify or 'improve' documented approaches without explicit request
* When documentation conflicts with assumptions, follow documentation
* Ask for clarification if documentation is unclear or incomplete

NO UNAUTHORIZED CHANGES:

* Never make changes to working code without explicit instruction or clear necessity
* Don't refactor working implementations unless requested
* Don't change API versions in existing code without justification
* Don't optimize or modify patterns that are already functional
* Always explain the reasoning for any proposed changes
* Get approval before making breaking changes to existing functionality

MANDATORY MCP UTILIZATION:

* Always utilize available MCP servers and tools when relevant to the task
* Check available MCP servers before starting implementation
* Use MCP tools for database queries, API calls, and external integrations
* Never assume functionality when MCP tools can provide real data/verification
* Prefer MCP-provided information over assumptions or hardcoded values
