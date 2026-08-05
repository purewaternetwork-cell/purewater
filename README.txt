V4.1 本地同源版

部署结构:

index.html
ffmpeg/
  index.js
  classes.js
  const.js
  errors.js
  types.js
  utils.js
  worker.js
  ffmpeg-core.js
  ffmpeg-core.wasm

本版本不调用 CDN Worker，避免跨域 SecurityError。

需要将 @ffmpeg/ffmpeg 0.12.x 的 esm 文件放入 ffmpeg 目录。
