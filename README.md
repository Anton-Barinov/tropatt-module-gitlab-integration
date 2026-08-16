# GitLab

Sync GitLab merge requests with TropaTT tasks (including self-managed GitLab).

A module for the [TropaTT](https://github.com/Anton-Barinov/TropaTT) self-hosted CRM and work platform.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**Languages:** [English](#english) · [Русский](#русский) · [中文](#中文)

## English

### About

Sync GitLab merge requests with TropaTT tasks (including self-managed GitLab).

Two-way sync (v1.1.0): task comments and status changes are pushed back to the linked merge request.

### Module info

| Field | Value |
|---|---|
| Module | `crm.gitlab-integration` |
| Version | `1.1.0` |
| Category | Integration |
| Core | `>=1.0.0` |
| Required permissions | project.manage, task.manage |
| Author | [Anton Barinov](https://github.com/Anton-Barinov) |

### Installation

1. In TropaTT open **Admin → Modules → Install**.
2. Choose one of:
   - **Install from URL:** `https://github.com/Anton-Barinov/tropatt-module-gitlab-integration/releases/download/v1.1.0/crm.gitlab-integration-1.1.0.zip`
   - **Upload archive:** download the release `.zip` and upload it manually.
3. Activate the module and configure it in **Admin → Modules**.

### Repository layout

- `upload/` — the module itself (what gets installed).
- `LICENSE` — MIT license.
- `SECURITY.md` — how to report vulnerabilities.

### Requirements

- TropaTT (PHP 8.1+, MySQL), `core_version` `>=1.0.0`.

### License

[MIT](LICENSE) © Anton Barinov

## Русский

### О модуле

Синхронизация Merge Requests GitLab с задачами TropaTT (включая self-managed GitLab)

Двусторонняя синхронизация (v1.1.0): комментарии и смена статуса задачи возвращаются в связанный Merge Request.

### Информация о модуле

| Поле | Значение |
|---|---|
| Модуль | `crm.gitlab-integration` |
| Версия | `1.1.0` |
| Категория | Интеграция |
| Ядро | `>=1.0.0` |
| Требуемые права | project.manage, task.manage |
| Автор | [Anton Barinov](https://github.com/Anton-Barinov) |

### Установка

1. В TropaTT откройте **Админ → Модули → Установка**.
2. Выберите один из вариантов:
   - **Установка по URL:** `https://github.com/Anton-Barinov/tropatt-module-gitlab-integration/releases/download/v1.1.0/crm.gitlab-integration-1.1.0.zip`
   - **Загрузка архива:** скачайте `.zip` из релиза и загрузите вручную.
3. Активируйте модуль и настройте его в **Админ → Модули**.

### Структура репозитория

- `upload/` — сам модуль (то, что устанавливается).
- `LICENSE` — лицензия MIT.
- `SECURITY.md` — как сообщать об уязвимостях.

### Требования

- TropaTT (PHP 8.1+, MySQL), `core_version` `>=1.0.0`.

### Лицензия

[MIT](LICENSE) © Anton Barinov

## 中文

### 关于

将 GitLab 合并请求与 TropaTT 任务同步（包括私有化部署的 GitLab）。

双向同步（v1.1.0）：任务评论和状态变更会同步回关联的合并请求。

### 模块信息

| 字段 | 值 |
|---|---|
| 模块 | `crm.gitlab-integration` |
| 版本 | `1.1.0` |
| 类别 | 集成 |
| 内核 | `>=1.0.0` |
| 所需权限 | project.manage, task.manage |
| 作者 | [Anton Barinov](https://github.com/Anton-Barinov) |

### 安装

1. 在 TropaTT 中打开 **管理 → 模块 → 安装**。
2. 选择以下方式之一：
   - **从 URL 安装：** `https://github.com/Anton-Barinov/tropatt-module-gitlab-integration/releases/download/v1.1.0/crm.gitlab-integration-1.1.0.zip`
   - **上传压缩包：** 下载 release 中的 `.zip` 并手动上传。
3. 在 **管理 → 模块** 中激活并配置模块。

### 仓库结构

- `upload/` — 模块本身（被安装的内容）。
- `LICENSE` — MIT 许可证。
- `SECURITY.md` — 如何报告漏洞。

### 要求

- TropaTT（PHP 8.1+、MySQL），`core_version` `>=1.0.0`。

### 许可证

[MIT](LICENSE) © Anton Barinov
