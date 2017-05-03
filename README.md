<script>
    $(document).ready(function(){
        $("<iframe />").attr("src", "https://rezon.gitbooks.io/rezon-faq/content/")
            .attr("frameborder", 0)
            .attr("border", 0)
            .attr("width", "100%")
            .attr("height", "100%")
            .appendTo($(".body-inner"));
        $(".book-header").remove();
    });
</script>
