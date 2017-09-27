# Worksheet 2: Character Encoding

## Instructions

- Due on Sunday at Midnight
- Upload to Courseworks
- Make sure you understand / complete the tutorial [here][01] before starting
  with this worksheet.

[01]: https://github.com/dh-notes/dhnotes/blob/master/tutorials/command-line/100-plain-text.md

1. What is a bit? What is a byte?

2. Why is a byte 8 bits?

3. What is the difference between a plain text and for example a .pdf file?

4. Write "hello world" (by hand) in ASCII binary notation (use a look-up table).

5. Using a plain text editor (or `echo 'hello world' > hello.txt`) type "hello
   world" and save the file as `hello.txt`. Verify the length with `wc -c
hello.txt`. How many bytes is it and why?

6. Open the file in MS Word. Save as `hello.docx`. How many bytes of
   information does it contain (use `wc -c hello.docx`) What accounts for the
extra information?

7. Browse through [Office Open XML File Formats][71] specification (you will
   have to download and unzip several files). Find a passage (any interesting
passaging) dealing with accessibility or intellectual property and discuss it
here.

8. What is ECMA? What is the ISO? What are their governing structures?

[71]: http://www.ecma-international.org/publications/standards/Ecma-376.htm

## For an extra challenge

Exercises this week aim to answer a seemingly simple question: Where
physically are the bits representing a simple file, such as hello.txt? How far
can you get in "getting at" (visualizing, addressing) the physical structure
of the stored data?
