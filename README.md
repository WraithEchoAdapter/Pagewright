Pagewright — Visual PDF Page Editor for Windows
Merge, reorder, rotate and split PDF pages by dragging thumbnails — 100% offline, no upload, no watermark, no install required.

Pagewright is a Windows-first fork of the open-source PDF Arranger project, rebuilt around one promise: double-click the .exe, drop your PDFs, drag pages into order, save. No GTK runtime to install, no broken file associations, no "Open With" menu that shows the wrong name.

Why Pagewright exists
The original PDF Arranger is a genuinely good idea - a small, focused, page-rearranging tool instead of a bloated "PDF suite" - buried under a rough Windows packaging experience:

The Windows installer defaults to a per-user install and silently skips system-wide shortcuts unless you pass TARGETDIR manually.
It doesn't register itself as a PDF handler - no double-click-to-open, and "Open With → PDF Arranger" shows a description string instead of the app name.
Users have hit wrong-DLL crashes when other GTK-based apps are installed alongside it, and the installer publisher field reads UNKNOWN.
Pagewright fixes exactly this: a single native portable .exe, correct file association on first run, no GTK side-install, no publisher confusion. Same trusted merge/split/rotate/crop engine underneath - just built the way a Windows user expects a Windows app to behave.

Features
Drag-and-drop page reordering with live thumbnail previews
Merge multiple PDFs into one document, or split one into many
Rotate, crop, and delete individual pages without re-exporting the whole file
Undo/redo for every page operation
Fully offline - nothing is uploaded, no telemetry, no account
Portable mode: runs from a USB stick, writes nothing outside its own folder
Proper Windows integration: correct .pdf file association, right-click "Open with Pagewright", signed installer with a real publisher name
Install
Option A — Portable (recommended for most users)

Download Pagewright-portable.exe from Releases
Run it. That's it - no install, no admin rights needed.
Option B — Installer

Download Pagewright-Setup.exe from Releases
Run it, choose install scope (this user / all users)
Pagewright registers as a .pdf handler automatically
How it works
Open Pagewright and drag in one or more PDF files
Pages appear as a thumbnail grid — drag to reorder, right-click to rotate/delete/duplicate
Drop in additional PDFs to merge them at any position
Click Save or Save As — your original files are never overwritten unless you choose to
Frequently asked questions
Is this safe to use for confidential documents? Yes - Pagewright never sends files anywhere. All processing happens locally on your machine.

Does it modify my original PDF? No, unless you explicitly overwrite it. "Save As" is the default.

Can I merge scanned PDFs and text PDFs together? Yes, Pagewright treats every PDF the same regardless of how it was created.

Why not just use an online PDF merger? Online tools require uploading your (possibly sensitive) document to a third-party server. Pagewright never leaves your computer.

Does it support Windows 7 / 8? The portable build targets Windows 10 and 11. Older systems may work but are not officially tested.

Roadmap
 Native right-click "Add to Pagewright" context menu entry
 Drag-and-drop directly onto the taskbar icon
 Page thumbnails for password-protected PDFs
 Batch mode: apply the same page layout to multiple PDFs
Credits & license
Topics / keywords for GitHub
pdf-editor pdf-merge pdf-split pdf-organizer windows portable-app offline-tool drag-and-drop pdf-tools gtk python open-source privacy-tool document-management Search terms this project targets: merge pdf offline, rearrange pdf pages windows, pdf page organizer free, split pdf without watermark, portable pdf editor windows exe.