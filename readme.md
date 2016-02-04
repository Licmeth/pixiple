# Pixiple

## What's Pixiple?

Pixiple searches for and lets you compare and manipulate a list of image file pairs sorted according to how similar their pixel and/or metadata content are.

## Screenshot

![Screenshot](screenshot.jpg)

## Features

- Fast, multi-threaded processing, though even with a fast SSD, you will likely be IO-bound.
- Resizable, DPI-aware UI.

## Misfeatures

- Simple, idiosyncratic UI with rough edges.
- Only image file formats supported by Windows Imaging Component (PNG, JPEG, GIF, TIFF, BMP) are processed.
- Only one folder (and all folders below this folder, recursively) is scanned at a time.
- No installer.

## Requirements

Windows 7 (64-bit). May work with Windows Vista and Windows 10.

## What's similar?

Pixiple will easily detect images that are identical, have identical pixel content, are uniformly resized, flipped, rotated (90, 180, 270 degrees) or have minor differences in pixel content.

Pixiple is less well able to detect similar images with significant changes to pixel content (cropping or change of brightness, contrast, saturation, etc).

Pixiple ignores file metadata (name, path, size, date, format) when detecting similarity.
