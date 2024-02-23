# Signal Desktop AppImage

This repository provides a convenient way to obtain an updated Signal Desktop AppImage. By forking this repository and running the `main.yml` GitHub Action workflow, you can obtain the latest version of Signal Desktop packaged as an AppImage.

## Usage

1. **Fork this Repository**: Start by forking this repository to your GitHub account.

2. **Run Workflow**: Execute the `main.yml` workflow to generate the updated Signal Desktop AppImage. This workflow automatically fetches the latest stable and beta versions of Signal Desktop, packages them into a single AppImage, and uploads it as an artifact.

3. **Download the AppImage**:
   - Once the workflow completes successfully, navigate to the Actions tab in your forked repository.
   - Locate the completed workflow run and download the generated `signal-desktop.AppImage` artifact.

4. **Run Signal Desktop**:
   - Use the downloaded `./signal-desktop.AppImage` to launch the latest stable release of Signal Desktop.
   - Alternatively, if you prefer to use the latest beta version, you can run `./signal-desktop.AppImage beta`.

## Disclaimer

This repository is not affiliated with or endorsed by Signal Messenger LLC. Use the Signal Desktop AppImage obtained from this repository at your own discretion.
