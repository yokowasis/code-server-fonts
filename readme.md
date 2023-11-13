# Langkah - Langkah

1. copy css dan fonts ke folder `/usr/lib/code-server/lib/vscode/out/vs/workbench`
2. edit `/usr/lib/code-server/lib/vscode/out/vs/code/browser/workbench/workbench.html` tambahkan code berikut di baris paling bawah

```html
<link
  rel="stylesheet"
  href="{{WORKBENCH_WEB_BASE_URL}}/out/vs/workbench/fonts.css"
/>
```
