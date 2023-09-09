# Writing Good Documentation

## Step 1: Using Codeblocks

Codeblocks make it *easy* for tech people to **_copy, paste,_** and share code. A cloud engineer uses Codebloocks whenever possible.

Because it allows users to copy and paste their code to replicate or research issues.

- In order to create Codeblocks in Markdown you need three backticks ( ``` )
- Not to be confused with single qutations ( ' )


## Javascript Code Block
```javascript
var today = new Date();
var date = today.getFullYear()+'-'+(today.getMonth()+1)+'-'+today.getDate();
var time = today.getHours() + ":" + today.getMinutes() + ":" + today.getSeconds();
var dateTime = date+' '+time;
 
console.log(dateTime)

```
![Bowie   Beaumont](https://github.com/grover47/github-docs-examples/assets/10213341/922bd712-ab04-42de-84b0-70fa329476b2)

> Here is an example of Quoting using Codeblock in Bash

## References

- [GitHub Flavored Markdown Spec]https://github.github.com/gfm/#what-is-github-flavored-markdown-
- https://docs.github.com/en/contributing/writing-for-github-docs/creating-screenshots#criteria-for-including-a-screenshot
