# Tachyons issues

... and that's a **killer**.

That is _functional CSS_, which means it's _not_ cascaded.

Each element needs to get its very own styling, if i get that correctly.

## Why is that an issue?

While it is **really nice to work with**, it is not suited for a blog, because the `{{.Content}}
parts of a page in the go templates would _not_ receive styling (_not_ cascaded, remember?)

So all images, headers, etc. in there would _maybe_ get the appropriate font _type_, but not
even the font size would be correct. Let's not talk colors, etc.
