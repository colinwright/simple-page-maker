# Simple Page Maker

A lightweight, beautiful, and modular one-page website builder (similar to Carrd) designed following the minimalist design guidelines of Truly Simple Tools. Create portfolios, bio cards, product landing pages, newsletter signups, and media embeds quickly and for free.

---

## Features

- **Block-Based Builder**: Build your page by stacking content sections. We support:
  - **Profile / Bio Card** (Avatar image, name, bio, and dynamic social links).
  - **Text Blocks** (Headed text sections).
  - **Buttons / Links** (High-quality call-to-action block links).
  - **Image Blocks** (Image URLs with alt text and caption options).
  - **Video Embeds** (Supports direct MP4 links or responsive video frames like YouTube and Vimeo).
  - **Audio Embeds** (Supports direct MP3 links or audio frames like Spotify and SoundCloud).
  - **Forms** (Contact forms or email newsletter subscriptions linking to Formspree or Netlify).
  - **Dividers & Spacers** (Tactile rules or empty space for visual layout separation).
- **Drag-and-Drop Sorting**: Easily rearrange your sections using handle-based list drag sorting (`⋮⋮` handles).
- **Live Preview**: Real-time iframe view showing theme styling, layouts, and media player rendering.
- **Visitor Dark Mode**: Built-in responsive sun/moon toggle button in the generated header, matching color schemes dynamically (Cream Paper, Charcoal, Sepia, Slate, and Monochrome).
- **Privacy & Ownership**: Runs 100% locally in the browser with no accounts required. Exports a clean ZIP bundle containing raw `index.html`, `style.css`, `script.js`, and `settings.js`.

---

## Setup & Customization

You can run the builder offline:
1. Double-click the `SimplePageMaker.html` file to open it in your default web browser.
2. Customize the global page settings (Page Title, Theme, Fonts) in the left sidebar.
3. Add and configure blocks. Use the drag handles to reorder sections.
4. Click **Generate Website** to download the `upload_these_files.zip` folder.

---

## How to Publish Your Page

Unzip the exported folder and upload the files (`index.html`, `style.css`, `script.js`, `settings.js`) directly to your web host:

### Option 1: Netlify (Fastest)
1. Go to [app.netlify.com](https://app.netlify.com) and create an account.
2. Scroll to the manual deployment area.
3. Drag-and-drop the unzipped `upload_these_files` folder directly into the browser.
4. Your site will deploy in under a minute under a free `netlify.app` subdomain (which you can change or point to a custom domain).

### Option 2: GitHub Pages
1. Create a new public repository on GitHub.
2. Click **Add file** -> **Upload files**, and drag the four extracted files in.
3. Click **Commit changes**.
4. Go to repository **Settings** -> **Pages**, select deployment from the branch (`main` or `master`), and click **Save**.
5. Your site will be live at `https://your-username.github.io/your-repo-name`.
