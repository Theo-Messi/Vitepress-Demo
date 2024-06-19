# Markdown 扩展示例

此页面演示了 VitePress 提供的一些内置 markdown 扩展。

## 语法突出显示

VitePress 提供由 [Shiki](https://github.com/shikijs/shiki) 提供支持的语法高亮功能，以及行高亮等附加功能：

**输入**

````md
```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```
````

**输出**

```js{4}
export default {
  data () {
    return {
      msg: 'Highlighted!'
    }
  }
}
```

## 定制容器

**输入**

```md
::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::
```

**输出**

::: info
This is an info box.
:::

::: tip
This is a tip.
:::

::: warning
This is a warning.
:::

::: danger
This is a dangerous warning.
:::

::: details
This is a details block.
:::

## 了解更多

查看 [markdown 扩展完整列表](https://vitepress.dev/guide/markdown) 的文档。
