## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/jeffreyVianai/jeffreyvianai.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jeffreyVianai/jeffreyvianai.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

___________________


---
title: Optimizing Models 
description: You can deploy your model as you registered it, or optimize it with open source optimization tools, such as ONNX and PyTorch, or use Vianai's proprietary optimization called DVQ.  
keywords: dvq, onnx, torch, pytorch
permalink: main_optimizing_models.html
sidebar: tree  
layout: default

---

# {{ page.title }} 

{{ page.description }}

#### Prerequisites

- The model to optimize must have been registered. See [Registering Models](main_registering_models.html).

#### Procedure

1. Open the platform to the **Optimize Models** tab.  
   - The entire folder structure of registered models appears in the main window.
   - If you just registered the model, then the folder system expands to show that model and the versions registered under it.  

1. Click version (v1, v2, etc.) under the name of the registered model you want to optimize.  

   A list with the available optimization methods expands under the version, and a chart with control buttons appears in the right panel.  

1. Check the **Optimize** button in the right panel.  

	The **Optimization Preferences** dialog box appears.

1. Check any of the optimizations you want to run.

1. Click **Confirm**.

1. Monitor the job in the **Jobs** window. 

1. Click the **Optimization Results** button to view details of the different optimizations.


#### Results

You have optimized the model, and now you can deploy it. See [Deploying Models](main_deploying_models.html).





