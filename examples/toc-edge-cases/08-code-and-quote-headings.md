# Fake vs Real Headings

Headings inside fenced/indented code must NOT show in the TOC. A heading inside
a blockquote IS a real heading and *will* show — note where it scrolls to.

## Real Heading Before Code

Lorem ipsum dolor sit amet.

```markdown
## This is INSIDE a fenced code block — not a real heading
### Neither is this one
#### Or this
```

Text between.

    ## Indented-code-block heading — also NOT a real heading
    ### still fake

## Real Heading After Code

Sed do eiusmod tempor incididunt ut labore.

> ## Heading Inside A Blockquote
>
> This h2 lives in a blockquote — cmark still gives it an anchor, so it appears
> in the TOC. Consectetur adipiscing elit.

## Heading with `## hashes in inline code` in its text

Ut enim ad minim veniam, quis nostrud exercitation.

#NotAHeading (no space after hash — this is a paragraph, not a heading)

Final paragraph. Duis aute irure dolor.
