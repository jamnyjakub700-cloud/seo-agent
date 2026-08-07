# SEO Agent

An SEO auditor that does the whole workflow rather than handing you a dashboard.
It monitors a site continuously, finds issues, tracks keyword rankings, measures
visibility in AI-powered search engines, opens pull requests for the fixes it can
make itself, and reports what genuinely needs a human.

## What it does

- **Audits continuously** rather than on demand, so regressions surface when they
  happen instead of at the next manual review.
- **Fixes autonomously where it is safe to.** Changes arrive as pull requests, so
  every automated edit is reviewable and revertible before it reaches production.
- **Separates what it fixed from what it cannot.** The report is the part that
  needs judgement, not a list of everything it noticed.
- **Measures AI-search visibility** alongside classic ranking data, because a
  page can rank well and still never be cited in an AI-generated answer.
- **Runs conversationally.** One interface drives audit, analysis, fix and report
  rather than four separate tools.

## Code

This repository holds the description. The implementation lives in a private
repository.

Happy to walk through how it is built: **[jakubjamny.com](https://jakubjamny.com)**

## License

MIT, see [LICENSE](LICENSE).
