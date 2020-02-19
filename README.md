# npm-statistics

![NPM Stats](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fmaddhruv%2Fnpm-statistics%2Fmaster%2Fstats.json)

NPM Download Statistics for maddhruv's Open Source Projects. Updated Daily.

## Downloads

<!-- Please do not modify this auto generated content -->
<!-- AUTO-GENERATED-CONTENT:START (PACKAGES) -->
| Name                        | Downloads |
| --------------------------- | --------- |
| `post-merge-install`        | 3855      |
| `@cleartax/zoids`           | 3074      |
| `engines-ok`                | 2450      |
| `types-directory`           | 2339      |
| `good-first-issue`          | 2210      |
| `install-types`             | 1598      |
| `npmtotal`                  | 1304      |
| `web-workers`               | 791       |
| `prepublish-ok`             | 613       |
| `props-validator`           | 383       |
| `@arrant/button`            | 231       |
| `clean-node`                | 227       |
| `@arrant/theme`             | 206       |
| `check-web-workers-support` | 195       |
| `ipopen`                    | 166       |
| `@rabbitsm/rsm`             | 121       |
| `authorer`                  | 117       |
| `dumbbell`                  | 88        |
| `check-support`             | 75        |
| `goandget`                  | 70        |
| `enpmjs`                    | 57        |
| `clean-deps`                | 0         |
| **Sum**                     | **20170** |
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
