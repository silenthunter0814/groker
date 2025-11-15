# groker  


# MathJax 引擎检测

1. 标准公式：$$ \int_0^\infty e^{-x^2} dx = \frac{\sqrt{\pi}}{2} $$

2. MathJax 专属：$$ \require{mhchem} \ce{CO2 + C -> 2CO} $$

3. 取消线：$$ \cancel{abc} $$

**设置**
- 按快捷键：Ctrl + Shift + P  
- 输入并选择：Preferences: Open User Settings (UI)  
- 搜索并设置 MathJax: markdown-preview-enhanced

**settings.json**
``` {highlight=13}
{
    "editor.fontSize": 16,
    "files.autoSave": "afterDelay",
    "editor.minimap.enabled": false,
    "workbench.colorTheme": "Visual Studio Dark",
    "editor.formatOnPaste": true,
    "workbench.editor.enablePreview": false,
    "emmet.preferences": {},
    "workbench.settings.applyToAllProfiles": [],
    "git.confirmSync": false,
    "git.enableSmartCommit": true,
    "editor.autoIndentOnPaste": true,
    "markdown-preview-enhanced.mathRenderingOption": "MathJax"
}
```

**git configration**
- git config --global user.name "Silent Hunter"  
- git config --global user.email zhangliwen000@gmail.com  
- git config --global init.defaultBranch main  
- git config --global pull.rebase true  

- git pull  
- git push
- git commit

**脚注**
Content [^1]
[^1]: Hi! This is a footnote

Content [^2]
[^2]: Hi! This is a footnote

**上标**
30^th^

**下标**
H~2~O

**缩略**
*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium
The HTML specification
is maintained by the W3C.

**标记**
==marked==

**提示信息**

!!! note 注释
    This is the admonition body

!!! info 信息
!!! tip 要点
!!! caution 警告
!!! example 例题1.1 计算积分
    $f(x) = \int f(x)dx$

