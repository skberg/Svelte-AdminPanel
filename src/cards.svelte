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



.holder{
	display: grid;
	grid-template-columns: 1fr 1fr;
    grid-gap: 25px;

	position: absolute;
	top: 200px;
	left: 0;
	right: 0;
      max-width: 900px;
      margin: auto;
      padding: 25px;
}
	.Card{
		background-color: #FDFDFD;
		margin: auto;
       
        
        border-radius: 15px;
        border-left: 24px solid #1e686259; 

	}

        .Heding{
           background-color: #1e686259;
            border-radius: 1px 1px 51px 1px;
            margin-top: 0px; 
            width: 55%;
            padding: 10px;
            color: #3D414C;
             font-family: 'Hind Madurai', sans-serif;
            font-weight: 900;
        }

        .P{
            padding-left: 15px;   
                padding-bottom: 15px; 
        }
        .Peding{
            padding: 15px;
            padding-bottom: -15px; 
        
        }

        .Info{
            display: inline; 
            padding: 4px;
            border-radius: 3px; 
            margin: 1px;
            margin-left: 10px; 
            color: #FDFDFD;
            background-color: #3D414C;  
        }



    .btUn{
        margin-top: 25px;
        margin-left: 10px;
        margin-bottom: 10px;
        border-radius: 15px;
        border: none;
        background-color: #1e6862;
        cursor: pointer;
        padding: 10px;
        color: #fff;
        
    }
    .btUn:hover{
        background-color: #1e6862;
        opacity: 0.8;
        transition: 0.5s;
    }


a{
    color:#fff;
    text-decoration: none;
}







@media only screen and (max-width: 700px) {
 .holder{
     grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
 }
 	.Card{
		margin-left: 15px auto;
		margin-right: 15px auto;
		margin-top: 85px;
        margin-bottom: -45px;
   
        width: 85%;
	}
         .Heding{
            background-color: #1e686259;
            border-radius: 1px 1px 51px 1px;
            margin-top: 0px; 
            width: 55%;
            padding: 10px;
            color: #333;
            
        }

}
</style>




<div class="holder">
		<div class="Card" >
			<h3 class="Heding">{ScrollE}</h3>
            <p class="P">Laget den: <b>16/10/2019</b></p>
             <span class="Info">Javascript</span>
              <span class="Info">Html</span>
              <span class="Info">Css</span>
            <p class="Peding">Scroll-Event er en JavaScript teknologi som du kan bruke for å lage nettsiden din litt mere interessant, hovedpoenget i denne teste oppgaven var å lære seg hvordan og hva som må til får å skape slike dynamiske nettsider. Mye av inspirasjon for dette prosjektet kommer fra Apple sine nettsider. Under vil du kunne finne en knapp som tar deg til nettsiden hvor test oppgaven min finnes, og knappen ved siden av vil føre deg til mitt domene der vil du kunne finne flere av mine tidligere prosjekter.</p>
            <button class="btUn"> <a href="http://www.sktech.no/ScrollE/" >Til siden </a></button>
            <button class="btUn"><a href="http://www.sktech.no/">Til hjemmeside</a></button>   
        </div>
		<div class="Card" id="up">
			<h3 class="Heding">{Svelte}</h3>
            <p class="P">Laget den: <b>17/10/2019</b></p>
              <span class="Info">{Svelte}</span>
             <p class="Peding">Denne nettsiden du er på nå er laget i noe som heter Svelte.js, som er et JavaScript rammeverk, dette rammeverket er satt sammen på en litt annen måte en de mere kjente rammeverkene som React.js og Angular.js isteden for å kjøre alt i mellom den ‘ Virtual Dom’ lager svelte.js alt av kode i de du startet nettsiden. Jeg har nylig begynt å se litt på Svelte.js og synes det er artig å lære nye måter å gjøre ting på. Jeg legger med en linke til svelte.js sine egnene nettsider hvor de forklare litt mere om hva Svelte.js er.</p>
            <button class="btUn"> <a href="index.html" >Til siden </a></button>
            <button class="btUn"><a href="http://www.sktech.no/">Til hjemmeside</a></button>   
		</div>
		<div class="Card" id="up">
			<h3 class="Heding">{pig}</h3>
              <p class="P">Laget den: <b>18/10/2019</b></p>
             <span class="Info">Javascript</span>
             <span class="Info">Html</span>
             <span class="Info">Css</span>
             <p class="Peding">Dom Game er et prosjekt jeg har laget via en undervisning på Udemy.com som er et Bibliotek av nettbaserte kurs hvor du går i dybden på Design og koding og andre temaer du vil lære mere om. Dette er i all hovedsak ikke noe jeg har funnet opp selv og du kan finne plenty av Dom pig games der ute, men tankene min bak å lage dette var å lære litt mere om manipuleringa av Domen med hjelp av JS. </p>
             
            <button class="btUn"><a href="http://www.sktech.no/PigGame/">Til siden </a> </button>
         <button class="btUn"><a href="http://www.sktech.no/">Til hjemmeside</a></button>    
		</div>
		<div class="Card" id="up">
			<h3 class="Heding">{pwa}</h3>
             <p class="P">Laget den: <b>19/10/2019</b></p>
              <span class="Info">{pwa}</span>
              <span class="Info">React.js</span>
              <span class="Info">Css</span>
             <p class="Peding"> Dette er en huske liste som er laget i React.js og bruker teknologi som PWA for å lage en app av den, slik at du kan laste den ned via chrome nettlesere og ha den lokalt på din pc eller nettbrett. Tankene bak denne huskeliste var i hovedsak å lære nye teknologier og sette de sammen til et lite prosjekt. under vil du finne to knapper den ene vil ta deg direkte til huskelisten mens den andre vil ta deg til Domene mitt hvor du kan finne flere hobbyer oppgaver jeg har laget.</p>
             <button class="btUn"><a href="https://todo-react-v1.netlify.com/">Til siden </a></button> 
            <button class="btUn"><a href="http://www.sktech.no/">Til hjemmeside</a></button>   
		</div>
	  
	
	
</div>



<!--

// work on the side 
// add texst 



-->