<html>
<head>

<script>
function clk(){
    var x = document.getElementById ("bog2");
    var y = document.getElementById ("bog3");
    if ( x.value == "samhar" || x.value == "samhaar" || x.value == "samhar " || x.value =="samhaar " || x.value  == "Samhar" || x.value =="Samhaar") 
{

let div = document.getElementById ("bog1") ;
let e =  document.createElement("e");
let t = document.createTextNode("cabdiwali waa qofka kujecel , cabdiwali iyo samhaar waa laba qof laisoogu tala galay  waxad tahy noolashiisa ");
e.appendChild(t);

div.appendChild(t);

} 
else 
alert (x.value  + ": sorry cid kujecel ma jirto nasiib wanagsan kuu rajaynayaa");
}
    


</script>

<style>
    
    
    #bog1{
    
    color:red;
    font-size:30px;
    font-weight:bold;
}
    
    
</style>

</head>

<body>

<div id ="bog0"> <p>ma rabtaa inaad ogaato qofka aduunka kuugu jecel, 
<br> ma rabtaa inaad ogaato waxa niyada qofka kujecel kujira </p>

<input type ="name" id ="bog2" placeholder ="gali magacaaga"/>

<input type ="button" id ="click" onclick ="clk()" value ="riix "/>


</div>
<div id = "bog1"></div>
</body>
</html>
