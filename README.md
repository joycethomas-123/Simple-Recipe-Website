# Simple-Recipe-Website
Simple recipe website using  html &amp; css
#html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="new.css"
 type="text/css">
</head>
<body>
    <div>
        
        
        <h1 class="recipe">RECIPE</h1>
        <div><h2>BIRIYANI</h2></div>
        <div class="grid-container">
        <div><img class="img" class="grid-item"src="image.jpg"></div>
       
        <div class="column"class="grid-item" >
         <h3 >INGREDIENTS</h3>
          <br>
        <ol>
            <li>1 Kg meat</li>
           <li>1 tbsp salt</li>
            <li>1 tbsp ginger garlic paste</li>
            <li>1 tbsp red chilli paste</li>
            <li> 1 tbsp green chilli paste (sauteed brown onions to taste)</li>
            <li>1/2 tbsp cardamom powder</li>
            <li>3-4 Cinnamon sticks</li>
            <li>1 tbsp cumin seeds</li>
            <li>4 Cloves</li>
            <li>A pinch of maceto taste mint leaves</li>
            <li> 2 tbsp lemon juice</li>
            <li>250 gms curd</li>
            <li>4 tbsp clarified butter</li>
            <li>750 gms semi cooked rice</li>
            <li>1 tsp saffron</li>
            <li>1/2 cup water</li>
        </ol>
        
        </div>
       </div>
        <div class="met"><h3>METHODS OF PREPARATION</h3>
            <ol>
                <li>Clean the meat. Now in a pan add meat, salt, ginger garlic paste, red chilli powder, green chilli paste, sauteed brown onions, cardamom powder, cinnamon, cumin seeds, cloves, mace, mint leaves and lemon juice.</li>
                <br>
                <li>Mix all of these ingredients thoroughly together.</li>
                <br>
                <li>Add curd, clarified butter, semi cooked rice, saffron, water and oil. Mix it well.</li>
                <br>
                <li>Now apply sticky dough on the sides of the pan.</li>
                <br>
                <li>Cover with lid to seal it and cook for about 25 minutes.</li>
                <br>
                <li>Hyderabadi Biryani is ready to eat. Garnish it with boiled eggs, sliced carrots, cucumbers and serve hot.</li>
            </ol>
             </div>

    </div>
</body>
</html>
#css
.recipe{
    text-align: center;
    color: black;
    text-decoration: underline;
}
.img{
    width:600px;
    height:30em;
    border-style:solid;
    border-color:BLACK;
    border-width:1em;
    float: left;
    text-decoration: underline;
}
.column{
    top:50%;
    
    width: fit-content;
    right: 50%;
    width:581px;
    float:left;
   
}
h2{
    text-align: centre;
    color:black;
    text-decoration: underline;
}
h3{
    text-decoration: underline;
}
.grid-container{

    display:grid;
    grid-template-columns: auto auto;
    padding:10px;
   
    
}

.grid-item {
    background-color: rgba(255, 255, 255, 0.8);
    border: 1px solid rgba(0, 0, 0, 0.8);
    padding-left: 30em;
    font-size: 30px;
    text-align: center;
  }
.met{
    
    right:50em;
}
body{
    background-color:#FEAA00;
}
