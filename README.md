# npm-statistics

![NPM Stats](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fmaddhruv%2Fnpm-statistics%2Fmaster%2Fstats.json)

NPM Download Statistics for maddhruv's Open Source Projects. Updated Daily.

## Downloads

<!-- Please do not modify this auto generated content -->
<!-- AUTO-GENERATED-CONTENT:START (PACKAGES) -->
| Name                                                 | Downloads                                                                            |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------ |
| [error](https://www.npmjs.com/package/error)         | Internal Server Error                                                                |
| [path](https://www.npmjs.com/package/path)           | /npm-stat/api/download-counts                                                        |
| [status](https://www.npmjs.com/package/status)       | 0                                                                                    |
| [timestamp](https://www.npmjs.com/package/timestamp) | 2024-06-12T01:58:05.255+00:00                                                        |
| **Sum**                                              | **Internal Server Error/npm-stat/api/download-counts02024-06-12T01:58:05.255+00:00** |
<!-- AUTO-GENERATED-CONTENT:END -->

### Wanna use `npm-statistics`?

1. `Fork` this repository.
2. Add your npm username/author or list of packages in `package.json` as `npm-stats` key.
   for author

```js
{
  "npm-stats": "cleartax"
}
```

or for packages

```js
{
  "npm-stats": [
    "post-merge-install",
    "engines-ok"
  ]
}
```

3. Run `npm i` and then `npm start` to generate the Downloads.
4. The repo comes with a daily CRON job that updates the Downloads.
5. For updating the badge replace `ClearTax` in badge endpoint to your github username/orgname.
   https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F`username`%2Fnpm-statistics%2Fmaster%2Fstats.json
6. Enable `GitHub Actions` for your forked repo, as it is disabled by default for forks.

## Ref

- [npmtotal](https://github.com/maddhruv/npmtotal) - Find you npm download statistics
