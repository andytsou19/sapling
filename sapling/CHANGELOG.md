# Change Log

All notable changes to the "sapling" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [1.0.0] - [Initial Release] - 2021-10-5

### Added
- Initial release of Sapling VSCode Extension
- Features:
  - Parses React applications written in JSX syntax with ES6 import syntax
  - Interactive sidebar webview displays component hierarchy
  - Files corresponding to each component can be opened from webview
  - Status bar button allows tree to be built from currently opened file
  - Identifies and displays JSX props
  - Identifies components connected to Redux store when exported with `connect` from `react-redux`
  - Maintains tree state when sapling is opened/closed or workspace is opened/closed
  - Automatically updates tree view on file save
  - Windows / WSL / Linux / MacOS compatible