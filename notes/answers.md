# Difference Between apt update and apt upgrade

`apt update` downloads the latest package information from the configured repositories. It does not install or upgrade packages. `apt upgrade` installs newer versions of packages that are already installed on the system. Therefore, we normally run `sudo apt update` before `sudo apt upgrade`.
