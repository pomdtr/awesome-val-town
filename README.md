# Awesome Val Town <!-- omit from toc -->

> A curated list of useful applications, tool and libraries for Val Town.

## Table of Contents <!-- omit from toc -->

- [Apps / Websites](#apps--websites)
  - [Internal](#internal)
  - [External](#external)
  - [URL Actions](#url-actions)
- [Vals](#vals)
  - [Middlewares](#middlewares)
  - [Sqlite](#sqlite)
  - [Blobs](#blobs)
  - [Markdown](#markdown)
  - [Http](#http)
  - [API](#api)

## Apps / Websites

### Internal

- [SQLite Explorer](https://www.val.town/v/nbbaier/sqliteExplorerApp) - View and interact with your Val Town SQLite data
- [Blob Admin](https://www.val.town/v/stevekrouse/blob_admin)
- [Test Explorer](https://www.val.town/v/pomdtr/test_explorer)
- [Cron Compiler](https://stevekrouse-cron.web.val.run/) - Go from natural language to cron expressions.

### External

- [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=pomdtr.valtown) - Manage you vals / blobs / sqlite database from the confort of your favorite editor.
- [LibSQL](https://libsqlstudio.com/) - A generic SQL client that works with your val.town database.
- [vt CLI](https://github.com/pomdtr/vt) - A command line interface to interact with the val.town API.
- [Chrome Extension](https://github.com/pomdtr/val-town-chrome-extension) - Add a customizable sidebar to the val.town website.

### URL Actions

These tools allow you to interact with your vals by replacing `www.val.town` by `<tool-origin>` while viewing a val page.

- [Valshot](https://www.val.town/v/vladimyr/valshot) - A tool to take screenshots of your vals.
- [Dependency Graph Viewer](https://www.val.town/v/rlesser/dependency_graph) - Visualize the dependencies between your vals.
- [CDN](https://www.val.town/v/pomdtr/cdn) - Access a raw version of a val code/readme/metadata.
- [Val Town by Example](https://pomdtr-val_town_by_example.web.val.run/) - An equivalent to Deno/Go by example, but for Val Town.

## Vals

### Middlewares

These tools requires you to wrap you http handler in a middleware to add the functionality.

- [@pomdtr/password_auth](https://www.val.town/v/pomdtr/password_auth) - Protect your vals behind a password.
- [@pomdtr/email_auth](https://www.val.town/v/pomdtr/email_auth) - Protect your vals behind an email verification (requires pro account).
- [andreterron/codeOnValTown](https://www.val.town/v/andreterron/codeOnValTown) - Adds a "Code on Val Town" ribbon to your page.

### Sqlite

- [@pomdtr/sql](https://val.town/v/pomdtr/sqlite) - An sql template string tag that improves the developer experience when working with sqlite.
- [@vladymir/keyvhqSqlite](https://www.val.town/v/vladimyr/keyvhqSqlite) - Use your sqlite database as a key-value store.
- [@sqlite/db](https://val.town/v/sqlite/db) - Query all public vals using sqlite.

### Blobs

- [@pomdtr/lowdb](https://www.val.town/v/pomdtr/lowdb) - Use a blob as a NoSQL database.
- [@pomdtr/blob_editor](https://www.val.town/v/pomdtr/blob_editor) - Edit your blobs from a web interface.

### Markdown

- [@pomdtr/gfm](https://www.val.town/v/pomdtr/gfm) - Render your markdown files to HTML with Github style.
- [@pomdtr/mdx](https://www.val.town/v/pomdtr/mdx) - Serve you readme as a MDX file.
- [@pomdtr/serveReadme](https://www.val.town/v/pomdtr/serve_readme) - Serve your val readme on it's http endpoint.

### Http

- [@stevekrouse/fetchJSON](https://www.val.town/v/stevekrouse/fetchJSON) - Remove the boilerplate of fetching JSON data from the val.town API. Variants: `fetchText`, `fetchRSS`

### API

- [@pomdtr/api](https://www.val.town/v/pomdtr/lowdb) - A client for the val.town API. Remove the boilerplate, and handle authentication/pagination.
- [@pomdtr/extractValMetadata](https://www.val.town/v/pomdtr/extractValMetadata) - Easily find out the author and name of the current val.
