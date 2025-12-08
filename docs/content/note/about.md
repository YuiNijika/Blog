---
title: 关于
---

# 你好鸭

我是鼠子(YuiNijika)

熟悉PHP开发、略懂NuxtJS，倾向于面向对象编程。

## 代表作

- [G2M](https://github.com/GTANext/G2M) : Rust + NuxtJS开发的GTAMOD管理器

- [TTDF](https://github.com/YuiNijika/TTDF) : 最直观的Typecho主题模板开发框架

- [VueEcho](https://github.com/YuiNijika/VueEcho) : 基于Vue+Markdown驱动的纯静态博客日志系统

![Soyo](/images/about.jpg)

```php
<?php 
/**
 * 欢迎使用Typecho主题模板开发框架！
 * @package TTDF
 * @author 鼠子(Tomoriゞ)
 * @version 1.0.0
 * @link https://github.com/YuiNijika/TTDF
 */
if (!defined('__TYPECHO_ROOT_DIR__')) exit;
// 面向过程调用
get_components('AppHeader');

// 开发前删除即可
WelCome();

// 面向对象调用
Get::Components('AppFooter');
```