# Sortory

Free Windows tool for batch renaming and organizing photos and videos by date.

Sortory helps you quickly clean up messy photo folders from iPhone, DSLR, mirrorless cameras, and videos into organized, searchable filenames.

Perfect for:

* Travel photo organization
* Family photo backup
* RAW image archive cleanup
* External SSD / NAS management
* Content creator workflows

---

# Features

* Batch rename photos and videos
* Rename files by EXIF capture date
* Automatic numbering
* RAW / DNG support
* Video metadata support
* Preview before renaming
* Windows Explorer right-click integration
* Portable executable (no installation required)

---

# Example

Before:

```text id="6cq9ci"
IMG_4821.jpg
IMG_4822.jpg
IMG_4823.jpg
```

After:

```text id="1hz6m6"
Trip_Seoul_20260426_01.jpg
Trip_Seoul_20260426_02.jpg
Trip_Seoul_20260426_03.jpg
```

---

# Supported Formats

## Photos

```text id="m4du20"
.jpg .jpeg .png .bmp .tif .tiff .heic .heif
```

## Videos

```text id="50xgic"
.mp4 .mov .avi .mkv
```

## RAW (optional)

```text id="rjdz0m"
.cr2 .cr3 .nef .arw .dng .orf .rw2 .raf .pef .srw .rwl .x3f
```

---

# How It Works

Sortory generates filenames using:

```text id="nq2u0d"
prefix_YYYYMMDD_NN.ext
```

Date priority:

1. EXIF capture date
2. Video creation date
3. File creation date
4. Date detected in filename
5. File modified date

---

# Folder Processing Modes

## Process Subfolders

Each subfolder is processed separately.

Folder names automatically become filename prefixes.

Example:

```text id="8okzk0"
Travel/IMG_0001.jpg
→ Travel_20260426_01.jpg
```

---

## Process Current Folder Only

Rename only files inside the selected folder.

Custom prefix can be entered manually.

---

# Safety Features

Sortory uses a two-step temporary rename process to avoid filename conflicts during batch operations.

Files are previewed before execution.

Unsupported or skipped files are shown in gray.

---

# Privacy & Security

All processing happens locally on your PC.

Your photos, videos, and files are NEVER uploaded to any server.

Sortory does not collect personal data.

---

# Download

Download the latest version from the Releases page.

---

# Windows SmartScreen Warning

Because Sortory is currently an unsigned executable, Windows may display a SmartScreen warning during first launch.

This is common for independent software distributed outside the Microsoft Store.

You can continue by clicking:

```text id="2gfnp9"
More info → Run anyway
```

---

# Roadmap

Planned features:

* Undo rename
* Recursive folder processing
* Duplicate detection
* Custom rename templates
* Automatic watch folders
* NAS workflow improvements

---

# Feedback

Bug reports and feature suggestions are welcome.

If Sortory helped organize your photo library, please consider starring the repository ⭐

---

# License

Copyright © Lifematic Team

All rights reserved.
