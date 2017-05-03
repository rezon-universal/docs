<script>
    var defer = function (method) {
        window.jQuery ? $(function () {method()}) : (setTimeout(function() { defer(method) }, 50));
    }
    defer(function() {
        $(document).ready(function(){
            $("<iframe />").attr("src", "https://rezon.gitbooks.io/rezon-faq/content/")
                    .addClass("page-iframe")
                    .attr("frameborder", 0)
                    .attr("border", 0)
                    .attr("width", "100%")
                    .attr("height", "100%")
                    .insertAfter($(".book-header"));
        });
    });
</script>
