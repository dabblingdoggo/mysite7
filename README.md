<!-- KaTeX -->
<link rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/katex@0.13.11/dist/katex.min.css"
    integrity="sha384-Um5gpz1odJg5Z4HAmzPtgZKdTBHZdw8S29IecapCSB31ligYPhHQZMIlWLYQGVoc"
    crossorigin="anonymous">
<script defer
    src="https://cdn.jsdelivr.net/npm/katex@0.13.11/dist/katex.min.js"
    integrity="sha384-YNHdsYkH6gMx9y3mRkmcJ2mFUjTd0qNQQvY9VYZgQd7DcN7env35GzlmFaZ23JGp"
    crossorigin="anonymous"></script>
<script defer
    src="https://cdn.jsdelivr.net/npm/katex@0.13.11/dist/contrib/auto-render.min.js"
    integrity="sha384-vZTG03m+2yp6N6BNi5iM4rW4oIwk5DfcNdFfxkk9ZWpDriOkXX8voJBFrAO7MpVl"
    crossorigin="anonymous"></script>
<script>
    document.addEventListener("DOMContentLoaded", function () {
        renderMathInElement(document.body, {
            // customised options
            // • auto-render specific keys, e.g.:
            delimiters: [
                { left: '$$', right: '$$', display: true },
                { left: '$', right: '$', display: false },
                { left: '\\(', right: '\\)', display: false },
                { left: '\\[', right: '\\]', display: true }
            ],
            // • rendering keys, e.g.:
            throwOnError: false
        });
    });
</script>




# $ \KaTeX $ Test

$$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

