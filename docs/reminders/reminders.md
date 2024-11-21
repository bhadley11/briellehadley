# **Helpful Reminders for Coding**


## Using the Terminal

Here’s a handy list of terminal commands and prompts you can use for common tasks. They’re grouped by purpose for easier reference:

---

### **Navigation and File Management**
1. **`ls`**  
   - List all files and directories in the current directory.
2. **`cd [directory_name]`**  
   - Change to a specified directory.
3. **`cd ..`**  
   - Go up one directory level.
4. **`pwd`**  
   - Show the current directory path.
5. **`mkdir [new_directory_name]`**  
   - Create a new directory.
6. **`touch [file_name]`**  
   - Create an empty file.
7. **`rm [file_name]`**  
   - Delete a file.
8. **`rm -r [directory_name]`**  
   - Delete a directory and its contents.

---

### **Git Commands**
9. **`git clone [repository_url]`**  
   - Clone a repository from GitHub to your computer.
10. **`git status`**  
    - Check the status of your Git repository.
11. **`git add [file_name]` or `git add .`**  
    - Stage a file or all files for a commit.
12. **`git commit -m "commit message"`**  
    - Save staged changes with a message.
13. **`git push`**  
    - Push committed changes to GitHub.
14. **`git pull`**  
    - Fetch and merge changes from the remote repository.
15. **`git log`**  
    - View the commit history.

---

### **Working with Files**
16. **`cat [file_name]`**  
    - Display the contents of a file.
17. **`nano [file_name]` or `vim [file_name]`**  
    - Open a file in a terminal-based text editor.
18. **`cp [source_file] [destination]`**  
    - Copy a file to a different location.
19. **`mv [file_name] [new_location_or_new_name]`**  
    - Move or rename a file.
20. **`code .`**  
    - Open the current directory in Visual Studio Code (if installed).

---

### **Python and Virtual Environments**
21. **`python3 [script_name.py]`**  
    - Run a Python script.
22. **`python3 -m venv [env_name]`**  
    - Create a Python virtual environment.
23. **`source [env_name]/bin/activate`**  
    - Activate a virtual environment.
24. **`deactivate`**  
    - Deactivate a virtual environment.
25. **`pip install [package_name]`**  
    - Install a Python package.

---

### **MkDocs and Web Development**
26. **`mkdocs new [project_name]`**  
    - Create a new MkDocs project.
27. **`mkdocs serve`**  
    - Preview your MkDocs site locally.
28. **`mkdocs build`**  
    - Build your MkDocs project for deployment.
29. **`mkdocs gh-deploy`**  
    - Deploy your MkDocs site to GitHub Pages.
30. **`open index.html`**  
    - Open an HTML file in the browser (Mac). Use `xdg-open` for Linux or `start` for Windows.

---

### **Shortcuts and System Info**
31. **`ctrl + c`**  
    - Cancel the current command or process.
32. **`clear`**  
    - Clear the terminal screen.
33. **`history`**  
    - Show your command history.
34. **`uname -a`**  
    - Show system information.
35. **`top`**  
    - View running processes and system usage.

---

### **Search and Text Manipulation**
36. **`grep [search_term] [file_name]`**  
    - Search for a term in a file.
37. **`find . -name "[file_name]"`**  
    - Search for a file in the current directory and subdirectories.
38. **`echo "text" > [file_name]`**  
    - Write text to a file.
39. **`cat [file1] [file2] > [new_file]`**  
    - Combine files into a new file.

---

### **Networking and Internet**
40. **`curl [url]`**  
    - Fetch data from a URL.
41. **`ping [hostname]`**  
    - Test the connection to a server.

---

This list covers many common tasks, but you can customize it with additional commands based on your workflow!

## Using Markdown

Here’s a a similar list of markdown features that you can reference when building a website!

---

### **Headings**
1. **`# Heading 1`**  
   - Use `#` for the largest heading, and add more `#` for smaller headings (up to six levels):  
     **Example:**  
     ```markdown
     # Heading 1  
     ## Heading 2  
     ### Heading 3  
     ```
