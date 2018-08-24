# pandoc
A template made from markdown that can be converted to anything

Use the following command to make a epub from your markdown files

```bash
  pandoc -t epub3 --epub-cover-image cover.jpg --epub-stylesheet style.css -S -o demo.epub title.txt\
  chapters/01-introduction.md
```

To convert to latex or pdf use the following

```bash
  pandoc demo.epub -o demo.tex
  pandoc demo.epub -o demo.pdf

  # In case the PDF rendering does not work
  # run the following command as root
  texconfig rehash
```
