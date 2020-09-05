# My Visual Studio Code Settings File


**Nguồn tham khảo**: https://viblo.asia/p/my-visual-studio-code-naQZRGDAlvx

---

## Thiết lập dòng 
```json
 "editor.lineNumbers": "relative",
 "editor.renderLineHighlight": "all",
 "editor.lineHeight": <number>,
```

## Caret: Thay đổi kiểu nháy con trỏ:
```json
"editor.cursorBlinking": "phase",
```

## Wrap text:
```json
"editor.wordWrap": "on",
```

## Set lại tab size:
```json
"editor.tabSize": 2,
```

## Đặt ruler để kiểm soát dòng code không quá dài:
```json
"editor.rulers": [80],
```

## Tự động format code khi code và paste:
```json
"editor.formatOnType": true,
"editor.formatOnPaste": true,
```

## Zoom khi dùng chuột:
```json
"editor.mouseWheelZoom": true,
```

## Tắt thanh activity bar:
```json
"workbench.activityBar.visible": false,
```

## Tắt thanh menu bar (Có thể mở thanh này bằng cách bấm phím Alt):
```json
"window.menuBarVisibility": "toggle",
```

## Tự động mở 1 file mới khi mở vscode
```json
"workbench.startupEditor": "newUntitledFile",
```

## Tự động trim các whitespace khi lưu:
```json
"files.trimTrailingWhitespace": true,
```

## Thêm 1 dòng trống vào cuối file khi save:
```json
"files.insertFinalNewline": true,
```

## Cắt bỏ các dòng trống ở cuối file (trừ 1 dòng trống, cài đặt trên và cài đặt này sẽ đảm bảo cho bạn CHỈ có 1 dòng trống ở cuối file)
```json
"files.trimFinalNewlines": true,
```

## Bật tính năng complete với tab khi bạn gõ những từ đầu tiên của code
```json
"editor.tabCompletion": true,
```
