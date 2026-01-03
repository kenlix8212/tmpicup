
Temu Local Cropper — 3:4 vertical & 1:1
=======================================
- Fixed options: 3:4 (vertical) and 1:1 only. Default is last-used; first run defaults to 3:4.
- Default sizes: 3:4 → 1500x2000; 1:1 → 1500x1500 (you can edit).
- Choose a base folder once; each batch saves into {base}/{SPU}/.
- Uses File System Access API: Chrome/Edge latest recommended. Use "Download current" if unsupported.
- 支持剪贴板粘贴图片（点击页面或预览区后按 Ctrl/Cmd+V）。

测试说明：
- 在桌面 Chrome/Firefox：打开页面，点击预览区域后按 Ctrl/Cmd+V（从图片查看器或网页复制图片）→ 图片应被添加到缩略图并可裁剪。
- 复制图片文件（在文件管理器中复制）或在网页上右键“复制图片”后粘贴；也可以复制图片 URL 并粘贴（若跨域允许，将尝试下载并添加）。
- 在不支持剪贴板读取的浏览器上仍可通过拖拽或「选择/拖入图片」按钮添加图片。
