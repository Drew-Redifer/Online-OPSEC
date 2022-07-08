# Online-OPSEC.net ([https://online-opsec.net](https://online-opsec.net))

A site dedicated to online privacy.

Simple step-by-step text and image-based tutorials for learning basic Online Operational Security.

Suggestions welcome.

## Submission guidelines

- follow the general style of pre-existing articles
- use the root user (i.e. no `sudo`) unless there is a specific need.
- do not preface commands with `$` or `#` or anything.
- use `.svg` files for icons/logos and for illustrative images, keep filesize low
- Use `example.org`
- custom command/file info should be highlighted with `<strong>` tags

### On `<pre>` tags


In-line code should be in `<code>` tags, while codeblocks should be in a `<code>` tag *inside* of a `<pre>` tag.
`<pre>` allows formatting preserving whitespace.
That said, do *not* format `<pre>` tags as following:

```
<pre><code>
	echo "Here is a command."
	echo "Here is another."
</code></pre>
```

but do it like this:

```
<pre><code>echo "Here is a command."
echo "Here is another."</code></pre>
```

**All** whitespace, including tabbing in and initial and final newlines are displayed by `<pre>`.
To maintain consistency and avoid goofy-looking extra lines, add no extra whitespace.
