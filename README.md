# Caskly Community Feedback

Welcome to the Caskly community feedback repository! This is where you can report bugs, request features, ask questions, and discuss improvements for [Caskly](https://caskly.app).

## About Caskly

Caskly is a native macOS app that helps you adopt your existing applications to Homebrew management. Your existing apps become Brew casks. Updates become a breeze. All done through Caskly. It's that easy.

**🚨 This repository is for feedback only - source code is not available here.**

## How to Contribute

### 🐛 Report a Bug

Found something broken? [Create a bug report](../../issues/new?template=bug_report.md) with:

- Steps to reproduce
- Expected vs actual behavior
- Your macOS version and Caskly version
- Any relevant screenshots or logs

### 💡 Request a Feature

Have an idea to make Caskly better? [Submit a feature request](../../issues/new?template=feature_request.md) with:

- Clear description of the feature
- Use case or problem it solves
- Any mockups or examples (optional)

### ❓ Ask a Question

Need help or have general questions? [Start a discussion](../../issues/new?template=question.md) or check existing issues first.

### 🗳️ Vote on Features

Use GitHub reactions (👍 👎) on issues to show support for features or bugs you care about. This helps prioritize development.

## Before You Post

1. **Search existing issues** - your issue might already be reported
2. **Check the FAQ** below for common questions
3. **Use appropriate labels** - they help organize and prioritize issues

## FAQ

### General

**Q: Where can I download Caskly?**
A: Visit [caskly.app](https://caskly.app) for download links and more information.

**Q: Is Caskly free?**
A: Pricing information is available on our website at [caskly.app](https://caskly.app).

**Q: What macOS versions are supported?**
A: Caskly requires macOS 15.0 (Sequoia) or later.

### Troubleshooting

**Q: Caskly says Homebrew isn't installed, but I have it**
A: Caskly checks for Homebrew in standard locations:

- `/opt/homebrew/bin/brew` (Apple Silicon)
- `/usr/local/bin/brew` (Intel)

If you installed Homebrew elsewhere, Caskly may not find Homebrew. You can reinstall Homebrew from [brew.sh](https://brew.sh).

**Q: Why isn't my app showing up in the scan?**
A: Caskly only scans `/Applications` for `.app` bundles. Apps in other locations or non-standard formats may not be detected.

**Q: An app was matched to the wrong cask**
A: You can manually override the suggested cask name using 'Custom Cask' at any time.

### Privacy & Security

**Q: What data does Caskly collect?**
A: Caskly operates entirely locally on your Mac. No data is sent to external servers except for fetching Homebrew cask information from the official Homebrew API.

**Q: Is it safe to link my existing apps?**
A: Yes. Caskly uses standard Homebrew commands and doesn't modify your existing applications. It simply tells Homebrew to manage them going forward.

## Support

- 🌐 **Website**: [caskly.app](https://caskly.app)
- 📧 **Email**: [hello@hugeideas.ca](mailto:hello@hugeideas.ca)
- 🐛 **Bug Reports**: [Create an issue](../../issues/new?template=bug_report.md)

## Labels

We use these labels to organize issues:

- `bug` - Something isn't working correctly
- `enhancement` - New features or improvements
- `question` - General questions or support requests
- `good first issue` - Easy issues for new contributors
- `priority-high` - Critical bugs or important features
- `priority-low` - Nice-to-have improvements
- `wontfix` - Issues we've decided not to implement
- `duplicate` - Duplicate of another issue

## Code of Conduct

Please be respectful and constructive in all interactions. We're here to make Caskly better together!

---

Made with ❤️ by [Huge Ideas](https://hugeideas.ca)
