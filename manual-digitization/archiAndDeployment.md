Architecture & Deployment
=======

System Diagram
----------
![](https://drive.google.com/uc?export=view&id=1uTpAx2oax583AJhiDk9JBQwJIj_uBcHm)

Source Code File System
----------
### index.html
![](https://drive.google.com/uc?export=view&id=1rxljWOjUJFQjnWSRKOcuF4bN77azsgj4)
> We made use of an open source markdown - website conversion tool called **MDwiki**. This file is downloaded from the said source. And it automates the rendering of our `.md` files into a website with proper formatting.

### config.json

``` json
{
    "useSideMenu": true,
    "lineBreaks": "gfm",
    "additionalFooterText": "All content and images &copy; by MySuki, Inc.",
    "anchorCharacter": "#"
}
```
> This file manages some available configuration for further customization of our markdown website.

### navigation.md

```markdown
# Manual Digitization

[Introduction](index.md)

[Markdown Syntax]()

  * [Basic Syntax](basicSyntax.md)
  * [Some Advanced Syntax](advanceSyntax.md)

[Architecture & Deployment](archiAndDeployment.md)

[Next Steps](nextSteps.md)

[gimmick:theme](journal)

```

> This file is used to define the navigation items on the menu and this is also where we set the theme for our website.

### xxx.md

![](https://drive.google.com/uc?export=view&id=1arO1YHcrA0OCts9DR-RW9QmeNwNfEQzr)
> These are the files referenced on `navigation.md`. This is where we put the contents of our website/manual using the defined markdown format.