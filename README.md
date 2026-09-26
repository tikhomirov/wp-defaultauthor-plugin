# WordPress Default Post Author

[![WordPress Plugin](https://img.shields.io/badge/WordPress-5.0%2B-blue.svg)](https://wordpress.org/)
[![PHP Support](https://img.shields.io/badge/PHP-7.4%20%7C%208.0%20%7C%208.1%20%7C%208.2%20%7C%208.3-777BB4.svg)](https://php.net/)
[![License](https://img.shields.io/badge/License-GPLv3-green.svg)](https://www.gnu.org/licenses/gpl-3.0.html)

Automates post publishing by automatically assigning a default author to newly created posts and drafts.

## Requirements

| Component | Minimum | Tested |
|-----------|---------|--------|
| **WordPress** | 5.0 | 5.0 – 6.7 |
| **PHP** | 7.4 | 7.4, 8.0, 8.1, 8.2, 8.3 |

## Features

- **Default Author Assignment:** Automatically set designated author on post creation.

## Installation

### Via Composer (VCS Repository)
Add the repository to your `composer.json` and require the package:

```bash
composer config repositories.tikhomirov-wp-defaultauthor-plugin git https://github.com/tikhomirov/wp-defaultauthor-plugin.git
composer require tikhomirov/wp-defaultauthor-plugin
```

### Manual Installation
1. Download the latest ZIP release.
2. Upload the plugin folder to the `/wp-content/plugins/` directory.
3. Activate the plugin through the 'Plugins' menu in WordPress.

---

## Русский

Автоматизирует процесс публикации записей в WordPress, назначая заданного автора по умолчанию для новых постов и черновиков.

### Совместимость
- **WordPress:** от 5.0 и выше
- **PHP:** от 7.4 до 8.3

### Возможности
- Автоматическое назначение автора по умолчанию для новых записей.

**Установка:** подключите через Composer (VCS) или скачайте архив и активируйте в панели управления WordPress.
