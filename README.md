# WebTutorsAtWork

Static download and product website for TutorsAtWork.

## Replace The Placeholder Downloads

The download buttons currently point to:

- `downloads/TutorsAtWork-Android-placeholder.txt`
- `downloads/TutorsAtWork-Windows-placeholder.txt`

When releases are ready:

1. Add the Android APK and the ZIP containing the complete Windows release.
2. Update both download links in `index.html`.
3. Remove the placeholder notice from the download section.

The Windows ZIP must contain `TutorsAtWork.exe`, its DLL files, and the `data`
directory. The executable does not run as a standalone file.

For large release files, host them as GitHub Release assets and use their
release URLs in `index.html`.
