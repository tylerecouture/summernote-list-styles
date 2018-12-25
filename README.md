# summernote-lists
A [Summernote](http://summernote.org/) extension that allows additional formatting of lists.

### Additional styles

Sets the `list-style-type` of `<ul>` and `<ol>` elements.  Options are:
<br>1. Numbered<br>
a. Lower Alpha<br>
A. Upper Alpha<br>
i. Lower Roman<br>
I. upper Roman<br>
• Disc<br>
◦ Circle<br>
□ Square<br>

### Usage

1. Include the js and css
2. add `listStyles` to your toolbar after `ul` or `ol`:

        $('#summernote').summernote({
            toolbar: [
                ...
                ['para', ['ul', 'ol', 'listStyles', 'paragraph']],
            ]
        });

### Working Examples

* bootstrap3: https://rawgit.com/tylerecouture/summernote-list-styles/master/Example/example.html
* bootstrap4: see `Example/example-bs4.html`

