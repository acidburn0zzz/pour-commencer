# Pour commencer

An action for filtering pull requests and issues from the initial begining point an user evolve under a contributors.

# Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: actions/first-interaction@v1
  with:
    repo-token: ${{ secrets.GITHUB_TOKEN }}
    issue-message: '# Message with markdown.\nThis is the message that will be displayed on users' first issue.'
    pr-message: 'Message that will be displayed on users' first pr. Look, a `code block` for markdown.'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
