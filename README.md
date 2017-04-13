## Huajh Awesome Latex CV 中文版本

English Version is in the [master branch](https://github.com/huajh/awesome-latex-cv/tree/master)

### 样例

中文样例: [PDF](http://huajh7.com/cv/awesome-cv-cn.pdf)

[![Example](http://huajh7.com/img/cv/awesome-cv-cn-1.png)](http://huajh7.com/cv/awesome-cv-cn.pdf)
[![Example](http://huajh7.com/img/cv/awesome-cv-cn-2.png)](http://huajh7.com/cv/awesome-cv-cn.pdf)


### 编译

+  采用 `xelatex` 编译。
+  需要 [fontawesome Package version 4.6.3.2.](http://www.ctan.org/tex-archive/fonts/fontawesome) 或更高版本（已经放在仓库的主目录下）。
+  中文支持借鉴[billryan/resume/tree/zh_CN的中文分支](https://github.com/billryan/resume/tree/zh_CN),`zh_cn-adobefonts_external.sty`,`zh_cn-adobefonts_internal.sty`和adobe字体库(在`fonts/zh_cn-adobe/`目录下,56.4MB)都来自于该仓库分支，感谢分享。



### The Latex 文件结构

```matlab
% cls file
awesome-source-cv.cls   

% main file 主函数
huajh-awesome-cv.tex

%subsection
  - section_headline.tex
  - section_education.tex
  - section_publications.tex
  - section_skills.tex
  - section_experience_short.tex
  - section_languages.tex
  - section_awards.tex
  - section_interests.tex
```