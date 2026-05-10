<p align="center">

  <img width="1120" height="493" alt="SocialGPT" src="https://github.com/user-attachments/assets/7ce89147-29a3-46af-994b-ff38f8960d01" />

</p>

# SocialGPT: Prompting LLMs for Social Relation Reasoning

**原论文作者**: Wanhua Li, Zibin Meng, Jiawei Zhou, Donglai Wei, Chuang Gan, Hanspeter Pfister:contentReference[oaicite:1]{index=1}  
**论文**: [arXiv:2410.21411v1](https://arxiv.org/abs/2410.21411)  

---

## 📂 汇报 PPT
[Download PPT](https://github.com/user-attachments/files/27562504/5.pptx)


> 点击按钮下载完整 PPT，包含详细技术实现、实验结果及示例。

---

## 📝 论文摘要
- 社会关系识别：从图像中识别如朋友、亲属、同事等关系  
- 提出 **SocialGPT 框架**：结合视觉基础模型(VFMs)与大型语言模型(LLMs)  
- **GSPO算法**：贪婪段提示优化，自动优化 LLM 提示，提高零样本推理性能  
- 可解释输出：LLM 生成自然语言推理说明

---

## 💡 核心贡献
1. 模块化 SocialGPT 框架，零样本社会关系识别  
2. GSPO: 段级优化提示，处理长提示与自由文本输出  
3. 可解释性强：生成社会故事并输出自然语言推理  
4. 强零样本性能：无需额外训练即可竞争或超越传统方法  

---

## 🤔 个人思考
- SocialGPT 可以推广到其他视觉-语言推理任务  
- 段级提示优化在处理长文本任务中效率显著提升  
- 零样本学习结合视觉描述，可用于跨域/少标注场景  
- PPT 中示例对不同图像风格（素描、卡通）有很好的泛化表现  

---

## 🔗 相关链接
- [原论文 PDF](https://arxiv.org/pdf/2410.21411.pdf)  
- [GitHub 仓库主页](https://github.com/Mengzibin/SocialGPT)

---

> **说明**: README 内容用于学术交流，请尊重原论文作者版权。
