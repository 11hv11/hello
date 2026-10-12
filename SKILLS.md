# 项目中的 Agent Skills

这个仓库收录已安装的全部技能：Nature Skills 的 22 个科研技能、1 个共享支持包，以及 `ppt-master`。保留完整的 references、scripts、templates 和 assets 目录。

## 使用

技能位于 `.agents/skills/`，支持该目录约定的 Agent 可以在项目中发现它们。先读取需要使用的 `SKILL.md`，再按该技能的说明运行。

若希望其他项目也使用这些技能，请将各技能的完整目录复制到自己的 `~/.agents/skills/`，保留 `nature-shared`；不要覆盖已有修改。仓库内的技能文件不会自动为其他机器安装运行依赖。

当前云环境已提供共享运行环境，执行脚本前运行：

```bash
source /workspace/skill-runtime/activate.sh
```

其他机器需要按各技能的 requirements.txt 和运行说明安装 Python 包，以及实际任务需要的 LibreOffice、浏览器、R 或 Node 工具。浏览器下载、OCR、外部 API 和模型权重的配置另行处理。虚拟环境、缓存和凭据不包含在这个仓库中。

## 技能目录

- [nature-academic-search](.agents/skills/nature-academic-search/SKILL.md)
- [nature-citation](.agents/skills/nature-citation/SKILL.md)
- [nature-data](.agents/skills/nature-data/SKILL.md)
- [nature-downloader](.agents/skills/nature-downloader/SKILL.md)
- [nature-experiment-log](.agents/skills/nature-experiment-log/SKILL.md)
- [nature-figure](.agents/skills/nature-figure/SKILL.md)
- [nature-image2ppt](.agents/skills/nature-image2ppt/SKILL.md)
- [nature-literature-pipeline](.agents/skills/nature-literature-pipeline/SKILL.md)
- [nature-paper-card](.agents/skills/nature-paper-card/SKILL.md)
- [nature-paper-to-patent](.agents/skills/nature-paper-to-patent/SKILL.md)
- [nature-paper-trans](.agents/skills/nature-paper-trans/SKILL.md)
- [nature-paper-xray](.agents/skills/nature-paper-xray/SKILL.md)
- [nature-paper2ppt](.agents/skills/nature-paper2ppt/SKILL.md)
- [nature-polishing](.agents/skills/nature-polishing/SKILL.md)
- [nature-proposal-writer](.agents/skills/nature-proposal-writer/SKILL.md)
- [nature-reader](.agents/skills/nature-reader/SKILL.md)
- [nature-ref-verifier](.agents/skills/nature-ref-verifier/SKILL.md)
- [nature-response](.agents/skills/nature-response/SKILL.md)
- [nature-reviewer](.agents/skills/nature-reviewer/SKILL.md)
- [nature-shared](.agents/skills/nature-shared/SKILL.md)
- [nature-social-science](.agents/skills/nature-social-science/SKILL.md)
- [nature-statistics](.agents/skills/nature-statistics/SKILL.md)
- [nature-writing](.agents/skills/nature-writing/SKILL.md)
- [ppt-master](.agents/skills/ppt-master/SKILL.md)

## 来源与许可

- Nature Skills：https://github.com/Yuan1z0825/nature-skills
  - 收录版本：`e605b35611ab2849af46d0cf7831aefdcf85be07`
  - 原仓库许可：[Apache-2.0](licenses/nature-skills-LICENSE)
- PPT Master：https://github.com/hugohe3/ppt-master
  - 收录版本：`ca04346de145ed6462ddf34682848e71df5e20a2`
  - 原包许可：[MIT](.agents/skills/ppt-master/LICENSE)

各技能内附的第三方素材及其许可、归属说明一并保留，使用时遵守对应条款。
