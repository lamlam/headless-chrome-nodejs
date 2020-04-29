# Chrome Headless Docker Action for Node.js

This action provide environment of Node.js, Chrome Headless and fonts to support major charsets.

# Example usage

```yml
# some github action setting
# ...
# after setup
- uses: lamlam/headless-chrome-nodejs@1.0.0
  with:
    args: yarn

- uses: lamlam/headless-chrome-nodejs@1.0.0
  with:
    args: yarn start
```
