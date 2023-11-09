# Practice: Formatting Text

## Practice Exercise: Combining `nl`, `fold`, and `groff` Commands in Linux

This exercise is designed to reinforce your understanding and skills in using the `nl`, `fold`, and `groff` commands in the Linux command line. You will be creating a formatted text document, adding line numbers, applying word wrapping, and finally converting it into a PDF.

### Task Overview:

1. Create a plain text document using `vim`.
2. Add line numbers to the document using the `nl` command.
3. Wrap the text at a specific width using the `fold` command.
4. Format the document into a `troff` file with basic macros.
5. Convert the `troff` file to a PDF using `groff`.

### Step-by-Step Tasks:

#### Step 1: Create a Sample Text File

Use `vim` to create a text file named `exercise.txt`. It should contain several paragraphs of text. If you are not sure what to write, you can generate "lorem ipsum" text or simply write about what you've learned in Linux so far.

```bash
vim exercise.txt
```

_Write your text, then save and exit._

#### Step 2: Numbering Lines

Add line numbers to your document using `nl`. Save the output to a new file called `numbered.txt`.

```bash
nl exercise.txt > numbered.txt
```

#### Step 3: Wrapping Text

Use the `fold` command to wrap text lines to 80 characters wide. Save the output to a file named `wrapped.txt`.

```bash
fold -w 80 numbered.txt > wrapped.txt
```

#### Step 4: Formatting with `groff`

Create a simple `groff` macro file `formatted.groff` using `vim` to give the text some basic formatting. You can add a title, author, and enable the use of the `MS` macro package.

```bash
vim formatted.groff
```

_In `vim`, write the groff macros and text content._

#### Step 5: Convert to PDF

Finally, convert your formatted `.groff` file to a PDF file using `groff`.

```bash
groff -ms formatted.groff -T pdf > output.pdf
```

### Deliverables:

1. `exercise.txt` - Original text file.
2. `numbered.txt` - Text file with added line numbers.
3. `wrapped.txt` - Text file with wrapped text at 80 characters wide.
4. `formatted.groff` - Groff file with basic formatting.
5. `output.pdf` - Final PDF output of the formatted document.
