<%*  
const title = await tp.system.prompt("Slide title");  
%>
--- 
title: <% title %>
summary: 
tags: 
  -
published: true
created: <% tp.file.creation_date("YYYY-MM-DD HH:mm:ss") %>
modified: <% tp.file.last_modified_date("YYYY-MM-DD HH:mm:ss") %>
createdBy: Bo Xu
---
# <% title %>

---
title: 用 Continual Learning 改进 LoRA 的局限
summary: 关于 LoRA 改进的实验进展
tags:
  - LLM
  - PEFT
  - LoRA
  - continual-learning
published: true
---
