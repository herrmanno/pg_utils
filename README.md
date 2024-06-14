# pg_utils

Tools for taking snapshots of databases and restoring databases from snapshots.

## Install

```sh
cp pg_snapshot pg_rollback /usr/local/bin
chmod +x /usr/local/bin/pg_{snapshot,rollback}

cp pg_rollback_completion pg_snapshot_completion ~/.bash_completion.d
```

## Usage

```sh
pg_snapshot <existing db name> <suffix>
```

```sh
pg_rollback <existing db name w/ suffix>
```


