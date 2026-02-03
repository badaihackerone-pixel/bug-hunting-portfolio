---
layout: ../../layouts/MainLayout.astro
title: "HTTP Basics"
---

<div class="prose prose-slate prose-lg max-w-3xl mx-auto py-12">

# Understanding HTTP for Bug Hunters

Stop looking at the browser. Start looking at the traffic.

As a security analyst, the graphical user interface (GUI) is a distraction. The truth lies in the **HTTP Request** and **Response**.

## The Anatomy of a Request

Every time you click a button, your browser sends a text message to the server. It looks like this:
```http
POST /api/login HTTP/1.1
Host: [www.target.com](https://www.target.com)
User-Agent: Mozilla/5.0
Content-Type: application/json

{"username": "admin", "password": "supersecret"}
```
## The Response

The server replies with a status code:

* **200 OK**: Success.
* **302 Found**: Redirect.
* **403 Forbidden**: Security Block.

<div class="mt-12 pt-6 border-t border-slate-200">
    <a href="/learn" class="text-blue-600 font-bold hover:underline">← Back to Learning Path</a>
</div>

</div>
