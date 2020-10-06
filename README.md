# Weaknesses Testing Tool: Towards a Technique to Detect Weaknesses in C Programs.

  A testing technique to reports weaknesses in C programs.

## Abstract
  Several critical systems, such as Linux, are implemented using C language, and a security flaw in these systems may impact a huge number of users. Some tools and strategies are proposed to avoid these security-related issues. Static analysis tools, such as flawfinder and cppcheck, may help in this problem, reporting some kinds of weaknesses. However, they present a high rate of false alarms, a problem reported in a program when no problem actually exists. Despite the effort to provide security support, these systems still have weaknesses, leading to vulnerable code. The number of reported vulnerabilities has been increased in the last years, where more than 17 thousand vulnerabilities were reported to the National Vulnerability Database (NVD) in 2019. To address this problem, we present a technique that associates static analysis and software testing with the aim to detect weaknesses introduced in the code during earlier development stages of C programs. We implement it in a tool called TWT, which reports weaknesses in C programs. To verify our technique’s relevance, we evaluate 49 warnings of 5 different projects and we detect 10 weaknesses of four different kinds: Buffer Overflow, Format String, Integer Overflow, and Race Condition. Overall, our results show evidence that our strategy may help developers anticipate weakness detection in C programs, reducing vulnerability occurrence in operational versions.

## Technique
### Overview

<embed src="images/technique2.0.pdf" width="960px" height="220px" />

## Evaluation
- ...

## Contact
- ...

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/WeaknessesTestingTool/page/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/WeaknessesTestingTool/page/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
