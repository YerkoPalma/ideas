# Relicense

> Change the license of your git repos

## description:

Change the license of all of your repos, or some of them. This might sound 
simple but it isn't always that simple, some licenses are compatible between 
them but some others not, and moving between means major (breaking) changes, the 
idea is to easily handle that.

Initially, it would work for Github client, but it should work for any git 
client with a stable API

So, api might look like this

```bash
$ relicense <gh-user> <license>
```

Above command would relicense **every** project from _gh-user_ to _license_. 
_gh-user_ could be a user or organization. By default, this should handle semver 
changes (minor change). When the license update implies a major change, user 
will be prompted to accept change. There should be an option to force change 
(make major changes without prompting) or to skip them (only make minor changes).

Also some filters should be added

```bash
$ relicense <gh-user/project> <license>     # Use specific project
$ relicense --lang=js <gh-user> <license>   # Only js projects (shortcut: -l js)
$ relicense --tag=js <gh-user> <license>    # Only web tagged projects (shortcut: -t web)
```