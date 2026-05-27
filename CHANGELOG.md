# Changelog


## [v2026.05.27] - 2026-05-27

### Added
- Shorebird setup has been implemented to enhance the development environment.
- Code signing setup has been added to ensure secure and authenticated builds.
- Android deploy action using fastlane has been set up to streamline the deployment process.
- Fastlane has been configured for Android to automate tasks and workflows.
- The Facebook logo in the about page has been downscaled to improve visual consistency.
- Version name is now displayed in the about us section to provide transparency and clarity.

### Changed
- The release-scribe action version has been updated to 1.0.1 to incorporate the latest features and improvements.
- Java 17 is now used in the GitHub action to leverage its enhanced performance and security features.
- The rexml library in the iOS project has been updated from 3.2.8 to 3.3.9 to address potential security vulnerabilities and improve parsing efficiency.
- The Android gradle plugin has been migrated to a newer version to take advantage of its improved features and bug fixes.
- The package name in MainActivity has been fixed to ensure correct identification and functionality.
- The build number is now used to determine the version code to maintain consistency and accuracy.
- The version name is now retrieved from a Flutter environment variable to allow for dynamic and flexible versioning.
- The GitHub ref name is used to trigger tags to automate the release process.
- The Playstore internal track and TestFlight now use the Flutter name to maintain consistency across platforms.

### Removed
- The 'v' prefix has been removed from the version tag to simplify versioning and reduce unnecessary characters.
- The bundle exec command has been removed from fastlane to streamline the execution process.

### Fixed
- The Android metadata has been updated to ensure accuracy and completeness.
- The keystore is now decoded on CI to facilitate secure and automated builds.
- The api key path has been updated to point to the latest build number to ensure correct authentication and authorization.

### Security
- The rexml updates from 3.2.8 to 3.3.9 address potential security vulnerabilities to protect against parsing-based attacks.
