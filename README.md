# Srin Engine - Official Documentation

This folder contains the complete, standalone static HTML documentation for **Srin Engine** (`deadxfire/srin`), architected and developed by **Arindam Makar** ([@deadxfire](https://github.com/deadxfire)).

## 🚀 Hosting & Deployment Options
This documentation is 100% self-contained static HTML, CSS, and vanilla JavaScript (zero server runtime or database required). You can deploy it instantly:

1. **GitHub Pages:**
   Push this folder to a GitHub repository (e.g. `deadxfire/srin-docs` or `gh-pages` branch) and enable GitHub Pages under repository Settings.
2. **Netlify / Vercel / Cloudflare Pages:**
   Deploy this directory directly with drag-and-drop or Git linking.
3. **Any Web Server (Apache, Nginx, LiteSpeed, Caddy):**
   Drop these files into any public web folder (e.g. `public_html/docs/`).

## 📚 Chapters Included
- `index.html` / `introduction.html` - Framework Philosophy & Standalone Architecture
- `installation.html` - Requirements, Composer, Git, and .env Setup
- `cli.html` - Complete `php srin` Console Command Reference (Scaffolding, Migrations, Route Inspection, Checkpoint Generation, and Real-Time Log Tailing)
- `routing.html` - HTTP Verbs, Named Routes, Route Helpers, and Checkpoints (Linear Middleware Gates)
- `controllers.html` - All 25+ BaseController Superpower Methods, Action Guards (`$this->guard()`), and Native HTTP File/Image Uploads
- `views.html` - Srin Tags (`[if]`, `[each]`, `[empty]`, `[end]`), `[layout]`, `[block]`, `[slot]`, and XSS Sanitization
- `assets.html` - `{{assets('')}}` Direct URL Linking & Automatic Image Folder Resolution
- `database.html` - Multi-Driver Configuration (SQLite, MySQL, PostgreSQL), Transactions, `db()` Gateway
- `models.html` - ActiveRecord CRUD, Fillable Mass Assignment, JSON Serialization
- `query-builder.html` - Standalone Query Builder (`search`, `filter`, `distinctValues`, `when`, `pluck`)
- `relationships.html` - Model Relations (`hasMany`, `belongsTo`, `hasOne`), Eager Loading `with()`
- `pagination.html` - Auto-Query Retaining Paginator & `[paginate]` Tag
- `migrations.html` - Schema Blueprint Column Types, Modifiers, and Migration CLI
- `seeders.html` - Database Seeders & Populating Test Data
- `security.html` - Defense-in-Depth (CSRF, Honeypot Anti-Bot, Rate Limiting, Sanitization, Universal `Core\Auth` Authentication, and Secure File Uploads)
- `mailer.html` - Mail Transfer (SMTP, Native, Local Log Driver)
- `helpers.html` - Complete Global Helper Reference (URLs, Database, Security, Auth, Diagnostics & Logging)

