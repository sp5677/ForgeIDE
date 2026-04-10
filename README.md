# Blockly

Blockly is a library that adds a visual code editor to web and mobile apps. The Blockly editor uses interlocking, graphical blocks to represent code concepts like variables, logical expressions, loops, and more. It allows users to apply programming principles without having to worry about syntax or the intimidation of a blinking cursor on the command line. All code is [free and open source](https://github.com/raspberrypifoundation/blockly/blob/develop/LICENSE).

![Sample](./sample.svg)

## Getting Started with Blockly

Blockly has many resources for learning how to use the library. Start at our [Developers Site](https://developers.google.com/blockly) to read the documentation on how to get started, configure Blockly, and integrate it into your application. The developers site also contains links to:

- [Getting Started article](https://developers.google.com/blockly/guides/get-started/web)
- [Getting Started codelab](https://blocklycodelabs.dev/codelabs/getting-started/index.html#0)
- [More codelabs](https://blocklycodelabs.dev/)
- [Demos and plugins](https://raspberrypifoundation.github.io/blockly-samples/)

Help us focus our development efforts by telling us [what you are doing with Blockly](https://developers.google.com/blockly/registration). The questionnaire only takes a few minutes and will help us better support the Blockly community.

### Installing Blockly

Blockly is [available on npm](https://www.npmjs.com/package/blockly):

```bash
npm install blockly
```

For more information on installing and using Blockly, see the [Getting Started article](https://developers.google.com/blockly/guides/get-started/web).

### Getting Help

- [Report a bug](https://developers.google.com/blockly/guides/modify/contribute/write_a_good_issue) or file a feature request on GitHub
- Ask a question, or search others' questions, on our [developer forum](https://groups.google.com/forum/#!forum/blockly). You can also drop by to say hello and show us your prototypes; collectively we have a lot of experience and can offer hints which will save you time. We actively monitor the forums and typically respond to questions within 2 working days.

### blockly-samples

We have a number of resources such as [examples](https://github.com/raspberrypifoundation/blockly-samples/tree/main/examples), [codelabs](https://github.com/raspberrypifoundation/blockly-samples/tree/main/codelabs), and [plugins](https://github.com/raspberrypifoundation/blockly-samples/tree/main/plugins) in another repository called [blockly-samples](https://github.com/raspberrypifoundation/blockly-samples). A plugin is a self-contained piece of code that adds functionality to Blockly. Plugins can add fields, define themes, create renderers, and much more. For more information, see the [Plugins documentation](https://developers.google.com/blockly/guides/programming/plugin_overview).

## Contributing to Blockly

Want to make Blockly better? We welcome contributions to Blockly in the form of pull requests, bug reports, documentation, answers on the forum, and more! Check out our [Contributing Guidelines](https://developers.google.com/blockly/guides/modify/contributing) for more information. You might also want to look for issues tagged "[Help Wanted](https://github.com/raspberrypifoundation/blockly/labels/help%20wanted)" which are issues we think would be great for external contributors to help with.


### Branches

Most development happens in the **[main](https://github.com/raspberrypifoundation/blockly/tree/main)** branch. Pull requests should typically be made against main. This branch should be stable; features that aren't ready yet should be merged to a feature branch instead. Once something is in main we expect it to be part of the next release. However, features and APIs here are subject to change until they are released. If you're working on a production application using Blockly, you should use the release from npm or the GitHub release page, not the `main` branch.

Larger changes may have their own branches until they are good enough for people to try out. These will be developed separately until we think they are almost ready for release. They will be merged into main when ready.

### New APIs

Once a new API is released, it is considered beta until the following release. We generally try to avoid changing an API after it has been released, but sometimes we need to make changes after seeing how an API is used. If an API has been around for at least two releases we'll do our best to avoid breaking it.

Unreleased APIs may change radically. Anything that is in `main` but not released is subject to change without warning.

## Issues and Milestones

We typically triage all bugs within 1 week, which includes adding any appropriate labels and assigning it to a milestone. Please keep in mind, we are a small team so even feature requests that everyone agrees on may not be prioritized.

## Good to Know

- Cross-browser Testing Platform and Open Source <3 Provided by [Sauce Labs](https://saucelabs.com)
- We test browsers using [BrowserStack](https://browserstack.com)
