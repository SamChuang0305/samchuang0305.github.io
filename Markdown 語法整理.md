# Markdown 語法整理

---

**粗體字**

##### Markdown 語法：

```md
**粗體字**

或

__粗體字__
```

---

*斜體字*

##### Markdown 語法：

```md
*斜體字*

或

_斜體字_
```

---

<u>底線</u>

##### Markdown 語法：

```md
<u>底線</u>
```

---

~~刪除線~~

##### Markdown 語法：

```md
~~刪除線~~
```

---

`Highlight 凸顯字`

##### Markdown 語法：

```md
`Highlight 凸顯字`
```

---

$註記$

###### *(GitHub 不支援)*

##### Markdown 語法：

```md
$註記$
```

---

### 連結

<https://www.google.com>

##### Markdown 語法：

```md
在連結頭、尾加上 "<" 和 ">"
<https://www.google.com>
```

---

### 使用文字的連結

[連結文字](https://www.google.com)

##### Markdown 語法：

```md
[連結文字](https://www.google.com)
```

---

### 圖片

![圖片 Alt](https://picsum.photos/id/684/600/400 "圖片 Title")

##### Markdown 語法：

```md
![圖片 Alt](https://picsum.photos/id/684/600/400 "圖片 Title")
```

--- 

### 分隔線

##### Markdown 語法：

```md
---
```

---

### 標題類

# H1 標題1 (含底線)

## H2 標題2 (含底線)

### H3 標題3

#### H4 標題4

##### H5 標題5

###### H6 標題6

##### Markdown 語法：

```md
# H1 標題1
## H2 標題2
### H3 標題3
#### H4 標題4
##### H5 標題5
###### H6 標題6
```

---

### 數學公式

###### *(GitHub 不支援)*

$$
f(x)=10
$$

##### Markdown 語法：

```md
$$
f(x)=10
$$
```

---

### HTML 區塊

<div>
<h3>文章標題</h3>
文章內容<br />
使用 HTML 連結語法 <a href="http://www.google.com" target="_blank">Google</a><br />

含有<span style="color:magenta"> *顏色* </span>的文章內容
</div>

##### Markdown 語法：

```html
<div>
<h3>文章標題</h3>
文章內容<br />
使用 HTML 連結語法 <a href="http://www.google.com" target="_blank">Google</a><br />

含有<span style="color:magenta"> *顏色* </span>的文章內容
</div>
```

---

### 程式碼區塊

```csharp
// C# 程式碼區塊
public class MyClass
{
    public string String1 { get; set; }
    public int Int1 { get; set; }

    public MyClass()
    {
      Console.WriteLine("建構子");
    }
}
```

##### Markdown 語法：

    ```csharp
    // C# 程式碼區塊
    public class MyClass
    {
        public string String1 { get; set; }
        public int Int1 { get; set; }

        public MyClass()
        {
          Console.WriteLine("建構子");
        }
    }
    ```

---

### 引言

> 引言，若要換行，結尾要加兩個 `空白`__  
> 這是新的一行

##### Markdown 語法：

```md
> 引言，若要換行，結尾要加兩個 `空白`__  
> 這是新的一行
```

---

### 表格與對齊方式

| A          | B          | C          | D          |
|:---        | ---        |:---:       | ---:       |
| XXXXXXXXXX | XXXXXXXXXX | XXXXXXXXXX | XXXXXXXXXX |
| 靠左       | 預設       | 置中       | 靠右       |
| A1         | B1         | C3         | D1         |
| *斜體*     | **粗體**   | <u>底線</u>| ~~刪除線~~ |
| `凸顯字`   | B2         | C2         | D2         |

##### Markdown 語法：


```md
| A          | B          | C          | D          |
|:---        | ---        |:---:       | ---:       |
| XXXXXXXXXX | XXXXXXXXXX | XXXXXXXXXX | XXXXXXXXXX |
| 靠左       | 預設       | 置中       | 靠右       |
| A1         | B1         | C3         | D1         |
| *斜體*     | **粗體**   | <u>底線</u>| ~~刪除線~~ |
| `凸顯字`   | B2         | C2         | D2         |
```
第一排是標題列 ( 以粗體顯示 )  
第二排是對齊列 ( `:` 表示對齊位置，並搭配至少三個 `-` 符號表示內容 )  
表格內可用 `空白` 排板增加 Markdown 可讀性，但不會影響輸出呈現的結果  
表格內可使用行內格式符號

---

### 有序列表

1. 有序列表 1
2. 有序列表 2
   1. 有序列表 1-1
   2. 有序列表 1-2
      1. 有序列表為 `數字` + `.` + `空白鍵`
      > 2. 可搭配引言符號 `>`
      > * 可搭配無序列表符號 *
      > + 可搭配無序列表符號 +
      > - 可搭配無序列表符號 -
   3. 有序列表 1-3 結尾加兩個 `空白鍵` + `換行` __  
      這行文字就會對齊
   4. 有序列表 1-4
3. 有序列表 3


##### Markdown 語法：

```
1. 有序列表 1
2. 有序列表 2
   1. 有序列表 1-1
   2. 有序列表 1-2
      1. 有序列表為 `數字` + `.` + `空白鍵`
      > 2. 可搭配引言符號 `>`
      > * 可搭配無序列表符號 *
      > + 可搭配無序列表符號 +
      > - 可搭配無序列表符號 -
   3. 有序列表 1-3 結尾加兩個 `空白鍵` + `換行` __  
      這行文字就會對齊
   4. 有序列表 1-4
3. 有序列表 3
```

---

### 無序列表

- 無序列表 1
- 無序列表 2
  - 無序列表 1-1
  - 無序列表 1-2
    - 無序列表為 `*` 或 `+` 或 `-`
    > - 可搭配引言符號 `>`
    > 1. 可搭配有序列表 `數字` + `.` + `空白鍵`
    > 2. 可搭配有序列表 `數字` + `.` + `空白鍵`
    > 3. 可搭配有序列表 `數字` + `.` + `空白鍵`
  - 無序列表 1-3 結尾加兩個 `空白鍵` + `換行` __  
    這行文字就會對齊
  - 無序列表 1-4
- 無序列表 3

##### Markdown 語法：

```
- 無序列表 1
- 無序列表 2
  - 無序列表 1-1
  - 無序列表 1-2
    - 無序列表為 `*` 或 `+` 或 `-`
    > - 可搭配引言符號 `>`
    > 1. 可搭配有序列表 `數字` + `.` + `空白鍵`
    > 2. 可搭配有序列表 `數字` + `.` + `空白鍵`
    > 3. 可搭配有序列表 `數字` + `.` + `空白鍵`
  - 無序列表 1-3 結尾加兩個 `空白鍵` + `換行` __  
    這行文字就會對齊
  - 無序列表 1-4
- 無序列表 3
```

---

#### 補充

若輸入的內容行尾有 `分行符號`，但顯示的內容沒有斷行，  
在分行符號前 (行尾處) 加兩個 `空白鍵` 即可。  
例如本補充的前兩行行尾就有用兩個 `空白鍵` + `分行符號`

#### 參考資料

1. <https://gist.github.com/christech1117/6dc5221c177104990767d6490ad8c7ba>
2. <https://gist.githubusercontent.com/christech1117/6dc5221c177104990767d6490ad8c7ba/raw/e97cc6bb396ab387ef66fbfe91c6fa702b7f2a55/Markdown%25E6%2595%2599%25E5%25AD%25B8.md>
