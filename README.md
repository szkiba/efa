# ｅｆａ

**Set go flag values ​​from the environment**

The **efa** library enables setting go flag values ​​from environment variables. The name of the environment variable can be generated from the flag name (and an optional prefix) or can be specified directly.

### Features

- supports the standard go [flag package](https://pkg.go.dev/flag)
- supports the [spf13/pflag](https://github.com/spf13/pflag) package
- can be used with the [spf13/cobra](https://github.com/spf13/cobra) package
- supports prefixed environment variables
- can automatically prefix from the executable name
- annotate flags with the environment variable name
- has no dependencies

