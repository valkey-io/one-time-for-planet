
<!-- 6789 123456789 123456789 123456789 123456789 123456789 123456789 123456789 -->

# One-time for Planet

One-time links as an Atom Feed for Planet Valkey.

This repository contains a feed file, [feed.xml](https://github.com/valkey-io/one-time-for-planet/blob/main/feed.xml),
which is aggregated by [Planet Valkey](https://planet.valkey.io/).

<!-- 6789 123456789 123456789 123456789 123456789 123456789 123456789 123456789 -->

By adding entries to this file, it is possible to include content to Planet Valkey
that would otherwise be difficult to aggregate.  This includes news sources
without a feed, filtered subscriptions that excludes relevant posts, or sources
which are not worth adding.

More information can be found in the [Allow one-off posts](https://github.com/oursqlcommunity-org/planet/issues/145)
issue on the [Planet for the MySQL Community](https://planet.oursqlcommunity.org/) repository.

<!-- 6789 123456789 123456789 123456789 123456789 123456789 123456789 123456789 -->

If you know of an interesting post missing from Planet Valkey, open an issue,
or even better, submit a PR.

<!-- 6789 123456789 123456789 123456789 123456789 123456789 123456789 123456789 -->

## Technical notes

For fixing content-type:
* https://groups.google.com/g/brython/c/M--O59kY6GA?pli=1
* https://raw.githack.com/

<!-- 6789 123456789 123456789 123456789 123456789 123456789 123456789 123456789 -->

### Checklist

Adding an entry is error-prone.  Use the checklist below:

- make changes in a branch so multiple commits can be squashed-merged
  (more than one commit might be needed to fix xml errors);

- before merging, validate the file with a feed validator
  like [Feed Validator](https://www.feedvalidator.org/) (easier to use, but http only)
  or [W3C Markup Validation Service](https://validator.w3.org/) (more complete, reporting minor errors);

- the URL for the file to be validated can be generated with [rawgit.hack](https://raw.githack.com/).

<!-- EOF -->
