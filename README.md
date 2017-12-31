# summernote-lists
A [Summernote](http://summernote.org/) extension that allows additional formatting of lists.

### Additional styles

Sets the `list-style-type` of <ul> and <ol> elements.  Options are:


### Usage

1. Include the js and css
2. add `listStyles` to your toolbar after `ul` or `ol`:

        $('#summernote').summernote({
            toolbar: [
                ...
                ['para', ['ul', 'ol', 'listStyles', 'paragraph']],
            ]
        });

### Example

See Example/example.html
