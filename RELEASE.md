# Releasing

1. Ensure version is updated in `mix.exs`
2. Test build `mix hex.build`
3. Update version in `README.md`, `CHANGELOG.md`, and `mix.exs`
4. Commit with message `Bump version to XXXXXX`
5. Git Push `git push origin`
6. Tag release with `git tag -a vXXXXXX`
7. Git push tags `git push origin --tags`
8. Push package `mix hex.publish`
