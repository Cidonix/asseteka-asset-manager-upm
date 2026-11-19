# Asseteka Asset Manager

Browse and download assets from your Asseteka library inside the Unity Editor. This repository distributes the Windows Editor extension through Unity Package Manager (UPM).

## Install v1.0.2

Install Git 2.14.0 or newer and make sure `git --version` works in a new terminal on Windows. Unity Package Manager uses the Git executable on `PATH`. [Unity Git installation guide](https://docs.unity.com/en-us/engine/6000.0/manual/packages-list/managing-packages-window/upm-ui-actions/upm-ui-giturl)

1. Open your Unity project and choose **Window > Package Manager**.
2. Open the **+** menu and choose **Install package from git URL** (called **Add package from git URL** in older Editors).
3. Paste the URL below and click **Install** or **Add**.

```text
https://github.com/Cidonix/asseteka-asset-manager-upm.git#v1.0.2
```

## Open your library

1. In Unity, choose **Window > Asseteka > My Assets**.
2. Click **Sign in with browser**, sign in to your Asseteka account and select **Connect Unity**.
3. Return to Unity and select an asset in your library. For ZIP archives and `.unitypackage` files, choose **Download and import**. For a UPM `.tgz` release, choose **Install package** or **Update package**.

ZIP import lets you choose a folder and files. A `.unitypackage` opens Unity's import dialog. A UPM archive installs the full package version as a dependency of the project. The options shown for each asset depend on the formats enabled by the store and the releases available to your account.

## Compatibility

Asseteka Asset Manager runs in the Unity Editor on Windows x64. The compatibility matrix covers the following Editor versions.

| Unity series | Editor versions |
| --- | --- |
| Unity 2022 | `2022.3.62f3` |
| Unity 2023 | `2023.1.22f1`, `2023.2.22f1` |
| Unity 6 | `6000.0.85f2`, `6000.1.17f1`, `6000.2.15f1`, `6000.3.29f1`, `6000.4.12f1`, `6000.5.11f1`, `6000.6.10f1` |

For help with your account or asset library, [contact Asseteka support](https://asseteka.com/support).
