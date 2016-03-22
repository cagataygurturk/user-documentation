Normally, after installing HHVM, you can use the [sensible defaults](../02-basic-usage/01-introduction.md) provided to [run Hack and PHP scripts](../02-basic-usage/02-command-line.md) or [run HHVM as a server](../02-basic-usage/03-server.md).

While a majority of the time you will not need to tweak the default settings or use the more advanced modes available with HHVM, they are available:

* [Repo Authoritative](./02-repo-authoritative.md) mode allows you to compile your entire codebase into one unit, allowing for HHVM to perform highly aggressive optimizations to make your code run quickly.
* [Daemon](./03-daemon.md) mode allows you to run HHVM as a background process.
* The [admin server](./04-admin-server.md) allows you to monitor HHVM as it is running in server mode.
* [FastCGI](../03-advanced-usage/05-fastCGI.md) is another server type for HHVM that is highly configurable and fast, but requires a separate web server on top of it.

## Custom Configuration

There are also a plethora of custom [configuration options](../04-configuration/01-introduction.md) that you can set to tweak how HHVM operates when running scripts or running as a server.
