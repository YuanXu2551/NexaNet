# NexaNet
NexaNet offers versatile cloud storage with easy file sharing and online editing. Its batch operations simplify file handling, while a recycle bin guards against unintended deletions. Enhanced by a swift global search, NexaNet stands out for efficient, secure file management.

## Software Architecture
**Front-end:** Element UI, Vue CLI @ 3, Node.js, Webpack

**Backend:** Spring Boot, MyBatis, JPA, JWT

**Database :** MySQL

**Data structures:** recursive algorithms, tree traversal and insertion ...
## Basic File Operations

| Operation | File | Folder | Single | Batch | Remarks |
|-----------|------|--------|--------|-------|---------|
| Create    | ✓    | ✓      | ✓      | ⚪    | Create Word, Excel, PowerPoint online files |
| Delete    | ✓    | ✓      | ✓      | ✓    |         |
| Upload    | ✓    | ✓      | ✓      | ✓    | Drag and drop upload, paste screenshot upload |
| Rename    | ✓    | ✓      | ✓      | ⚪    |         |
| Move      | ✓    | ✓      | ✓      | ✓    |         |
| Copy      | ✓    | ⚪      | ✓      | ⚪    |         |
| Decompress| ✓    | ⚪      | ✓      | ⚪    | ZIP, RAR |
| Preview   | ✓    | ⚪      | ✓      | ⚪    | Support for online preview of images, videos, audio. Support for common text files such as PDF, JSON, TXT, HTML. Support for online preview of Office files |
| Share     | ✓    | ✓      | ✓      | ✓    | Support for validity period, extraction code |
| Search    | ✓    | ✓      | ⚪      | ⚪    | Support for ElasticSearch file name fuzzy search |

## Special Features

| Feature | Description |
|---------|-------------|
| Office online editing | Online creation, editing, and collaborative editing of Word, Excel, PowerPoint documents. Integrated with OnlyOffice, installation method refer to Installing ONLYOFFICE |
| Markdown online editing | Supports online preview, editing, and saving of markdown files. Integrated with mavon-editor, built into the front-end project |
| Code online editing | Supports online preview, editing, and saving of common code files such as C, C++, C#, Java, JavaScript, HTML, CSS, Less, Sass, Stylus. Integrated with vue-codemirror, built into the front-end project, refer to the codemirror official website for adding more languages |
| File category view | Images, videos, music, documents, others, faster category viewing |
| Multiple viewing modes | Supports grid mode, list mode, timeline mode. Manual control of icon display size in grid mode |
| Recycle bin | Deleted files automatically moved to the recycle bin, support for permanent deletion and restoration of files in the recycle bin |
| Multiple storage methods | Based on the Qiwen community's self-developed framework UFOP, achieving diversified file storage. Supports local disk, Alibaba Cloud OSS object storage, FastDFS storage, MinIO storage, Qiniu Cloud KODO object storage, click to view storage configuration method |
| Supports fragment upload | Based on the Qiwen community's self-developed framework UFOP, achieving file fragment upload. Integrated with the excellent open-source project vue-simple-uploader |
| Supports rapid second pass | Calculate file MD5, achieve rapid second pass effect, improve upload efficiency |
| Supports breakpoint continuation | For the same file, when the upload process is interrupted by the network, it can continue to upload from the breakpoint |
| Real-time progress display | The page displays real-time upload file progress, speed, results, and other information |
| Storage capacity display | Can display real-time file storage occupancy and total storage capacity |

## 部分功能截图
<img width="416" alt="791693103067_ pic" src="https://github.com/YuanXu2551/NexaNet/assets/138524143/9529f9a2-9912-4be4-8981-eb56bf489b69">
<img width="416" alt="801693103075_ pic" src="https://github.com/YuanXu2551/NexaNet/assets/138524143/82bca8c2-abea-45e5-ad77-c41ad61260ff">
