# AoE2DE Tech Tree Quick Search Alfred Workflow
  
## Usage
  
Quick Search of a civ's tech tree on [aoe2techtree.net](aoe2techtree.net) via the `aoe` keyword.

![aoe2techtree-1.png](https://pub-b5fd5637194140da82aab38eadc4a60e.r2.dev/attachments/png/41/41a74e370925ae8a2cbdddf91639c0f4b56669197ac72f242b34460d0948083b.png)

![CleanShot 2026-10-16 at 14.41.03@2x.png](https://pub-b5fd5637194140da82aab38eadc4a60e.r2.dev/attachments/png/f8/f8262aef14082250dfb78806c8796bfe7064047ff229daa251bc8aab9ba1f320.png)

![CleanShot 2026-10-16 at 14.41.49@2x.png](https://pub-b5fd5637194140da82aab38eadc4a60e.r2.dev/attachments/png/42/42166c4ae66695b5251ed634a7a0acbbacc4de4357b50856748fec0ff59c97e2.png)
  
*Within seconds, Varangian's tech tree is shown in your default browser.
  
## Installation and Configuration

1. Download the latest `.alfredworkflow` from the [Releases](../../releases) page.

2. Open the downloaded file and confirm the import in Alfred.

3. This workflow uses `jq`, a lightweight command-line JSON processor. You may install it either with:
	1. Homebrew: `brew install jq`, or;
	2. [Alfred's built-in Dependencies Manager]((https://www.alfredapp.com/help/kb/dependencies/)
4. (Optional) To customize the keyword, oppen the workflow's configuration and replace `aoe` with your preference.
  
## First run and local data

Upon the first invocation, this workflow downloads the current civ data and icons (<2MB in total) and store them in Alfred's per-workflow data directory in order to improve search speed. A background refresh checks for updates periodically.
  ![CleanShot 2026-10-16 at 14.30.38@2x.png](https://pub-b5fd5637194140da82aab38eadc4a60e.r2.dev/attachments/png/84/8409f6743ec0f6ee7b34c5582a111f9f30d9c95cfbc1581dd1f17985740b8262.png)

The first invocation downloads the current civilization data, English descriptions, and civilization icons. These files are stored in Alfred's per-workflow data directory on your Mac, not in the workflow's source folder. After the initial setup, search results use the local cache; a background refresh checks for updated source data periodically.

## Credits

- This is an independent community workflow. Shout out to [Siege Engineers AoE2 Tech Tree](https://github.com/SiegeEngineers/aoe2techtree) for constantly updating and sharing the game data.  
- [Alfred](https://www.alfredapp.com/) for providing the workflow platform.
