# dsh-client-ui-skin-dnd — 署名与出处

《龙与地下城》D&D 主题皮肤。

## 代码与设计

- 皮肤 chrome 结构（dsw token 重映射、alias/aion 变量、滚动条/链接/选区/代码图配色）以
  `@linxin666/dsh-client-ui-skin-dragon-heir`（dsh-web-ui，BSD-3-Clause）的样式骨架为模板，
  由本皮肤构建脚本按 D&D 配色表整体重映射生成。
- D20 骰子 favicon 为原创 SVG。

## 背景美术

- 背景图由 `gpt-image-2`（OpenAI 图像模型，经 OpenAI 兼容接口生成）绘制：
  亮色《冒险者卷宗》、暗色《龙巢地牢》。
- 发送按钮骰子（「20」面与翻滚精灵帧）同样由 `gpt-image-2` 生成，经 sharp 后处理
  （裁剪 / 去底 / 锐化 / 精灵帧归一化）后内嵌。
- AI 生成图像不享有人类作者署名；生成提示词与流程说明见 README.md「从源码重建」一节。

## 使用条款

本皮肤仅供个人使用。D&D 相关名称与意象属于其各自权利人的商标/知识产权。
