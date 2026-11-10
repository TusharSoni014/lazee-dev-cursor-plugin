# lazee.dev Jobs for Cursor

Search open tech jobs from Cursor's agent. lazee.dev reads open roles from
company career pages every 12 hours and tags each one by role, seniority,
country and workplace.

This plugin connects Cursor to the lazee.dev Jobs MCP server
(`https://lazee.dev/mcp`) and adds a skill for finding jobs that fit what you
ask for.

## Tools

- `search_jobs`: filter by role, level, region, remote/hybrid/on-site, company,
  yearly pay range and posting date. Returns up to 25 jobs a page with the
  link to apply on the company's site.
- `get_job`: details of one job.
- `list_job_filters`: every accepted filter value and exact company names.
- `get_job_stats`: how many jobs and companies are tracked and when they were
  last refreshed.

All tools are read-only.

## Sign-in

The first time the agent uses it, a lazee.dev page opens: sign in with your
lazee.dev account and select Allow. No API key needed. Every tool call counts
toward your lazee.dev account's monthly limit.

## Links

- Docs: https://lazee.dev/mcp-server
- Privacy: https://lazee.dev/privacy
- Terms: https://lazee.dev/terms
- Support: support@lazee.dev
