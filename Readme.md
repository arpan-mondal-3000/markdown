# This is a tutorial for Markdown files

- There are three type of headings which can be written using "#", "##" and "###" tags. The examples are written below.

# Heading 1

## Heading 2

### Heading 3

- A horizontal line can be drawn using "---" tag.

---

- Use "\*\*Your text\*\*" to make your text bold and "\*Your text\*" to make your text italics.

**Sample bold text**

_Sample Italics text_

- A checkbox can be made by using the "- [x]" tag for already checked version and "- [ ]" can be used for checked version. This is not a normal markdown syntax and it only works in GitHub.
- [x] This is a checked checkbox.
- [ ] This is an unchecked checkbox.

- Emojis can be placed by ":emoji name:" tag or it can be placed directly are UTF-16 is supported everywhere.
  :joy: :smile: :car: :monkey: :man: 😘 😎

- Superscript can be written using "\^sup^" and subscript can be written using "\~sub~" tags.
  (a + b)^2^ = a^2^ + b^2^ + 2ab
  H~2~O, CH~4~

- Highlighted text can be written using "\==your text==" tag.
  ==This is a highlighted text==

- Strikethrough can be written using "\~~your text~~" tag.
  ~~This is a strikethrough~~

- The ">" tag can be used to write a blockquote

  > This is a blockquote

- The "-" tag can be used to make unordered list with bullet points. I have been using this all along to make this list.

- Backtics (\`your code\`) can be used to write code single line code. For multiline code use three backtics and write the name of the language at first to get syntax highlighting.

\`\`\`javascript
your multiline code
\`\`\`

`console.log("This is a singleline code");`

```javascript
console.log("This is a multiline code");
console.log("This is in a Markdown file");
```

```c
#include<stdio.h>
int main()
{
   printf("Hello World");
   return 0;
}
```

```cpp
#include<iostream>
using namespace std;
int main()
{
   cout << "Hello World";
   return 0;
}
```

- Tables can be made like this:

  | Syntax    | Description |
  | --------- | ----------- |
  | Header    | Title       |
  | Paragraph | Text        |

- Alignment in tables can be made by using colons.

  | Syntax    | Description |   Test Text |
  | :-------- | :---------: | ----------: |
  | Header    |    Title    | Here's this |
  | Paragraph |    Text     |    And more |

- To make a link use "\[]()" tag. The name of the link is written inside of the square brackets and the link to follow is written inside the parenthesis.

[GitHub](https://github.com/arpan-mondal-3000)
[LinkedIn](https://www.linkedin.com/in/arpan-mondal-a1b43a28a/)

- Images can be used by using the "\!\[]()" tag. The ! states that the link is for an image, alternative text is written inside the square brackets and the link of the image is written in the parenthesis. Image size cannot be controlled.

1. Image from local file:
   ![Coding](./image.jpg)

2. Image from web link:
   ![Coding](https://images.unsplash.com/photo-1515879218367-8466d910aaa4?q=80&w=2069&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
