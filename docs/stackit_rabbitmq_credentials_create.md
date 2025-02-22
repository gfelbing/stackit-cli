## stackit rabbitmq credentials create

Creates credentials for an RabbitMQ instance

### Synopsis

Creates credentials (username and password) for an RabbitMQ instance.

```
stackit rabbitmq credentials create [flags]
```

### Examples

```
  Create credentials for an RabbitMQ instance
  $ stackit rabbitmq credentials create --instance-id xxx

  Create credentials for an RabbitMQ instance and hide the password in the output
  $ stackit rabbitmq credentials create --instance-id xxx --hide-password
```

### Options

```
  -h, --help                 Help for "stackit rabbitmq credentials create"
      --hide-password        Hide password in output
      --instance-id string   Instance ID
```

### Options inherited from parent commands

```
  -y, --assume-yes             If set, skips all confirmation prompts
      --async                  If set, runs the command asynchronously
  -o, --output-format string   Output format, one of ["json" "pretty"]
  -p, --project-id string      Project ID
```

### SEE ALSO

* [stackit rabbitmq credentials](./stackit_rabbitmq_credentials.md)	 - Provides functionality for RabbitMQ credentials

