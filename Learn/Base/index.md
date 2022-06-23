<h1>Bases d'informatique</h1>
<div id="c"></div>
<script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script>
<script type="text/javascript">
    $(document).ready(function() {
        const str = window.location.href;

    const words = str.split('#');
    $("#c").load(words[1]+".html");
    });
</script>