# English

*"Finally, the final frontier of computer programming."*

English is a non-deterministic programming language that allows you to harness the true potential of your computing device.

Source files go in `.engl` files. Organize them however you'd like.

No code. Just vibes.

## Compile

English will ask OpenAI what it thinks your program should do. It will then emit an intermediate C program, which will be compiled into a binary.

```bash
engl compile [src_dir]
```

## Formatting

English has a very non-opinionated syntax. However, normalizing line breaks, indentation, and trailing newlines aids in collaboration.

```bash
engl format [src_dir]
```

## Linting

English uses [LanguageTool](https://languagetool.org/) to ensure vibe quality.

```bash
engl lint [src_dir]
```

## Check

Format and lint in one pass.

```bash
engl check [src_dir]
```