2. **Keep heading levels consistent** to ensure a logical structure, especially for longer documents.

---

### **Formatting Text**
3. **Bold:**  
   - Use `**` or `__` around text for **bold**:  
     ```markdown
     **Bold Text**  
     __Bold Text__
     ```
4. **Italic:**  
   - Use `*` or `_` around text for *italic*:  
     ```markdown
     *Italic Text*  
     _Italic Text_
     ```
5. **Bold and Italic:**  
   - Combine `***` for ***bold and italic***:  
     ```markdown
     ***Bold and Italic***
     ```
6. **Strikethrough:**  
   - Use `~~` around text for ~~strikethrough~~:  
     ```markdown
     ~~Strikethrough~~
     ```

---

### **Lists**
7. **Unordered Lists:**  
   - Use `-`, `+`, or `*` for bullets:  
     ```markdown
     - Item 1  
     - Item 2  
     ```
8. **Ordered Lists:**  
   - Use numbers followed by periods:  
     ```markdown
     1. First item  
     2. Second item  
     ```
9. **Nested Lists:**  
   - Indent with spaces for sub-items:  
     ```markdown
     - Main item  
       - Sub-item
     ```

---

### **Links and Images**
10. **Links:**  
    - Use `[link text](URL)` to create hyperlinks:  
      ```markdown
      [Google](https://www.google.com)
      ```
11. **Images:**  
    - Use `![alt text](image_URL_or_path)` to display images:  
      ```markdown
      ![Example Image](https://example.com/image.png)
      ```

---

### **Code and Syntax Highlighting**
12. **Inline Code:**  
    - Use backticks `` ` `` for inline code:  
      ```markdown
      Use the `ls` command to list files.
      ```
13. **Code Blocks:**  
    - Use triple backticks `` ``` `` for multi-line code blocks, and specify the language for syntax highlighting:  
      ```markdown
      ```python
      print("Hello, World!")
      ```
      ```

---

### **Tables**
14. **Basic Table Syntax:**  
    - Use pipes `|` and hyphens `-` to create tables:  
      ```markdown
      | Header 1 | Header 2 |  
      |----------|----------|  
      | Row 1    | Data     |  
      | Row 2    | Data     |
      ```

---

### **Blockquotes**
15. **Blockquotes:**  
    - Use `>` for quoting text:  
      ```markdown
      > This is a blockquote.
      ```

---

### **Horizontal Rules**
16. **Horizontal Line:**  
    - Use `---`, `***`, or `___` to create a horizontal rule:  
      ```markdown
      ---
      ```

---

### **Lists with Checkboxes**
17. **Task Lists:**  
    - Use `- [ ]` for an unchecked box and `- [x]` for a checked box:  
      ```markdown
      - [ ] Task 1  
      - [x] Task 2 (Completed)
      ```

---

### **Special Characters**
18. **Escape Special Characters:**  
    - Use a backslash `\` before special Markdown symbols to display them as text:  
      ```markdown
      Use `\*` to show an asterisk.
      ```

---

### **Tips for Advanced Markdown**
19. **Use Markdown Preview:**  
    - In editors like Atom or VS Code, use the preview feature (`Ctrl+Shift+M` in Atom) to see rendered Markdown.
20. **Use HTML for Extensions:**  
    - You can embed HTML directly for features not natively supported by Markdown:  
      ```markdown
      <details>
      <summary>Click to expand!</summary>
      Hidden text here.
      </details>
      ```

---

### **Markdown for GitHub**
21. **GitHub-Flavored Markdown (GFM):**  
    - Supports extended features like task lists, tables, and emoji:  
      ```markdown
      - [ ] GitHub supports task lists  
      - :smile: You can use emoji with `:emoji_name:`
      ```
22. **Linking Files:**  
    - Use relative paths for linking files in the same repository:  
      ```markdown
      [ReadMe](docs/README.md)
      ```

---

### **Keep It Readable**
23. **Break lines by adding two spaces** at the end of a line to avoid clutter in long paragraphs.  
24. **Use headings, lists, and horizontal rules** to structure content logically for readability.

This list can serve as a quick reference when you're working with Markdown!
