# Introduction

This repo provides samples for apps, solutions, and related services for Dynamics 365. For Dynamics 365 docs, visit <https://docs.microsoft.com/dynamics365>.

## How to download

### Download the entire repository

#### Option 1: Clone with Git (recommended)

If you have Git installed, you can clone the entire repository:

```bash
git clone https://github.com/microsoft/Dynamics365-Apps-Samples.git
```

#### Option 2: Download as ZIP

1. Click the green **Code** button at the top of this page
2. Select **Download ZIP**
3. Extract the ZIP file to your desired location

### Download a specific folder

GitHub doesn't natively support downloading individual folders, but you can use one of these methods:

#### Option 1: Using GitHub CLI (gh)

If you have [GitHub CLI](https://cli.github.com/) installed:

```bash
gh repo clone microsoft/Dynamics365-Apps-Samples
cd Dynamics365-Apps-Samples
# Keep only the folder you need, delete the rest
```

#### Option 2: Using SVN

You can use SVN to download a specific folder:

```bash
svn export https://github.com/microsoft/Dynamics365-Apps-Samples/trunk/sales
```

Replace `sales` with the name of the folder you want to download (e.g., `customer-service`, `marketing`, `field-service`).

#### Option 3: Using DownGit or similar services

Visit [DownGit](https://minhaskamal.github.io/DownGit/) or [download-directory.github.io](https://download-directory.github.io/), paste the URL of the specific folder, and download it as a ZIP file.

### Prerequisites

- **Git**: Download and install from [git-scm.com](https://git-scm.com/downloads)
- **SVN** (optional, for folder downloads): Download from [Apache Subversion](https://subversion.apache.org/packages.html)

## Related samples repos

- AL language code samples for Dynamics 365 Business Central: <https://github.com/Microsoft/AL>.
- Power Apps and Dataverse samples: <https://github.com/Microsoft/PowerApps-Samples>.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments . 
