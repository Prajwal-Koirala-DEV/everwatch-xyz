`main`

This branch represents the cutting edge of development, providing the absolute latest build. While generally functional, it may occasionally contain unintentional issues.

`dev`

The dev branch houses the most recent fully-tested build. It is typically functional, but you can refer to the list of known "bad" dev builds for potential issues. We continuously aim to merge changes from the master branch into dev, subjecting it to a more extensive testing process than the master branch during development.

`beta`

On a monthly basis, we select the "best" dev build from the preceding month and elevate it to the beta channel. These builds have undergone testing.

`stable`

When we deem a build particularly reliable, we promote it to the stable channel. Our goal is to do this approximately every quarter, though this timing may vary. For all production app releases, we recommend using this channel. While we plan to release hotfixes to the stable channel for high-priority bugs on rare occasions, such occurrences will be infrequent.
