# Markdown 語法整理

---

**粗體字**

<div>
<pre>
**粗體字**
</pre>
</div>

---

*斜體字*

<div>
<pre>
*斜體字*
</pre>
</div>

---

<u>底線</u>

<div>
<pre>
&lt;u&gt;底線&lt;/u&gt;
</pre>
</div>

---

~~刪除線~~

<div>
<pre>
~~刪除線~~
</pre>
</div>

---

`突出`

<div>
<pre>
`突出`
</pre>
</div>

---

$註記$

<div>
<pre>
$註記$
</pre>
</div>

---

[連結文字](https://www.google.com)

<div>
<pre>
[連結文字](https://www.google.com)
</pre>
</div>

---

![圖片 Alt](https://picsum.photos/id/684/600/400 "圖片 Title")

<div>
<pre>
![圖片 Alt](https://picsum.photos/id/684/600/400 "圖片 Title")
</pre>
</div>

--- 

### 分隔線

<div>
<pre>---</pre>
</div>

---

### 標題類

# H1 標題1

## H2 標題2

### H3 標題3

#### H4 標題4

##### H5 標題5

###### H6 標題6

<div>
<pre>
# H1 標題1
## H2 標題2
### H3 標題3
#### H4 標題4
##### H5 標題5
###### H6 標題6
</pre>
</div>

---

### 數學公式

$$
f(x)=10
$$

<div>
<pre>
$$
f(x)=10
$$
</pre>
</div>

---

### HTML 區塊

<div>
<h3>head 3 tag</h3>
文字內容<br />
<a href="http://www.google.com" target="_blank">Google</a><br /><br />
</div>

<div>
<pre>
&lt;div&gt;
&lt;h3&gt;head 3 tag&lt;/h3&gt;
文字內容&lt;br /&gt;
&lt;a href="http://www.google.com" target="_blank"&gt;Google&lt;/a&gt;
&lt;/div&gt;
</pre>
</div>

---

### 程式碼區塊

```csharp
// Code Block
// 程式碼區塊
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

<div>
<pre>
<code>```</code>csharp
// Code Block
// 程式碼區塊
public class MyClass
{
    public string String1 { get; set; }
    public int Int1 { get; set; }

    public MyClass()
    {
      Console.WriteLine("建構子");
    }
}
<code>```</code>
</pre>
</div>


---

### 引言

> Quote Block
> 
> 引言

<div>
<pre>
> Quote Block
> 
> 引言
</pre>
</div>

---

### 表格與對齊方式

| A   | B   | C   | D   |
|:--- | --- |:---:| ---:|
| A1  | B1  | C3  | D1  |
| A2  | B2  | C2  | D2  |
| A3  | B3  | C3  | D3  |

<div>
<pre>
| A   | B   | C   | D   |
|:--- | --- |:---:| ---:|
| A1  | B1  | C3  | D1  |
| A2  | B2  | C2  | D2  |
| A3  | B3  | C3  | D3  |
</pre>
</div>

---

### 數字列表清單

1. Order List 1
   
   1. Order List 1-1
   
   2. Order List 1-2
      
      1. Order List 1-2-1
      
      2. Order List 1-2-2
      
      3. Order List 1-2-3
   
   3. Order List 1-3

2. Order List 2

<div>
<pre>
1. Order List 1<br />
   1. Order List 1-1<br />
   2. Order List 1-2<br />
      1. Order List 1-2-1<br />
      2. Order List 1-2-2<br />
      3. Order List 1-2-3<br />
   3. Order List 1-3<br />
2. Order List 2
</pre>
</div>

---

### 清單列表

- Bullet List 1
  
  - Bullet List 1-1
  
  - Bullet List 1-2
    
    - Bullet List 1-2-1
    
    - Bullet List 1-2-2
    
    - Bullet List 1-2-3
  
  - Bullet List 1-3

- Bullet List 2

<div>
<pre>
- Bullet List 1<br />
  - Bullet List 1-1<br />
  - Bullet List 1-2<br />
    - Bullet List 1-2-1<br />
    - Bullet List 1-2-2<br />
    - Bullet List 1-2-3<br />
  - Bullet List 1-3<br />
- Bullet List 2
</pre>
</div>