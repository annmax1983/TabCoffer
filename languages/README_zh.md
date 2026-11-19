# TabCoffer

中文 | [English](../README.md) | [日本語](README_ja.md) | [Deutsch](README_de.md) | [Español](README_es.md) | [Français](README_fr.md)

本地优先的标签会话管理器。把当前标签存成命名保险箱，需要时一键取回。

> Chrome · Edge · Firefox · Manifest V3 · Local-first · No account · No tracking

---

## Free vs Pro

| 能力 | 免费 | Pro |
|------|------|------|
| 会话组数 | **3** | 100 |
| 每组标签数 | **20** | 200 |
| 一键保存 / 恢复 | ✅ | ✅ |
| 重命名、删除、排序 | ✅ | ✅ |
| JSON 导出 | ✅ | ✅ |
| 搜索会话与标签 | — | ✅ |
| JSON 导入（合并去重） | — | ✅ |
| 恢复时跳过重复 / 只开未打开的标签 | — | ✅ |

**保存、恢复与导出会话本身免费，能力不打折——唯一限制是 3 组 × 20 标签。** Pro 提高上限并加入搜索、导入和两个精细恢复选项。许可证完全可选，免费版从不索要。

---

## How to use

1. 打开你想归拢的一组标签。
2. 点击 TabCoffer 图标，输入名称，按**保存会话**。
3. 放心关掉这些标签——会话还留在保险箱里。
4. 之后打开弹窗，选择**在新窗口打开**或**添加到当前窗口**。

---

## Privacy

会话、标题、网址和图标只存在本机的 `chrome.storage.local`。TabCoffer 不读取网页内容、不发送统计。唯一的网络请求是激活 Pro 时向 `api.annmax1983.com` 发送的许可证校验，内容只有许可证密钥、随机安装标识和浏览器元数据——绝不包含你的会话。

---

## Source

> 本仓库仅用于项目展示，不发布完整源码。请从官方浏览器商店安装。

---

## Licence

Get a licence: `https://annmax1983.com/checkout?plugin=tabcoffer`

Activate it: TabCoffer popup → ⚙ → enter the key.

Copyright © 2026 TabCoffer. All rights reserved. Closed source.
