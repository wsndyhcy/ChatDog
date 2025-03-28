---
title: 宠物狗
language_tabs:
  - shell: Shell
  - http: HTTP
  - javascript: JavaScript
  - ruby: Ruby
  - python: Python
  - php: PHP
  - java: Java
  - go: Go
toc_footers: []
includes: []
search: true
code_clipboard: true
highlight_theme: darkula
headingLevel: 2
generator: "@tarslib/widdershins v4.0.29"

---

# 个人项目

Base URLs:   http://192.168.1.250:8020/ctc/dog

# Authentication

# Default

## POST 250

POST /ctc/dog

> Body 请求参数
```json
{
  "user_id": "int",
  "language": "string",
  "name": "string",
  "msg": "string",
  "qmd": "int"


}

// 请求示例
```
{
  "user_id": 44448,
  "language": "中文",
  "name": "ppdog",
  "msg": "你叫什么名字",
  "qmd": "10"
}
`
### 请求参数

|名称|位置|类型|必选|说明|
|---|---|---|---|---|
|body|body|object| 否 |none|
|» user_id|body|integer| 是 |用户id|
|» language|body|string| 是 |使用语言|
|» name|body|string| 是 |狗的名字|
|» msg|body|string| 是 |用户输入消息|
|» qmd|body|int| 是 |亲密度|

> 返回示例

> 200 Response

```json
{
    "reply": "汪汪！我的名字是ppdog，是您可爱的宠物狗！我会一直陪伴在您身边，汪汪！",
    "process_time": 3.1215431690216064
}
```

### 返回结果

|状态码|状态码含义|说明|数据模型|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|none|Inline|

### 返回数据结构

# 数据模型

