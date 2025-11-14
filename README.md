# groker  


# MathJax 引擎检测

1. 标准公式：$$ \int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2} $$

2. MathJax 专属：$$ \require{mhchem} \ce{CO2 + C -> 2CO} $$

3. 取消线：$$ \cancel{abc} $$

4. 右下角应显示：`Powered by MathJax`  

按快捷键：Ctrl + Shift + P  
输入并选择：Preferences: Open User Settings (UI)  
搜索并设置 MathJax: markdown-preview-enhanced


|                        设置项                         |   正确值   |        明         |
|----------------------------------------------------|---------|------------------|
| Markdown Preview Enhanced: Math Rendering Option   | MathJax | 强制使用 MathJax 引擎  |
| Markdown Preview Enhanced: Enable Script Execution | 勾上      | 允许加载扩展（如 mhchem） |
| Markdown Preview Enhanced: Live Update             | 勾上      | 实时刷新             |






git config --global user.name "Silent Hunter"  
git config --global user.email zhangliwen000@gmail.com  
git config --global init.defaultBranch main  
git config --global pull.rebase true  

git pull  
git push