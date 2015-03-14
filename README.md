# jQuery List Pagination Plugin

To use this plugin you need to include jquery.js and jquery.pagination.js in your document.

```html
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
  <script src="../js/jquery.pagination.js"></script>
```

A sample usage will be

```html
  <script type="text/javascript">
    $(document).ready(function() {
      $(".alphas").pagination({
        panel: "top",
        cssClass: "paginator",
        innerClass: null,
        style: "none",
        withPerPageSelect: false,
        perPage: 4,
        descTemplate: "Page #{page} of #{pages}",
        beforeClick: function(collection) {
          alert("beforeClick");
        }
      });
    });
  </script>
```

To see the demo [click here](https://github.com/louiezhao/jquery-list-pagination/blob/master/example.html).
