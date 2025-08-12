# React Transformer TextToSpeech

- transformer
   transformer.js AI 机器学习库
   来自于huggingface 全球最大开源大模型社区
   将模型下载到前端浏览器，JS 开发者的智能战场未来


- 
  - pnpm i @xenova/transformers
  - pnpm i tailwindcss @tailwindcss/vite
## 项目亮点
   - 使用transformer.js 的端模型
   - 使用tailwindcss 原子css 几乎不需要写样式了
      类名文档语义很好，特别适合AI 生成
   - webworker  nlp任务
      1. 延迟加载大模型
      2. 在组件挂载之后实例化 性能好
      3. 卸载时移除事件
   - 封装组件 
## 项目难点