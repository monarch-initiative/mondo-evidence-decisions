# mondo-evidence-decisions

Curator sign-off decisions for the [Mondo evidence browser](https://yaseminbridges.github.io/mondo-evidence-browser/).

The sign-off service commits each decision here as its own file:

```
decisions/<shard>/<record id>/<time>_<decision id>.json
```

Files are only ever added, never changed, so git history is the audit trail. The
browser's Pages build reads this repository to set each record's review status.

Don't edit by hand; see the browser repository's
[DEPLOY.md](https://github.com/yaseminbridges/mondo-evidence-browser/blob/main/DEPLOY.md).
