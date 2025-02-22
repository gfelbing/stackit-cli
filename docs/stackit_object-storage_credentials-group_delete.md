## stackit object-storage credentials-group delete

Deletes a credentials group

### Synopsis

Deletes a credentials group. Only possible if there are no valid credentials (access-keys) left in the group, otherwise it will throw an error.

```
stackit object-storage credentials-group delete CREDENTIALS_GROUP_ID [flags]
```

### Examples

```
  Delete a credentials group with ID "xxx"
  $ stackit object-storage credentials-group delete xxx
```

### Options

```
  -h, --help   Help for "stackit object-storage credentials-group delete"
```

### Options inherited from parent commands

```
  -y, --assume-yes             If set, skips all confirmation prompts
      --async                  If set, runs the command asynchronously
  -o, --output-format string   Output format, one of ["json" "pretty"]
  -p, --project-id string      Project ID
```

### SEE ALSO

* [stackit object-storage credentials-group](./stackit_object-storage_credentials-group.md)	 - Provides functionality for Object Storage credentials group

