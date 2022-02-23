# Prerequisites

## Amazon Web Services

The commands below deploy Kubernetes cluster into [Amazon Web
Services](https://aws.amazon.com).

## Amazon Web Services CLI

Install AWS CLI following instructions at https://aws.amazon.com/cli/.

Details how to configure AWS CLI are available
[here](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html).


## Running Commands in Parallel with tmux

[tmux](https://github.com/tmux/tmux/wiki) can be used to run commands on multiple compute instances at the same time. Labs in this tutorial may require running the same commands across multiple compute instances, in those cases consider using tmux and splitting a window into multiple panes with synchronize-panes enabled to speed up the provisioning process.

> The use of tmux is optional and not required to complete this tutorial.

![tmux screenshot](images/tmux-screenshot.png)

> Enable synchronize-panes by pressing `ctrl+b` followed by `shift+:`. Next type `set synchronize-panes on` at the prompt. To disable synchronization: `set synchronize-panes off`.

Next: [Part 1 - AWS login and Networking](02-part-01.md)
