A tool to export a system's user information

The command will be able to export user names, IDs, home directories, and shells as either JSON or CSV

By default, the command will display the information as JSON to Stdout, but the --format flag will allow a person to specify csv as an alternative export type.

Additionally, a file can be specified by using the --path flag. Here are the various ways that the tool can be used

$ hr --format=csv --path=path/to/users.csv
$ hr --path=path/to/users.json
$ hr --format=csv
