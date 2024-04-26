# Ex.08 Design of a Standard Calculator
## Date:

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
    <script>
        function fn(e){
            if(e.innerHTML == '='){
                output.value=eval(output.value);
            }
            else if(e.id=='back'){
                v=output.value;
                output.value=v.substring(0,v.length-1);
            }
            else if(e.nnerHTML=='C'){
                output.value='';
            }
            else{
                output.value+=e.innerHTML;
            }
        }
    </script>
     <div class="row mx-auto text-center" style="width: 24rem; color: rgb(3, 0, 0);background-color: rgb(94, 4, 251);text-align: center;">CALCULATOR</div> 
         <div class="row mx-auto text-center" style="width: 24rem;background-color: rgb(39, 200, 218);">
        <div class="col-12 my-4"><input type="text" name="" id="output" style="width: 100%;height: 50px;border-radius: 25px;"></div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">(</div>       
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">)</div>
        <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)">C</div>
        <div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)" id="back"><i class="bi bi-backspace"></i></div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">7</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">8</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">9</div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">X</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">4</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">5</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">6</div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">-</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">1</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">2</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">3</div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">+</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">0</div>
        <div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">.</div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">%</div>
        <div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">/</div>
        <div class="m-3 col-11 btn btn-warning rounded-4" onclick="fn(this)">=</div>

        <div style="width: 24rem; color: red;background-color: rgb(0, 0, 0);">SREE HARI K (212223230212)</div> 
        </div>  
</body>
```
## OUTPUT:
NAME:SANJIT P

REGISTER NO:212223230190
![Screenshot 2024-04-26 231647](https://github.com/Sanjit2328/Calc/assets/139331694/c7c6ca00-21cd-4a4e-82e2-4b472f26cb4c)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
