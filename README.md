# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste**, and **share** code.  A good __Cloud Engineer__ uses Codeblocks whenever possible because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown, you need to use three backticks (`).
- This is not to be confused with an apostrophe, AKA single quotation mark (').

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Webpage</title>
    <style>
        /* You can add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
    </header>
    <div class="container">
        <h2>About Me</h2>
        <p>Hello, I'm John Doe. This is a simple webpage.</p>

        <h2>My Interests</h2>
        <ul>
            <li>Web Development</li>
            <li>Programming</li>
            <li>Reading</li>
        </ul>

        <h2>Contact</h2>
        <p>You can reach me at <a href="mailto:john@example.com">john@example.com</a>.</p>
    </div>
</body>

</html>
```

- When you can, you should attempt to apply syntax highlighting to your codeblocks.

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Webpage</title>
    <style>
        /* You can add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
    </header>
    <div class="container">
        <h2>About Me</h2>
        <p>Hello, I'm John Doe. This is a simple webpage.</p>

        <h2>My Interests</h2>
        <ul>
            <li>Web Development</li>
            <li>Programming</li>
            <li>Reading</li>
        </ul>

        <h2>Contact</h2>
        <p>You can reach me at <a href="mailto:john@example.com">john@example.com</a>.</p>
    </div>
</body>

</html>
```

- Make note of where the backtick button is located.
- It should appear above the tab key, but it may vary based on your keyboard type.

<img width="400px" src="https://github.com/gambolputty33/github-docs-example/assets/142690564/b4c33ae9-9e65-4ac1-88b2-1a64075d3de0"
/>

<img width="400px" src="https://github.com/gambolputty33/github-docs-example/blob/main/assets/html-tagst.jpg"
/>

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  File "script.sh", line 6, in <module>
    result = divide_numbers(10, 0)
  File "script.sh", line 3, in divide_numbers
    return a / b
ZeroDivisionError: division by zero
```

> Here is an example of using a codeblock for an error that appears in Bash.

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>1</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcuts.
Here are some examples;

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`  | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:`  | :cloud_with_lightning: |

## Step 5 - How to create a table

You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:`  | :cloud: |
| Cloud with lightning | `:cloud_with_lightning:`  | :cloud_with_lightning: |
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>2</sup>](#external-references)

## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>1</sup>
- [GFM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>2</sup>


