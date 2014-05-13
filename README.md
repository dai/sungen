# GH Flavored Markdown

## table

|列 1   |列 2   |
|:------|------:|
|内容 1 |内容 2 |
|内容 a |内容 b |

!cap. 表 5F

以下が上記 表 5F の .md ソースです。

```
|列 1   |列 2   |
|:------|------:|
|内容 1 |内容 2 |
|内容 a |内容 b |

!cap. 表 5F
```

* * *

上記表組み記法を独自Script（Pandocベース） md to xhtml にかけ出力されたxhtmlソースが以下になる

```xhtml
<figure class="table">
<figcaption>表 5F</figcaption>
<table>
<thead>
<tr class="header">
<th>列 1</th>
<th>列 2</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>内容1</td>
<td>内容2</td>
</tr>
<tr class="even">
<td>内容a</td>
<td>内容b</td>
</tr>
</tbody>
</table>
</figure>
```

!cap. 表 5F のxhtmlソース


