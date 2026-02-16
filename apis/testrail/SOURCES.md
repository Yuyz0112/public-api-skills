# TestRail API Sources

This spec is maintained only from official TestRail API documentation.

- Introduction: https://support.testrail.com/hc/en-us/articles/7077083596436-Introduction-to-the-TestRail-API
- Accessing API: https://support.testrail.com/hc/en-us/articles/7077039051284-Accessing-the-TestRail-API
- Projects: https://support.testrail.com/hc/en-us/articles/7077711537684-Projects
- Suites: https://support.testrail.com/hc/en-us/articles/7101756524180-Suites
- Sections: https://support.testrail.com/hc/en-us/articles/7101779988372-Sections
- Cases: https://support.testrail.com/hc/en-us/articles/7077292642580-Cases
- Runs: https://support.testrail.com/hc/en-us/articles/7077874763156-Runs
- Plans: https://support.testrail.com/hc/en-us/articles/7077792390932-Plans
- Tests: https://support.testrail.com/hc/en-us/articles/7077990441108-Tests
- Results: https://support.testrail.com/hc/en-us/articles/7077819312404-Results
- Milestones: https://support.testrail.com/hc/en-us/articles/7077860530324-Milestones
- Users: https://support.testrail.com/hc/en-us/articles/7077871554452-Users
- Statuses: https://support.testrail.com/hc/en-us/articles/7077935129364-Get-statuses

Notes:

- If an endpoint/parameter cannot be verified from the links above, it should be removed or marked TODO before release.
- Entity schemas intentionally allow unknown fields via `additionalProperties: true` to avoid undocumented assumptions.
