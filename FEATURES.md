# Quick Peek features

## Everyday preview workflow

- Select a file or folder in File Explorer or on the desktop and press `Space` to preview it.
- Follow Explorer selection changes while the preview remains open.
- Move to the previous or next item with the arrow keys.
- Open the selected item in its default application with `Enter`.
- Copy the useful representation of the current preview with `Ctrl+C`.
- Pin the preview, use full screen, adjust interface density, or reopen recent files.
- Remembers window size and position independently for each monitor.
- Supports command-line opening and forwards requests to the already running instance.

## Text, code, and structured data

- Preview plain text, source code, logs, configuration files, and large generated SQL.
- Syntax highlighting for a broad set of programming and markup languages.
- Search, go to line, change encoding, inspect whitespace, bookmark lines, and follow growing files.
- Format and browse JSON, JSONL, NDJSON, and XML as searchable trees or tables.
- Accept common JSON variants such as comments and trailing commas.
- Filter structured content by JSON or XML path and copy keys, values, paths, or filtered results.
- Validate JSON against a schema.
- Read Markdown in preview, source, or split mode with highlighted code blocks.
- Browse CSV and Excel worksheets in virtualized, searchable, locale-aware tables.

## Documents and PDF

- Preview PDF, Word, PowerPoint, Rich Text, and legacy Office formats.
- Uses installed Windows preview handlers when appropriate, with local document fallbacks for modern
  Word and PowerPoint files.
- PDF page thumbnails, zoom, rotation, single/two-page viewing, and optional dark pages.
- Search and select PDF text, including matches across pages.
- Offline OCR for scanned PDF pages and images when Windows OCR support is available.
- Print PDFs, inspect outlines and document information, follow links, and browse attachments.
- Add local PDF highlights, bookmarks, and notes, with import/export support.
- Export selected PDF pages to a new PDF or rendered PNG files.
- Open AES-256 encrypted PDFs using an in-memory decrypted copy.

## Images and galleries

- Preview common image formats using Windows imaging codecs, including animation and EXIF orientation.
- Zoom, rotate, inspect dimensions and metadata, and browse nearby images in a filmstrip.
- Open a folder gallery with visible-first thumbnail loading and a bounded disk cache.
- Edit images and export full-resolution JPEG images as PNG.
- Extract text with offline OCR and inspect dominant colors or palettes.
- Compare two images with an interactive slider.
- Delete gallery items through an explicit reviewed deletion workflow.

## Audio and video

- Play audio and video using Windows Media Foundation.
- Display subtitles, remember playback position, and add media bookmarks.
- Inspect audio levels and silence maps.
- Use A–B looping, frame stepping, storyboard generation, and clip export.
- Links to optional Microsoft Store codec extensions when Windows lacks a decoder.

## Folders and archives

- Browse folders as a lazy tree, details table, or icon gallery with native shell thumbnails.
- Sort and group folder contents, calculate recursive statistics, and find largest files.
- Search subfolders and preview a selected child without leaving the folder view.
- Browse ZIP, 7z, TAR, TAR.GZ, JAR, NuGet, comic, and related archives.
- Preview files nested inside archives and open directly on a likely README or first useful entry.
- Export selected archive content through safe, bounded extraction.

## Books, email, fonts, and specialist formats

- Read EPUB books with chapters and a table of contents.
- Browse CBZ and CBR comics with page thumbnails.
- Preview EML and Outlook MSG email locally, including headers, bodies, inline images, and attachments.
- Preview TrueType, OpenType, and font collections with specimens and character sets.
- Inspect STL and OBJ models in an interactive native 3D view with measurements.
- View Git repository status and commits for folders.
- Preview HTML and SVG in a restricted WebView with scripts, remote resources, permissions, and
  downloads blocked.
- Show Explorer thumbnails and Windows property details for otherwise unsupported formats.

## File tools and export

- Compare two text files with a bounded side-by-side diff.
- Inspect binary files through a hexadecimal preview.
- Calculate and inspect file checksums.
- Generate QR codes from suitable preview content.
- Copy previews as text, tab-separated rows, images, or files depending on the format.
- Print supported content and reveal files in Explorer.
- Open code and folders in an editor, terminal, or their Git remote where applicable.

## Performance, privacy, and resilience

- Prepares nearby files ahead of navigation within configurable limits.
- Uses bounded caches, virtualization, lazy page/image rendering, and timeouts for large content.
- Runs third-party Windows preview handlers out of process and temporarily quarantines handlers that
  crash, hang, or render nothing.
- Processes file content locally and blocks remote content in HTML and email previews.
- Stores preferences, recent-file state, bookmarks, logs, and caches locally.
- Does not require uploading previewed files to Bytebrain.
