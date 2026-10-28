# Contributing to Minted

Thanks for helping. Small, focused pull requests are easiest to review. If you are unsure where to start, look for issues labeled `good first issue`.

## Build and test

You need Swift 5.9 or later and Xcode 15 or later, for iOS 17 or later. This is a Swift package, so it builds and tests with SwiftPM:

```bash
swift build
swift test
```

Run the tests before opening a pull request, and note the result in the pull request description.

## Opening a pull request

1. Fork the repository and create a branch for your change.
2. Keep the change focused on one thing, and add or update tests where the change needs them.
3. Open the pull request against `main`, describe what changed and why, and link any related issue.

## Code style

Match the style of the file you are changing, and add doc comments for new public API, as the surrounding code does.
