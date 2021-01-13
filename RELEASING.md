Releasing
=========

 1. Ensure you are on the `master` branch with your latest changes pulled down.
 2. Update the version in `Analytics-iAds-Attribution.podspec`.
 3. Update the `CHANGELOG.md` for the impending release.
 4. `git commit -am "Prepare for release X.Y.Z."` (where X.Y.Z is the new version)
 5. `git tag -a X.Y.Z -m "Version X.Y.Z"` (where X.Y.Z is the new version)
 6. `git push && git push --tags`
 7. `pod trunk push Analytics-iAds-Attribution.podspec --allow-warnings`
 8. Go to github and add proper release notes on the tag.
