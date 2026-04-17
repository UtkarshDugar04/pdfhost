# PDF Host (200MB+ Optimized)

This project provides a high-performance, full-width PDF viewer designed for large files (200MB+). It uses **PDF.js** with lazy loading and range requests to ensure the first page opens instantly.

## 🚀 How to use

1. **Host your PDF**: Since GitHub has a 100MB limit and GitHub Pages doesn't support LFS, you must host your PDF on a service that supports **CORS** and **Range Requests**.
2. **Update index.html**: Replace `YOUR_DIRECT_PDF_URL_HERE` in the `<script>` tag with your hosted URL.
3. **Deploy**: Push changes to this repo and enable **GitHub Pages** in Settings.

## 💎 Underrated Free Resources for 200MB+ PDFs

| Resource | Why it's Awesome | Constraints |
| :--- | :--- | :--- |
| **Cloudflare R2** | **The Best.** 10GB free, $0 egress fees (truly free), supports CORS/Range. | Needs credit card for account verification. |
| **Supabase Storage** | Very easy to set up. 1GB free storage, supports CORS. | 5GB bandwidth limit on free tier. |
| **Hugging Face** | Underrated "Storage Hack". Unlimited (LFS), global CDN. | Harder to configure CORS for direct scripts. |
| **Backblaze B2** | 10GB free. Pair with Cloudflare for free egress. | Setup is slightly more technical. |

## 🛠 Features
- **Zero UI**: No buttons, sidebars, or "Load PDF" prompts.
- **Fill Width**: Automatically scales to fill the viewport width.
- **Lazy Loading**: Only downloads and renders pages as you scroll.
- **Dark Mode**: Premium minimalist aesthetic.

