## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/coraou/Myudacityprojects/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/coraou/Myudacityprojects/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

### Summary

The data visualization is based on a dataset that includes information of 891 passengers on Titanic. The visualization aims to provide some intuitions about how to travel safely through exploring the relationship between the presence of travel companions and the survival rate.

### Design

## Chart Types:
As I want to show the proportions of groups, I only have two alternatives——pie chart and bar chart. But as pie charts are less effective than bar charts (in that pie charts use more visual encodings to convey the same information than bar charts), I chose bar charts in this visualization.

## Visual encodings:
x position: groups(Alone, With siblings or spouses, With parents or children)
y position: the proportions

## Story:
At first, I wanted to show an animation of the story. But setting a suitable time interval between different parts of the story is too difficult (because different people read at different speed). So later I created buttons so that readers can control the flow of the story by themselves.
The story is followed by an interaction which allows the readers to explore by themselves.
  
## Libraries:
As the bar charts are not complicated, I used dimple.js to create them.
Additionally, I also used d3.js.
  
