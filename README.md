Codespaces Android SDK CE (Community Edition)
---------------------------------------------

A codespace repository configured to install android
development tools.

## Installed Software

    * Ubuntu
    * Bazelisk
    * Gradle
    * Maven
    * Ant
    * Meson
    * Java 17 (Oracle)
    * Android SDK

## Usage

This repository can be used to create a codespace,
by using it as a template for new projects, or
including it as a submodule in an existing project.

To import as a submodule use 'git submodule add'

    git submodule add https://github.com/raymond-chetty/codespaces-AndroidSDK-CE .devcontainer

In theory it is possible to add access to additional
repositories within a codespace using 'customizations'

  * https://containers.dev/supporting#github-codespaces
  * https://docs.github.com/en/codespaces/managing-your-codespaces/managing-repository-access-for-your-codespaces

## devcontainer.json

The original devcontainer.json file was created using the
VS Code [codespaces configuration wizard][1].

Press "F1" or "Ctr + Shift + P" in [VS Code Codespaces][2]
and select "Codespaces: Add Dev Container Configuration Files...".

## Additional information

Additional information about [VS Code][3], the [UI][4],
[Dev Containers][5] and [VS Code Dev Containers][6] ([Extention][7])
is available online. Devcontainers are available on the most
common operating systems and the web ([1][8] & [2][9])!

[1]: https://docs.github.com/en/codespaces/setting-up-your-project-for-codespaces/adding-a-dev-container-configuration/introduction-to-dev-containers#using-a-predefined-dev-container-configuration

[2]: https://code.visualstudio.com/docs/remote/codespaces
[3]: https://code.visualstudio.com/
[4]: https://code.visualstudio.com/docs/getstarted/userinterface
[5]: https://containers.dev/
[6]: https://code.visualstudio.com/docs/devcontainers/containers
[7]: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers

[8]: https://github.com/features/codespaces
[9]: https://docs.github.com/en/codespaces/


