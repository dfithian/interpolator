# Releasing

Outline for releasing this package to Hackage and Stackage

## Steps

* `git tag <version> -m "Release version <version>"`
* `git push origin --tags`
* `stack sdist`
* Copy to a folder that can be navigated to for upload
* Upload here: http://hackage.haskell.org/packages/upload
* `scripts/hackage-docs.sh <user>`
* Create stackage PR if needed
