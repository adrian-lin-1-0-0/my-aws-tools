# My AWS tools

## Installation

MacOS and linux:
```bash
sudo cp -r -n ./tools/* /usr/local/bin/
```

## Tools
- aws-env
    > Make working with multiple AWS accounts and roles easily.<br><br>
    [Configuration and credential file settings](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-files.html)
    
    Help Message
    ```bash
    $ aws-env -h
    ```
    ```bash
    Usage: /usr/local/bin/aws-env [options]
    Options:
      -h, --help      Display this help message
      -l, --list      List all available environments
      -e, --env       Specify the environment number to use
    
    Example:
      /usr/local/bin/aws-env --env 1    
    ```
    List all available
    ```bash
    $ aws-env -l
    ```
    ```bash
    Available environments:
    
    1 default
    2 ************
    3 ************
    4 test-user
    ```
    Specify the environment number to use
    ```bash
    aws-env -e 4
    ```

    <img width="678" alt="image" src="https://github.com/adrian-lin-1-0-0/my-aws-tools/assets/61909204/6b1277e0-0aa5-43e2-ac49-8282758dc5db">
