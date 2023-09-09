<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        /* *{ margin:0px;
            padding:0px;
            box-sizing:border-box;
        } */
        .crd3{background-color: #44dcc6;
        border:2px solid black;
        height:100vh;
        width:100vw;
        display:flex;
        justify-content:center;
        align-items:center;}
        .crd3m{height:75vh; width:75vw;
        background-color: #383535;
        border:1px solid black;
        display:flex;
        flex-direction:row;
        justify-content:center;
        position:relative;}
        .crd3ml{
        height:100%; width:50%;
        display:flex;
        flex-direction:column;
        justify-content:space-evenly;
        align-items:center;
        text-align:center}
        .crd3m img{width:50%; 
        height:100%;
        float:right;
        overflow: auto;}
        #lastcrd3{display:flex;
        flex-direction:row;
        justify-content:space-evenly;
        align-items:center;}
        #crd3item{width:100%;
        display:flex;
        flex-direction:column;
        justify-content:space-evenly;
        align-items:center;
        /* line-height:10px; */ }
        #crd3num{font-size: 1.7rem;
        font-weight: bold;}
        #crd3unit{font-size:smaller;}
       
        
    </style>
</head>
<body>
    <div class="crd3" id="1">
        <div class="crd3m" id="2">
                <div class="crd3ml">
                    <div><h2>Get insights that helps your business grow</h2></div>
                    <div ><p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt, consequatur iste perferendis quibusdam pariatur nisi quae quam! Voluptatibus, deserunt quas?</p></div>
                    <div id="lastcrd3">
                        <div id="crd3item">
                            <div id="crd3num">10k+</div>
                            <div id="crd3unit">Comments</div>
                        </div>
                        <div id="crd3item">
                            <div id="crd3num">214</div>
                            <div id="crd3unit">Paid Users</div>
                        </div>
                        <div id="crd3item">
                            <div id="crd3num">12M+</div>
                            <div id="crd3unit">Views</div>
                        </div>
                    </div>
                </div>
   
                <img src="chana_masala.jpg" alt="chana"  >
                
        </div>
    </div>
    
</body>
</html>
