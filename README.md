# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown, you need to use three backticks (`)
- Not to be confused with a quotation (')

```
# Define a Person Class
class Person
  # Constructor
  def initialize (name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

  # Instance method to return a greeting
  def greeting
    "Hello, my name is #{@name} and I am #{@age} years old."
  end
end
```

- When you can, you should attempt to apply syntax highlighting to your codeblocks

```ruby
# Define a Person Class
class Person
  # Constructor
  def initialize (name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

  # Instance method to return a greeting
  def greeting
    "Hello, my name is #{@name} and I am #{@age} years old."
  end
end
```

- Make note of where the backtick button is located.
- It should appear above the tab key.
- It may vary based on your keyboard type.

<img width="360px" src="https://github.com/JPrime88/github-docs-example/assets/145236626/3cc47851-2031-4690-9fcd-045fa6e2e0cd" />

Good Cloud Engineers use cdeblocks for both code and errors that appear in the console.



```bash
Traceback (most recent call last):
        2: from/usr/bin/irb:23:in '<main>'
        1: from (irb):1
RuntimeError: This is a custom error message
```

> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavored Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (Optional)

Github Flavored Markdown (GFM) supports emoji shortcuts.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️ |

# Step 5 - How to create a table


You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:` | 🌩️ |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

![Pipe Character on Keyboard](https://github.com/JPrime88/github-docs-example/assets/145236626/f5fa2a22-5b98-4f2d-8ef1-bc9ad76bffdf)


## External References

- [Github Flavored Markdown Spec](https://github.github.com/gfm/#:~:text=GitHub%20Flavored%20Markdown%2C%20often%20shortened,a%20strict%20superset%20of%20CommonMark.) 
- [Basic Writing and Formatting Syntax(Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
