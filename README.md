# PoC for Discourse Community -> Coveo Integration

index.html is the Coveo results page, this is what needs to be hosted somewhere. It is a single file with all things embedded (including header logo).

  - This page contains a *public* API key that is read-only, for non-prod.

discourse.html is what would need to be disected and used on the Community Discourse site.

This currently works as a header element in Discourse at: https://jury.trydiscourse.com/, and is also available here: https://kward-influx.github.io/discourse.html

Note: we tried to use the Coveo stand-alone search box within Discourse, but had numerous issues with it - hence the stripped down version that is currently implemented.

It will probably need to be massaged to work elsewhere within the layout (outside of header)
