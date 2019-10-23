<script>
let name = "pleb!";
let Heding = "Velkommen til en svelte startside!";
let underhed = "her kan du finne noen css & pwa test porsjekter";

let pwa = "PWA";
let ScrollE = "Scroll event";
let Svelte = "Svelte.js";
let pig = "DOM Pig game";
let src = "/U.svg";
</script>


<style>

@import url('https://fonts.googleapis.com/css?family=Hind+Madurai:600&display=swap');



.navbar{
    position: absolute;
    top: 0;
    left: 0;
    height: auto;
    margin: 10px;
    width: 240px;
    background-color:whitesmoke;
    box-shadow: 0px 0px 11px 0px rgba(0, 0, 0, 0.13);
    border-radius: 15px;
    padding: 15px; 
    font-family: 'Hind Madurai', sans-serif;
}




.nav-Img{
    width: 100%;
    background-size: contain;
}

.Button-Holder{
    display: grid;
	grid-template-columns: 1fr 1fr;
    grid-gap: 15px;
    position: absolute;
    background-color:whitesmoke;
    left: 0;
    right: 0;
    height: 62px;
     border-radius: 15px ;
      box-shadow: 0px 0px 11px 0px rgba(0, 0, 0, 0.13);
    padding: 15px;
    margin: 25px auto;
    font-family: 'Hind Madurai', sans-serif;
    text-decoration: none;
 
}

.BT{
     background-color: #1d666059;
    text-align: center;
    font-size: 0.9rem;
    border-radius: 15px;
    box-shadow: inset 2px 2px 8px 0.2px rgba(0, 0, 0, 0.13);
    padding-top: 25px;
    cursor: pointer;
   color: #333;
   font-family: 'Hind Madurai', sans-serif;
       text-decoration: none;

}
.BT:hover{
        background-color: #1e686259;
        opacity: 0.8;
        transition: 0.5s;
    }



.Small{
    display: grid;
}
.nav-Small{
    align-content: center;
    text-align: center;
    width: 100px;
  
}

.navbar_2{
    text-align: center;
    padding: 14px;
    background-color:whitesmoke;
    margin: auto;
    text-align: center;
    width: 45%;

   
    border-radius: 15px;
    box-shadow: 0px 0px 11px 0px rgba(0, 0, 0, 0.13);
    font-family: 'Hind Madurai', sans-serif;
}


.nav-ul{
    padding: 0;

}
.nav-li{
    display: inline;
    text-align: center;
    list-style-type: none;
   font-family: 'Hind Madurai', sans-serif;
}


.nav-A{
    
    color: #3D414C;
  background-color: #1e686259;
    text-align: center;
    font-family: 'Hind Madurai', sans-serif;
    font-weight: 600;
    padding: 15px;
     box-shadow: inset 2px 2px 8px 0.2px rgba(0, 0, 0, 0.13);
    border-radius: 12px;
}.nav-A:hover{
      background-color: #1e686259;
        opacity: 0.8;
        text-decoration: none;
        border-right: 12px;
        transition: 0.5s;
   
}




@media only screen and (max-width: 500px) {

        .nav-Small{
            align-content: center;
            text-align: center;
            padding-top: 10px;
            padding-bottom: 10px;
            
        }

        .navbar_2{
            padding: 1px;
            float: left;
            margin-left: -20px;
            height: 5%;
            margin-top: 0px;

        }
        .nav-li{
            display: block;
            padding: 15px;
        }

    .nav-A{
        color: #333;
        background-color: transparent;
        text-align: center;
        font-family: 'Hind Madurai', sans-serif;
        font-weight: 600;
        margin-left: -50px;
        padding-left: 85px;
        padding-top: 10px;
        width: 100%;
        padding-bottom: 10px;
        box-shadow: none;
    }
    .nav-A:hover{
            background-color: #1e686259;
            border-radius: 1px 51px 51px 1px;
            transition: 0.5s;
            opacity: 1;
            text-decoration: none;
    
    }

}
@media only screen and (max-width: 1800px) {
 
        .navbar{
            display: none;
    
        }

    .Button-Holder{
        display: none;
  
         }
    }
     
@media only screen and (min-width: 1800px) {
 
        .navbar_2{
            display: none;
            
        }
        .nav-Small{
            display: none;
            
    
    }

}
</style>






<div class="Small">
   <img class="nav-Small" src={src} alt="Logo">
        <div class="navbar_2">
            <ul class="nav-ul">
                <li class="nav-li"><a class="nav-A" href="http://www.sktech.no/">Domene</a></li>
                <li class="nav-li"><a class="nav-A" href="https://svelte.dev//">{Svelte}</a></li>
            </ul>
        </div>
</div>

<div class="navbar">
    <img class="nav-Img" src={src} alt="img"> 
        <div class="Button-Holder">
            <a class="BT" href="http://www.sktech.no/">Domene</a>
            <a class="BT" href="https://svelte.dev//">{Svelte}</a>
        </div>
</div>
