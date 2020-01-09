# Markdown 語法整理

---

**粗體字**

##### Markdown 語法：

```
**粗體字**

或

__粗體字__
```

---

*斜體字*

##### Markdown 語法：

```
*斜體字*

或

_斜體字_
```

---

<u>底線</u>

##### Markdown 語法：

```
<u>底線</u>
```

---

~~刪除線~~

##### Markdown 語法：

```
~~刪除線~~
```

---

`Highlight 凸顯字`

##### Markdown 語法：

```
`Highlight 凸顯字`
```

---

$註記$

###### *(GitHub 不支援)*

##### Markdown 語法：

```
$註記$
```

---

### 超連結

<https://www.google.com>

##### Markdown 語法：

```
在網址頭、尾加上 "<" 和 ">"
<https://www.google.com>
```

---

### 含連結文字的超連結

[連結文字](https://www.google.com)

##### Markdown 語法：

```
[連結文字](https://www.google.com)
```

---

### 圖片

![圖片 Alt](https://picsum.photos/id/684/600/400 "圖片 Title")

##### Markdown 語法：

```
![圖片 Alt](https://picsum.photos/id/684/600/400 "圖片 Title")
```

--- 

### 分隔線

##### Markdown 語法：

```
---
```

---

### 標題類

# H1 標題1

## H2 標題2

### H3 標題3

#### H4 標題4

##### H5 標題5

###### H6 標題6

##### Markdown 語法：

```
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

```
$$
f(x)=10
$$
```

---

### HTML 區塊

<div>
<h3>文章標題</h3>
文章內容<br />
<a href="http://www.google.com" target="_blank">Google</a>
</div>

##### Markdown 語法：

```html
<div>
<h3>文章標題</h3>
文章內容<br />
<a href="http://www.google.com" target="_blank">Google</a>
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

> 若要換行，結尾要加兩個 `空白鍵`__  
> 引言

##### Markdown 語法：

```
> 若要換行，結尾要加兩個 `空白`__  
> 引言
```

---

### 表格與對齊方式

| A   | B   | C   | D   |
|:--- | --- |:---:| ---:|
| XXXXXXXXXX | XXXXXXXXXX | XXXXXXXXXX | XXXXXXXXXX |
| 靠左  | 預設  | 置中  | 靠右  |
| A1  | B1  | C3  | D1  |
| A2  | B2  | C2  | D2  |
| A3  | B3  | C3  | D3  |

##### Markdown 語法：

```
| A   | B   | C   | D   |
|:--- | --- |:---:| ---:|
| 靠左  | 預設  | 置中  | 靠右  |
| XXXXXXXXXX | XXXXXXXXXX | XXXXXXXXXX | XXXXXXXXXX |
| A1  | B1  | C3  | D1  |
| A2  | B2  | C2  | D2  |
| A3  | B3  | C3  | D3  |
```

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

#### 參考資料
1. <https://gist.github.com/christech1117/6dc5221c177104990767d6490ad8c7ba>
2. <https://gist.githubusercontent.com/christech1117/6dc5221c177104990767d6490ad8c7ba/raw/e97cc6bb396ab387ef66fbfe91c6fa702b7f2a55/Markdown%25E6%2595%2599%25E5%25AD%25B8.md>