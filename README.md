💥 Comment Annihilator 3000 💥

Clean Code, Zero Effort.

This extension provides a powerful, single-command utility to aggressively remove all single-line comments (//) from your active file, ensuring your code remains clean and compact.

✨ Features

The Annihilator uses precise regex logic to handle two scenarios flawlessly:

Full-Line Comment Removal: If a line contains only a comment (with optional indentation), the entire line is deleted, collapsing the space.

// This entire line will vanish
var x = 1;

becomes:

var x = 1;

Inline Comment Deletion: If a line contains code followed by a comment, only the comment (and the preceding whitespace) is removed. The code and its line break are preserved.

var x = 1; // This part is deleted

becomes:

var x = 1;

URL Protection: The extension will never remove // if it is preceded by a colon (:), protecting links in your code like https://example.com//path.

🚀 Usage

Open the file you wish to clean.

Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).

Search for: Annihilate All Single-Line Comments (Excluding URLs)

Execute the command. Your file is instantly cleaned!
