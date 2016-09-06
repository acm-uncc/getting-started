# Getting Started with UNC Charlotte ACM

## GitHub Access

1. Create a [GitHub account](https://github.com/join).

1. **Windows Only** - Install [Git for Windows](https://git-for-windows.github.io/). This will give you instant access to bash and git.

1. Open your terminal (or Git for Windows) and issue the command:
```
ssh-keygen
```
Keep hitting Enter to leave all options as the default. There is no need for a password.

1. Issue the following command to reveal the contents of the generated key:
```
cat ~/.ssh/id_rsa.pub
```
Highlight all of the outputted key, and copy it to your clipboard.

1. You know need to [add this key to your GitHub account](https://github.com/settings/keys). Follow the link and select the **New SSH Key** button.

1. Issue the following command to ensure you have successfully added your SSH key:
```
ssh -T git@github.com
```
You should see the output:
> Hi *username*! You've successfully authenticated, but GitHub does not provide shell access.

1. To be added to the [UNCC ACM group](https://github.com/uncc-acm), please shoot [Nick Breaton](https://github.com/nickbreaton/) an email at [nbreaton@uncc.edu](mailto:nbreaton@uncc.edu) with your GitHub username.

Congratulations. You have successfully connected with UNC Charlotte ACM on GitHub.
