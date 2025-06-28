---
outline: deep
---

# 运行时 API 示例

本页面演示了 VitePress 提供的一些运行时 API 的使用。

主要的 `useData()` API 可用于访问当前页面的站点、主题和页面数据。它适用于`.md`和`.vue`文件：

```md
<script setup>
import { useData } from 'vitepress'

const { theme, page, frontmatter } = useData()
</script>

## Results

### Theme Data
<pre>{{ theme }}</pre>

### Page Data
<pre>{{ page }}</pre>

### Page Frontmatter
<pre>{{ frontmatter }}</pre>
```

<script setup>
import { useData } from 'vitepress'

const { site, theme, page, frontmatter } = useData()
</script>

## Results

### Theme Data
<pre>{{ theme }}</pre>

### Page Data
<pre>{{ page }}</pre>

### Page Frontmatter
<pre>{{ frontmatter }}</pre>

## 了解更多


查看文档以获取 运行时 API 的[完整列表](https://vitepress.dev/reference/runtime-api#usedata).
