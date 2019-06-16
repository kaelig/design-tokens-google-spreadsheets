# Design tokens (demo project)

- Managed with Google Spreadsheets ([see source](https://docs.google.com/spreadsheets/d/1O0QOUUq8N-NfHmlGWa61TN6oOSdQMBaDq0lp6DsCReQ/edit#gid=0))
- Generated by [Theo](https://github.com/salesforce-ux/theo), using [`google-spreadsheets-theo`](https://www.npmjs.com/package/google-spreadsheets-theo)
- Published to npm as [`design-tokens-test`](https://www.npmjs.com/package/design-tokens-test)

## Quick start

1. Clone the repository and install the dependencies:

   ```
   git clone https://github.com/kaelig/google-spreadsheets-theo-demo.git
   cd google-spreadsheets-theo-demo
   yarn
   ```

2. Edit tokens in the spreadsheet
3. Run `yarn build-tokens`

This should appear:

```
yarn build-tokens
yarn run v1.12.3
$ yarn clean
$ rimraf tokens
$ node ./build-tokens.js
✔ Design tokens written to ./tokens/colors.scss
✔ Design tokens written to ./tokens/colors.common.js
✔ Design tokens written to ./tokens/colors.android.xml
✔ Design tokens written to ./tokens/colors.ios.json
✔ Design tokens written to ./tokens/spacing.scss
✔ Design tokens written to ./tokens/spacing.common.js
✔ Design tokens written to ./tokens/spacing.android.xml
✔ Design tokens written to ./tokens/spacing.ios.json
✨  Done in 2.29s.
```

The design tokens in `./tokens/` should be updated.
