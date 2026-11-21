# BigCaseManager3

BigCaseManager3 is an Obsidian plugin for managing projects, tasks, owners, and schedules in your vault. Filter unfinished tasks by owner, track deadlines in the calendar, and import or export your records with Excel.

## Installation

**From Obsidian:** Once the plugin is available for installation in the community directory, open **Settings → Community plugins → Browse**, search for **BigCaseManager3**, then select **Install** and **Enable**.

**Manual installation:**

1. Download `main.js`, `manifest.json`, and `styles.css` from the [GitHub Releases page](https://github.com/bransoninbrazil/BigCaseManager3/releases/latest). Use all three files from the same release.
2. Put the files in `<vault>/.obsidian/plugins/bigcase-manager-three/`. If you use a custom Obsidian configuration folder, use that folder instead of `.obsidian`.
3. Reload Obsidian, then enable **BigCaseManager3** in **Settings → Community plugins**.

## Usage

1. Open the command palette and run **打开 BigCaseManager3** (Open BigCaseManager3).
2. In a new vault, the task and people lists start empty. Follow the prompt to designate the current device for writing, then add your records.
3. In **未完事项** (Unfinished items), click an owner's name to filter the list. Use the calendar to follow deadlines, or open the Excel view to import or export records.

## Data and license

The plugin works locally and stores your records in your vault. It does not require an account or an external service. Excel import and export are started by the user.

The public release contains the compiled plugin, styles, and manifest. The source code is kept private for review by Obsidian. Anyone may download, install, and use the release under the terms in [LICENSE](LICENSE).

## 中文说明

在 Obsidian 笔记库中管理大事项、待办、日程和负责人。可以按负责人查看未完事项，在日历中跟进截止日期，并通过 Excel 导入或导出自己的记录。

## 开始使用

启用插件后，从 Obsidian 命令面板选择「打开 BigCaseManager3」。在新笔记库中，事项和人员列表为空。根据页面提示将当前设备设为写入设备，再添加自己的记录。

## 数据和权限

公开安装包仅包含程序、样式和插件清单。业务记录保存在当前用户的笔记库内。此版本在本地工作，无需登录外部服务。若当前库已经存有兼容的 BigCaseManager 数据，插件会使用库内已有记录。Excel 导入和导出由用户主动发起。

任何个人或组织均可下载、安装和使用公开发行版。源码由维护方私下维护，供 Obsidian 官方审核。使用条款见 LICENSE。
