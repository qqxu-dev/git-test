---
scene: git_message
alwaysApply: true
---
# 提交信息生成强制规则
1. 输出**纯文本**，**禁止前后加```、markdown代码块标记**
2. 严格遵循 conventional commits，只输出 commit 正文，无多余换行、无注释、无代码标识
3. 格式：type(scope): desc，可选换行补充详情