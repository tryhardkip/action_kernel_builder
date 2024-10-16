# Yet Another Kernel Builder Using GitHub Actions

## How to Use
1. Go to the **ACTIONS** tab.
2. Choose the Build Kernel workflow.
2. Fill in the required fields.
3. Run the workflow.

## Setting Up the Toolchain

### For Tarball
1. Navigate to [Android Clang Prebuilt](https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/).
2. Select the branch/tag and the `clang` folder for the version you want to use.
3. Long press the "tgz" link beside "path_history" and copy the link address.
4. Paste it into the toolchain URL link option.

### For Git Repository
1. Simply enter the repository URL.
2. To specify a branch, add `-b <branch>` after or before the URL. If no branch is specified, the default branch will be cloned.

