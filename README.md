# DependGuard GitHub Action

Automatically scan dependencies on every push/PR.

```yaml
jobs:
  dependguard:
    runs-on: ubuntu-latest
    steps:
      - uses: dependguard/action-scan@main
        with:
          server-url: http://your-dependguard-server.com
