# Editeur en ligne
<textarea id="text" name="text" rows="80" cols="60"></textarea>

<script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
<script type="text/javascript">
    var text = "";

    $("#text").change(function(){
        text = $("#text").val();
        location.href="#"+text;
    });
</script>