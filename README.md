# pandoc
A template made from markdown that can be converted to anything

Use the following command to make a epub from your markdown files

```bash
  pandoc -t epub3 --epub-cover-image cover.jpg --epub-stylesheet style.css -S -o demo.epub title.txt\
  01-introduction.md
```
