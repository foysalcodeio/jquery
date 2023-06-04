# get data using .val()
Example:
```
<body>

    <div>
        <label for="">Enter the value</label>
        <input type="text" id="myInputValue">
        <button type="button" id="myShowBtn">Show details</button>
    </div>
    <!-- main page -->
    <!-- https://cdnjs.com/libraries/jquery -->
    <!-- <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script> -->
    <!-- or -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.0/jquery.min.js" integrity="sha512-3gJwYpMe3QewGELv8k/BX9vcqhryRdzRMxVfq6ngyWXwo03GFEzjsUm8Q7RZcHPHksttq7/GFoxjCVUjkjvPdw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>


    <script>
        $(document).ready(function(){
            $('#myShowBtn').click(function(event){
                event.preventDefault();

                var str = $('#myInputValue').val();
                alert(str);
                console.log(str);
            })
        })
    </script>
</body>
```
