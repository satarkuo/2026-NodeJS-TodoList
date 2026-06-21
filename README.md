# Node.js Todolist API

使用 Node.js 原生 `http` 模組建立的 RESTful Todo API，支援新增、讀取、修改、刪除待辦事項，並部署至 Render。

## Demo

https://two026-nodejs-todolist.onrender.com/todos

## Features

- GET `/todos`：取得所有待辦事項
- POST `/todos`：新增待辦事項
- PATCH `/todos/:id`：修改單筆待辦事項
- DELETE `/todos/:id`：刪除單筆待辦事項
- DELETE `/todos`：刪除所有待辦事項

## Tech Stack

- Node.js
- JavaScript
- UUID
- Render

## Install

```bash
npm install
```

## Development

```bash
npm run dev
```

## Start

```bash
npm start
```

## API Example

### POST /todos

Request body:

```json
{
  "title": "學習 Node.js"
}
```

Response:

```json
{
  "status": "success",
  "data": [
    {
      "title": "學習 Node.js",
      "id": "uuid"
    }
  ]
}
```
