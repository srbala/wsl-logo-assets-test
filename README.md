# WSL Logo Assets test

This web based tool was created so I can visualize what images **resized** with sharp will look in sections of content like bootstrap cards and elements with CSS `background:cover`.

## Install

Bog standard, git clone, npm install and run.

## Docker

```
services:
  sharp-test:
    volumes:
      - ./my_images/:/src/images
    ports:
      - 3000:3000
```
