# set a value input field
```
 <script>
        $(document).ready(function(){
           var name = "Ahmed";
           $('#myInputBox').val(name);
        })
    </script>
```
#click and add text paragraph
```
<body>
    <div>
        <p id="MyPara"> </p>
        <button type="button" id="myButton">Click to Add</button>
    </div>
    
    <!-- main page -->
    <!-- https://cdnjs.com/libraries/jquery -->
    <!-- <script src="https://code.jquery.com/jquery-3.6.0.min.js" integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4=" crossorigin="anonymous"></script> -->
    <!-- or -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.0/jquery.min.js" integrity="sha512-3gJwYpMe3QewGELv8k/BX9vcqhryRdzRMxVfq6ngyWXwo03GFEzjsUm8Q7RZcHPHksttq7/GFoxjCVUjkjvPdw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script>
        $(document).ready(function(){
            $("#myButton").click(function(event){
                event.preventDefault();

                var paragraph = "This is me and I am self-learner";
                $("#MyPara").text(paragraph);
            })
        })
    </script>
</body>
```
