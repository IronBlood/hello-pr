# Hello PR

This repo demonstrates a minimal GitHub Actions workflow (`.github/workflows/hello-pr.yml`) that watches for pull requests being opened or updated and immediately posts a `helloworld` comment back to the PR. The `say_hello` job runs on `ubuntu-latest`, uses the built-in `GITHUB_TOKEN`, and calls the GitHub REST API via `curl` to send the comment.

Check out [#1](../../pull/1) for more details.
