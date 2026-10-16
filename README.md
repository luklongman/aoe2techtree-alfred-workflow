# (Alfred Workflow) AoE2:DE Tech Tree Quick Search
  
## `aoe`: take a quick look on [aoe2techtree.net](aoe2techtree.net)

![aoe2techtree-1.png](https://pub-b5fd5637194140da82aab38eadc4a60e.r2.dev/attachments/png/41/41a74e370925ae8a2cbdddf91639c0f4b56669197ac72f242b34460d0948083b.png)

![CleanShot 2026-10-16 at 14.41.03@2x.png](https://pub-b5fd5637194140da82aab38eadc4a60e.r2.dev/attachments/png/f8/f8262aef14082250dfb78806c8796bfe7064047ff229daa251bc8aab9ba1f320.png)
  ![aoe2techtree-3.jpeg](https://pub-b5fd5637194140da82aab38eadc4a60e.r2.dev/attachments/jpeg/85/859483b025994d7bd9bb28827914651bd2b554a6294989936b8172a305b5696b.jpeg)
*Within seconds, Varangian's tech tree is shown in your default browser.
  
## Install & Configure

1. Download the latest `.alfredworkflow` from the [Releases](../../releases) page.
2. Open the downloaded file and confirm the import in Alfred.
3. This workflow uses `jq`, a lightweight command-line JSON processor. You may install it either with:
   - Homebrew: `brew install jq`, or;
   - [Alfred's built-in Dependencies Manager](https://www.alfredapp.com/help/kb/dependencies/)
4. *(Optional) To customize the keyword, open the workflow's configuration and replace `aoe` with your preference.
  
## Fetch & Download

Upon the first run, this workflow downloads the current civ data and icons from [Siege Engineers AoE2 Tech Tree](https://github.com/SiegeEngineers/aoe2techtree)(<2MB in total) and store them in Alfred's per-workflow data directory in order to improve search speed. A background refresh checks for updates periodically.
  ![CleanShot 2026-10-16 at 14.30.38@2x.png](https://pub-b5fd5637194140da82aab38eadc4a60e.r2.dev/attachments/png/84/8409f6743ec0f6ee7b34c5582a111f9f30d9c95cfbc1581dd1f17985740b8262.png)

---

This is an independent community workflow created by: [Luk Long Man](https://github.com/luklongman). Shout out to [Siege Engineers AoE2 Tech Tree](https://github.com/SiegeEngineers/aoe2techtree) for constantly updating and sharing the game data.

2026-10-16: v1.0 Release
