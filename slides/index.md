- title : Exploring StackOverflow 
- description : Exploring StackOverflow with F# and R.
- author : Evelina Gabasova
- theme : white
- transition : none

***

- data-background : images/copypaste-bg.jpg

<table>
<tr>
  <td class="noborder" style="width:60%;">
  </td> 
  <td class="noborder" style="width:40%;">

<div style="color: white" >
<h2> <div style="color: white" > Evelina Gabasova </div> </h2>
@evelgab <br />
evelinag.com<br />
github.com/evelinag
</div>
</td>

</tr>
</table>

------------------------------------------------------------------------------------------------

<h2> Exploring </h2> <img style="height:200px" src="images/so-logo.png" /> 

<br /> 
<h2 style="color: #e3650c"> Evelina Gabasova </h2>
@evelgab 

------------------------------------------------------------------------------------------------

<h2> Exploring </h2> <img style="height:200px" src="images/cambridge-logo.jpg" /> 

<br /> 
<h2 style="color: #e3650c"> Evelina Gabasova </h2>
@evelgab 

------------------------------------------------------------------------------------------------

- data-background : images/cambridge1.jpg

------------------------------------------------------------------------------------------------

- data-background : images/cambridge2.jpg

------------------------------------------------------------------------------------------------

- data-background : images/cancer-unit.jpg

------------------------------------------------------------------------------------------------
![](images/so-logo.png)

' Why analyze StackOverflow?
' Why not? The data are there
' Can we actually learn something from it?

------------------------------------------------------------------------------------------------

![](images/api.png)

------------------------------------------------------------------------------------------------

![](images/archive.png)

------------------------------------------------------------------------------------------------

- data-background : black

![](images/files.png)

' 135 GB approx

------------------------------------------------------------------------------------------------

<h1 style="font-size:200pt"> ? </h1>

' Questions are important - parallel from genomics

------------------------------------------------------------------------------------------------

- data-background : black

![](images/persian-cat-room-guardian.jpg)

------------------------------------------------------------------------------------------------

- data-background : images/dafuq.png

------------------------------------------------------------------------------------------------

- data-background : #f68024

# Ask questions! 

------------------------------------------------------------------------------------------------

![](images/so-structure-full.png)

------------------------------------------------------------------------------------------------

![](images/so-structure-question.png)

------------------------------------------------------------------------------------------------

![](images/so-structure-tags.png)

------------------------------------------------------------------------------------------------

# Tags

<div class="fragment">

- What are the most common tags?

</div>

' how to recognize technologies that people use for hobby projects
' technology: F#, xml parsing
' insights: think about your target demographics
' fun: minecraft, Krzysztof, most corporate technologies

------------------------------------------------------------------------------------------------

<img src="images/tag-frequency.png" style="width:1500px" />


------------------------------------------------------------------------------------------------

# Tags

- What are the most common tags?

<div class="fragment">

- When do people ask questions?

</div>

------------------------------------------------------------------------------------------------

- data-background : #f68024

# Question: When?

' demo
' tags-time-full.csv
' Show csv type provider, don't run it
' Remark on distributed computing!!! Don't do serious data science on a laptop, unless you're using it to connect to a server/cluster

------------------------------------------------------------------------------------------------


<script type="text/javascript" src="https://www.google.com/jsapi"></script>
<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Monday"}, {"v": 1386}]}, {"c" : [{"v": "Tuesday"}, {"v": 1542}]}, {"c" : [{"v": "Wednesday"}, {"v": 1471}]}, {"c" : [{"v": "Thursday"}, {"v": 1502}]}, {"c" : [{"v": "Friday"}, {"v": 1391}]}, {"c" : [{"v": "Saturday"}, {"v": 930}]}, {"c" : [{"v": "Sunday"}, {"v": 969}]}]});
    var options = {"hAxis":{"title":"Number of questions","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"title":"Tag: f#","width":1000,"height":600} 
    var chart = new google.visualization.BarChart(document.getElementById('d58646cc-a055-47d1-8d4f-d9a17025c2d1'));
    chart.draw(data, options);
}
</script>
<div id="d58646cc-a055-47d1-8d4f-d9a17025c2d1" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Monday"}, {"v": 147006}]}, {"c" : [{"v": "Tuesday"}, {"v": 162664}]}, {"c" : [{"v": "Wednesday"}, {"v": 166002}]}, {"c" : [{"v": "Thursday"}, {"v": 164108}]}, {"c" : [{"v": "Friday"}, {"v": 144248}]}, {"c" : [{"v": "Saturday"}, {"v": 67336}]}, {"c" : [{"v": "Sunday"}, {"v": 67208}]}]});
    var options = {"colors":["#f68024"],"hAxis":{"title":"Number of questions","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"title":"Tag: c#","width":1000,"height":600}  
    var chart = new google.visualization.BarChart(document.getElementById('734e0c3a-02aa-4fdb-b5ef-8d2d1f2da484'));
    chart.draw(data, options);
}
</script>
<div id="734e0c3a-02aa-4fdb-b5ef-8d2d1f2da484" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

- data-background : #f68024

# Side projects?

------------------------------------------------------------------------------------------------

- data-background : #f68024 

<img src="images/Krzysztof1.jpg" style="height: 600px; text-align:center" />


------------------------------------------------------------------------------------------------

- data-background : #f68024 

<img src="images/Krzysztof2.jpg" style="height: 500px; text-align:center" />
<img src="images/Krzysztof-tweet.png" style="height: 100px; text-align:center" />

------------------------------------------------------------------------------------------------

- data-background : #f68024

' TODO: image of the concept

------------------------------------------------------------------------------------------------

### Functional languages

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "F#"}, {"v": 0.651055951727921}]}, {"c" : [{"v": "Scala"}, {"v": 0.592436649187611}]}, {"c" : [{"v": "Clojure"}, {"v": 0.750728862973761}]}, {"c" : [{"v": "Haskell"}, {"v": 0.886785260482846}]}, {"c" : [{"v": "Erlang"}, {"v": 0.587825740998608}]}, {"c" : [{"v": "OCaml"}, {"v": 0.778732545649839}]}, {"c" : [{"v": "Elm"}, {"v": 1.0126582278481}]}]});
    var options = {"hAxis":{"title":"Weekend ratio","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"width":1000,"height":600}  
    var chart = new google.visualization.BarChart(document.getElementById('8c94b49e-d814-44db-acbd-8d057057761b'));
    chart.draw(data, options);
}
</script>
<div id="8c94b49e-d814-44db-acbd-8d057057761b" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

### Continuous integration 

<div class="fragment">

<script type="text/javascript">
    google.load("visualization", "1", {packages:["corechart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "Travis-CI"}, {"v": 0.5944625407}]}, {"c" : [{"v": "Jenkins"}, {"v": 0.2083646193}]}]});
    var options = {"hAxis":{"title":"Weekend ratio","viewWindowMode":"explicit","viewWindow":{"min":0}},"legend":{"position":"none"},"width":1000,"height":400}  
    var chart = new google.visualization.BarChart(document.getElementById('8c94b49e-d814-44db-acbd-8d057057761c'));
    chart.draw(data, options);
}
</script>
<div id="8c94b49e-d814-44db-acbd-8d057057761c" style="width: 800px; height: 400px;"></div>

</div>

------------------------------------------------------------------------------------------------

<img src="images/travis-ci.jpg" style="height: 200px"/> 
<img src="images/jenkins.png" style="height: 200px"/>  

<div class="fragment"> 
# Who's your target user? 
</div>

' Do you want people to use your product in their free time?  Make it easy for them
' But targeting enterprise is a valid goal as well

************************************************************************************************

<h1 style="font-size:200pt"> ? </h1>

------------------------------------------------------------------------------------------------

![](images/profile1.png)

------------------------------------------------------------------------------------------------

![](images/profile2.png)

------------------------------------------------------------------------------------------------

# Question: Where?

' Are there local pockets for some of the languages?
' Where is each technology used?
' technology: type providers for JSON & Bing, HTML & Wikipedia, charting
' insights: technology countries, where are programmers concentrated

------------------------------------------------------------------------------------------------

# Where?

- 5 277 833 users in total

- 769 541 filled in their location


------------------------------------------------------------------------------------------------

- data-background : black

------------------------------------------------------------------------------------------------

- data-background : black

### $HOME

------------------------------------------------------------------------------------------------

# 83%

------------------------------------------------------------------------------------------------

- data-background : black

### (Unfortunately) Germany

------------------------------------------------------------------------------------------------

- data-background : black

### 7151 Mawson Station, Australian Antarctic Territory, Antarctica

------------------------------------------------------------------------------------------------

- data-background : images/antarctica.jpg

------------------------------------------------------------------------------------------------

- data-background : #f68024

' demo: JSON type provider + Bing map API

------------------------------------------------------------------------------------------------

- data-background : images/universe.jpg

------------------------------------------------------------------------------------------------
 
# Where?

------------------------------------------------------------------------------------------------

$$$
n \times \frac{1}{\text{population}} \times \frac{\text{registered}}{\text{located}}  \times 1,000,000

<br />
<br />

<div class="fragment"> 
### ppm (Programmers-per-million) 
</div>


------------------------------------------------------------------------------------------------

- data-background : #f68024

' we need population
' demo: HTML type provider

------------------------------------------------------------------------------------------------

#### C#

<script type="text/javascript">
    google.load("visualization", "1", {packages:["geochart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "United States"}, {"v": 670.535401381481}]}, {"c" : [{"v": "Canada"}, {"v": 859.864353932267}]}, {"c" : [{"v": "United Kingdom"}, {"v": 1038.57591813224}]}, {"c" : [{"v": "Turkey"}, {"v": 126.63803754908}]}, {"c" : [{"v": "Australia"}, {"v": 1017.73391790064}]}, {"c" : [{"v": "India"}, {"v": 73.9701250381566}]}, {"c" : [{"v": "Israel"}, {"v": 982.295832472123}]}, {"c" : [{"v": "New Zealand"}, {"v": 1391.84294948194}]}, {"c" : [{"v": "South Africa"}, {"v": 154.220092911692}]}, {"c" : [{"v": "Denmark"}, {"v": 1609.72939471198}]}, {"c" : [{"v": "Germany"}, {"v": 397.418188897564}]}, {"c" : [{"v": "Netherlands"}, {"v": 1071.62590960937}]}, {"c" : [{"v": "Ireland"}, {"v": 1144.22119716098}]}, {"c" : [{"v": "Sweden"}, {"v": 1433.49401915104}]}, {"c" : [{"v": "France"}, {"v": 224.859255157669}]}, {"c" : [{"v": "Belgium"}, {"v": 790.445818580377}]}, {"c" : [{"v": "Norway"}, {"v": 1198.71643471521}]}, {"c" : [{"v": "Lebanon"}, {"v": 185.547182623178}]}, {"c" : [{"v": "Hungary"}, {"v": 299.735295052542}]}, {"c" : [{"v": "Finland"}, {"v": 514.253542601698}]}, {"c" : [{"v": "Mexico"}, {"v": 31.5268077371783}]}, {"c" : [{"v": "Croatia"}, {"v": 442.429498412436}]}, {"c" : [{"v": "Philippines"}, {"v": 43.1432188619698}]}, {"c" : [{"v": "Poland"}, {"v": 299.716308727237}]}, {"c" : [{"v": "Uganda"}, {"v": 6.02835804534653}]}, {"c" : [{"v": "Argentina"}, {"v": 90.0064778016475}]}, {"c" : [{"v": "Brazil"}, {"v": 69.7925158680194}]}, {"c" : [{"v": "Paraguay"}, {"v": 25.3266716728618}]}, {"c" : [{"v": "Luxembourg"}, {"v": 433.855812475197}]}, {"c" : [{"v": "Spain"}, {"v": 167.029004493394}]}, {"c" : [{"v": "Belarus"}, {"v": 299.692879680601}]}, {"c" : [{"v": "Thailand"}, {"v": 18.3826343681608}]}, {"c" : [{"v": "Japan"}, {"v": 17.4422752424056}]}, {"c" : [{"v": "Austria"}, {"v": 629.927878832799}]}, {"c" : [{"v": "Portugal"}, {"v": 484.144542943107}]}, {"c" : [{"v": "Italy"}, {"v": 154.52821763801}]}, {"c" : [{"v": "Russia"}, {"v": 108.005646755603}]}, {"c" : [{"v": "Iceland"}, {"v": 2368.43415798779}]}, {"c" : [{"v": "Singapore"}, {"v": 690.01929906411}]}, {"c" : [{"v": "Oman"}, {"v": 1386.7328414427}]}, {"c" : [{"v": "Kenya"}, {"v": 12.6387353628882}]}, {"c" : [{"v": "Honduras"}, {"v": 17.5174896878728}]}, {"c" : [{"v": "Costa Rica"}, {"v": 139.15529335209}]}, {"c" : [{"v": "Uruguay"}, {"v": 281.337962539118}]}, {"c" : [{"v": "Switzerland"}, {"v": 839.958789615842}]}, {"c" : [{"v": "Bangladesh"}, {"v": 20.2183029173918}]}, {"c" : [{"v": "Pakistan"}, {"v": 54.6230900081828}]}, {"c" : [{"v": "Colombia"}, {"v": 28.1540183453459}]}, {"c" : [{"v": "Estonia"}, {"v": 617.397159173701}]}, {"c" : [{"v": "Greece"}, {"v": 249.419395949819}]}, {"c" : [{"v": "Slovakia"}, {"v": 273.860872711018}]}, {"c" : [{"v": "Ukraine"}, {"v": 263.87435293967}]}, {"c" : [{"v": "Lithuania"}, {"v": 520.759002760641}]}, {"c" : [{"v": "Malaysia"}, {"v": 67.7857488427263}]}, {"c" : [{"v": "Chile"}, {"v": 69.4719519324747}]}, {"c" : [{"v": "Gabon"}, {"v": 7.70591807664795}]}, {"c" : [{"v": "China"}, {"v": 1129.51440171214}]}, {"c" : [{"v": "Czech Republic"}, {"v": 501.150229139074}]}, {"c" : [{"v": "Ethiopia"}, {"v": 2.5605654699915}]}, {"c" : [{"v": "Georgia"}, {"v": 293.039517153687}]}, {"c" : [{"v": "Trinidad and Tobago"}, {"v": 51.4504934155792}]}, {"c" : [{"v": "Slovenia"}, {"v": 710.102932696489}]}, {"c" : [{"v": "El Salvador"}, {"v": 40.4675782442083}]}, {"c" : [{"v": "Jordan"}, {"v": 125.063161815841}]}, {"c" : [{"v": "Serbia"}, {"v": 291.448595830281}]}, {"c" : [{"v": "Guatemala"}, {"v": 23.1811631817266}]}, {"c" : [{"v": "Nepal"}, {"v": 48.1152366918901}]}, {"c" : [{"v": "Armenia"}, {"v": 190.116013286081}]}, {"c" : [{"v": "Latvia"}, {"v": 475.040761433586}]}, {"c" : [{"v": "Cuba"}, {"v": 34.6000219718453}]}, {"c" : [{"v": "Peru"}, {"v": 24.2579517116924}]}, {"c" : [{"v": "Kuwait"}, {"v": 63.0730154729553}]}, {"c" : [{"v": "United Arab Emirates"}, {"v": 162.047865383996}]}, {"c" : [{"v": "Moldova"}, {"v": 121.1714855196}]}, {"c" : [{"v": "Botswana"}, {"v": 46.6902667953529}]}, {"c" : [{"v": "Iran"}, {"v": 113.851642823447}]}, {"c" : [{"v": "Venezuela"}, {"v": 23.4985947692171}]}, {"c" : [{"v": "Egypt"}, {"v": 38.5189556929233}]}, {"c" : [{"v": "Bulgaria"}, {"v": 453.312015797099}]}, {"c" : [{"v": "Cambodia"}, {"v": 20.8859325611512}]}, {"c" : [{"v": "Samoa"}, {"v": 71.2584806455903}]}, {"c" : [{"v": "Ecuador"}, {"v": 18.3914313458067}]}, {"c" : [{"v": "Macedonia"}, {"v": 298.378679520976}]}, {"c" : [{"v": "Bosnia and Herzegovina"}, {"v": 210.417897957853}]}, {"c" : [{"v": "Saint Lucia"}, {"v": 74.6677775233597}]}, {"c" : [{"v": "South Korea"}, {"v": 20.3039764536141}]}, {"c" : [{"v": "Taiwan"}, {"v": 43.4103354924824}]}, {"c" : [{"v": "Vietnam"}, {"v": 35.5070654669336}]}, {"c" : [{"v": "Madagascar"}, {"v": 1.85717864411995}]}, {"c" : [{"v": "Kyrgyzstan"}, {"v": 34.4460959836922}]}, {"c" : [{"v": "Antigua and Barbuda"}, {"v": 402.346793538006}]}, {"c" : [{"v": "Mali"}, {"v": 4.16472037546464}]}, {"c" : [{"v": "Albania"}, {"v": 79.4017133661273}]}, {"c" : [{"v": "Qatar"}, {"v": 89.634985788565}]}, {"c" : [{"v": "Algeria"}, {"v": 13.5788158778248}]}, {"c" : [{"v": "Palestine"}, {"v": 53.3440594676014}]}, {"c" : [{"v": "Malta"}, {"v": 2368.43415798779}]}, {"c" : [{"v": "Afghanistan"}, {"v": 9.54096765112788}]}, {"c" : [{"v": "Saudi Arabia"}, {"v": 27.9859731008199}]}, {"c" : [{"v": "Panama"}, {"v": 47.3295439428301}]}, {"c" : [{"v": "Indonesia"}, {"v": 10.2330395190525}]}, {"c" : [{"v": "Tunisia"}, {"v": 85.911053641146}]}, {"c" : [{"v": "Niger"}, {"v": 45.5900579346104}]}, {"c" : [{"v": "Dominica"}, {"v": 2368.43415798779}]}, {"c" : [{"v": "Ghana"}, {"v": 6.02303691448196}]}, {"c" : [{"v": "Fiji"}, {"v": 72.0841174014441}]}, {"c" : [{"v": "Sri Lanka"}, {"v": 196.737449487047}]}, {"c" : [{"v": "Solomon Islands"}, {"v": 21.6327205908799}]}, {"c" : [{"v": "Abkhazia"}, {"v": 144.245098973275}]}, {"c" : [{"v": "Zambia"}, {"v": 4.35807349010436}]}, {"c" : [{"v": "Cyprus"}, {"v": 475.511206565528}]}, {"c" : [{"v": "Swaziland"}, {"v": 18.3924258879938}]}, {"c" : [{"v": "Kazakhstan"}, {"v": 21.1219148504108}]}, {"c" : [{"v": "Romania"}, {"v": 20.0310672394398}]}, {"c" : [{"v": "Myanmar"}, {"v": 6.25900696865481}]}, {"c" : [{"v": "Nicaragua"}, {"v": 21.0672552863798}]}, {"c" : [{"v": "Mongolia"}, {"v": 35.7848358457431}]}, {"c" : [{"v": "The Bahamas"}, {"v": 73.4747995944604}]}, {"c" : [{"v": "Guinea"}, {"v": 2.14539377760793}]}, {"c" : [{"v": "Morocco"}, {"v": 19.9676691063666}]}, {"c" : [{"v": "Bahrain"}, {"v": 98.8554816666304}]}, {"c" : [{"v": "Syria"}, {"v": 32.1694077047959}]}, {"c" : [{"v": "Bolivia"}, {"v": 25.2856295434461}]}, {"c" : [{"v": "Montenegro"}, {"v": 145.178339083871}]}, {"c" : [{"v": "Senegal"}, {"v": 1.40760191897891}]}, {"c" : [{"v": "Rwanda"}, {"v": 1.80316549241797}]}, {"c" : [{"v": "Mauritius"}, {"v": 131.967100119757}]}, {"c" : [{"v": "Jamaica"}, {"v": 61.1984666211348}]}, {"c" : [{"v": "Azerbaijan"}, {"v": 45.5561080230677}]}, {"c" : [{"v": "Chad"}, {"v": 1.91601112221079}]}, {"c" : [{"v": "Zimbabwe"}, {"v": 9.26519707378288}]}, {"c" : [{"v": "Libya"}, {"v": 13.0507814747172}]}, {"c" : [{"v": "Uzbekistan"}, {"v": 6.81758217973688}]}, {"c" : [{"v": "Yemen"}, {"v": 4.54887035352297}]}, {"c" : [{"v": "Maldives"}, {"v": 161.479978017108}]}, {"c" : [{"v": "Kosovo"}, {"v": 83.1639098632613}]}, {"c" : [{"v": "Central African Republic"}, {"v": 15.2831405374944}]}, {"c" : [{"v": "Brunei"}, {"v": 67.4348464158529}]}, {"c" : [{"v": "South Sudan"}, {"v": 2.28970515527902}]}, {"c" : [{"v": "Andorra"}, {"v": 2368.43415798779}]}, {"c" : [{"v": "Seychelles"}, {"v": 298.209366558123}]}, {"c" : [{"v": "Marshall Islands"}, {"v": 2368.43415798779}]}, {"c" : [{"v": "Benin"}, {"v": 1.95541453937}]}, {"c" : [{"v": "Bhutan"}, {"v": 35.7009539975191}]}, {"c" : [{"v": "Iraq"}, {"v": 7.14875134770857}]}, {"c" : [{"v": "Guyana"}, {"v": 27.8916989275905}]}, {"c" : [{"v": "Angola"}, {"v": 1.99352512474448}]}, {"c" : [{"v": "Burkina Faso"}, {"v": 1.09445599611153}]}, {"c" : [{"v": "Tanzania"}, {"v": 2.51803220367055}]}, {"c" : [{"v": "Nigeria"}, {"v": 0.297093003173357}]}, {"c" : [{"v": "Cameroon"}, {"v": 2.44619509759798}]}, {"c" : [{"v": "Tajikistan"}, {"v": 7.30872760929155}]}, {"c" : [{"v": "Tuvalu"}, {"v": 652.64128850305}]}, {"c" : [{"v": "Liechtenstein"}, {"v": 1107.42417824296}]}, {"c" : [{"v": "North Korea"}, {"v": 4.01500841205651}]}, {"c" : [{"v": "Namibia"}, {"v": 8.96249246210932}]}, {"c" : [{"v": "Malawi"}, {"v": 1.65012545297811}]}, {"c" : [{"v": "Suriname"}, {"v": 76.9233692208352}]}, {"c" : [{"v": "Barbados"}, {"v": 24.3652747707805}]}, {"c" : [{"v": "Micronesia"}, {"v": 135.099286180398}]}, {"c" : [{"v": "Ivory Coast"}, {"v": 2.14406128902212}]}, {"c" : [{"v": "San Marino"}, {"v": 420.790989830174}]}, {"c" : [{"v": "Mozambique"}, {"v": 2.62798295078753}]}, {"c" : [{"v": "Turkmenistan"}, {"v": 7.30785931493254}]}, {"c" : [{"v": "São Tomé and Príncipe"}, {"v": 37.0636825597923}]}, {"c" : [{"v": "Dominican Republic"}, {"v": 2.75695177924166}]}, {"c" : [{"v": "Monaco"}, {"v": 361.672047378774}]}, {"c" : [{"v": "Lesotho"}, {"v": 10.8728131153535}]}, {"c" : [{"v": "Cape Verde"}, {"v": 39.2145718386966}]}, {"c" : [{"v": "The Bahamas"}, {"v": 18.3686998986151}]}, {"c" : [{"v": "Haiti"}, {"v": 1.25367081135657}]}, {"c" : [{"v": "Mauritania"}, {"v": 3.73471610592391}]}, {"c" : [{"v": "Laos"}, {"v": 2.13914833025459}]}, {"c" : [{"v": "Sudan"}, {"v": 0.843222181570873}]}, {"c" : [{"v": "Papua New Guinea"}, {"v": 1.71805072174189}]}, {"c" : [{"v": "South Korea"}, {"v": 0.274378060183974}]}, {"c" : [{"v": "Grenada"}, {"v": 67.204468388747}]}, {"c" : [{"v": "Sierra Leone"}, {"v": 1.96281956918743}]}, {"c" : [{"v": "Belize"}, {"v": 36.9456613684293}]}, {"c" : [{"v": "North Korea"}, {"v": 0.286786315146893}]}]});
    var options = {"legend":{"position":"none"},"width":1000,"height":600}  
    var chart = new google.visualization.GeoChart(document.getElementById('f262b395-fe04-45c7-a5d2-608efd5ff25a'));
    chart.draw(data, options);
}
</script>
<div id="f262b395-fe04-45c7-a5d2-608efd5ff25a" style="width: 800px; height: 600px;"></div>

------------------------------------------------------------------------------------------------

#### F#

<script type="text/javascript">
    google.load("visualization", "1", {packages:["geochart"]})
    google.setOnLoadCallback(drawChart);
function drawChart() {
    var data = new google.visualization.DataTable({"cols": [{"type": "string" ,"id": "Column 1" ,"label": "Column 1" }, {"type": "number" ,"id": "Column 2" ,"label": "Column 2" }], "rows" : [{"c" : [{"v": "United States"}, {"v": 21.1441649612187}]}, {"c" : [{"v": "Australia"}, {"v": 33.5895256401621}]}, {"c" : [{"v": "Norway"}, {"v": 50.3885226982056}]}, {"c" : [{"v": "United Kingdom"}, {"v": 41.0609702691429}]}, {"c" : [{"v": "Poland"}, {"v": 9.21370207660584}]}, {"c" : [{"v": "New Zealand"}, {"v": 38.2940917317782}]}, {"c" : [{"v": "Netherlands"}, {"v": 27.2895993705161}]}, {"c" : [{"v": "Russia"}, {"v": 3.50390962731898}]}, {"c" : [{"v": "Canada"}, {"v": 21.2922413531757}]}, {"c" : [{"v": "India"}, {"v": 0.313034807609634}]}, {"c" : [{"v": "Brazil"}, {"v": 0.974474222519289}]}, {"c" : [{"v": "Sweden"}, {"v": 53.8960153684717}]}, {"c" : [{"v": "Switzerland"}, {"v": 25.8064642993965}]}, {"c" : [{"v": "Ireland"}, {"v": 36.4866453176332}]}, {"c" : [{"v": "Germany"}, {"v": 11.069909152792}]}, {"c" : [{"v": "Israel"}, {"v": 24.2741968485698}]}, {"c" : [{"v": "Denmark"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Belgium"}, {"v": 10.4248090891128}]}, {"c" : [{"v": "France"}, {"v": 6.34725338483007}]}, {"c" : [{"v": "Spain"}, {"v": 2.8411379457247}]}, {"c" : [{"v": "Turkey"}, {"v": 0.617316339027548}]}, {"c" : [{"v": "Guatemala"}, {"v": 0.429280799661604}]}, {"c" : [{"v": "Austria"}, {"v": 16.6815705617765}]}, {"c" : [{"v": "Italy"}, {"v": 4.92200989513662}]}, {"c" : [{"v": "South Africa"}, {"v": 2.49547075908887}]}, {"c" : [{"v": "Colombia"}, {"v": 0.568768047380725}]}, {"c" : [{"v": "China"}, {"v": 20.7944073955373}]}, {"c" : [{"v": "Japan"}, {"v": 0.710813724612141}]}, {"c" : [{"v": "Czech Republic"}, {"v": 21.7033563800386}]}, {"c" : [{"v": "Finland"}, {"v": 13.8987443946405}]}, {"c" : [{"v": "Saint Lucia"}, {"v": 37.3338887616799}]}, {"c" : [{"v": "South Korea"}, {"v": 0.137189030091987}]}, {"c" : [{"v": "Mexico"}, {"v": 0.323905558943612}]}, {"c" : [{"v": "Macedonia"}, {"v": 3.35256943281996}]}, {"c" : [{"v": "Oman"}, {"v": 18.5309511105928}]}, {"c" : [{"v": "Greece"}, {"v": 5.75583221422658}]}, {"c" : [{"v": "Madagascar"}, {"v": 0.309529774019991}]}, {"c" : [{"v": "Ukraine"}, {"v": 6.18582690419955}]}, {"c" : [{"v": "Malaysia"}, {"v": 0.437327411888557}]}, {"c" : [{"v": "Uruguay"}, {"v": 1.995304698859}]}, {"c" : [{"v": "Georgia"}, {"v": 3.7329874796648}]}, {"c" : [{"v": "Philippines"}, {"v": 0.202233838415483}]}, {"c" : [{"v": "Indonesia"}, {"v": 0.133242702070996}]}, {"c" : [{"v": "Trinidad and Tobago"}, {"v": 5.14504934155792}]}, {"c" : [{"v": "Egypt"}, {"v": 0.227474147792854}]}, {"c" : [{"v": "Portugal"}, {"v": 3.35745175411309}]}, {"c" : [{"v": "Argentina"}, {"v": 1.11512450373723}]}, {"c" : [{"v": "Bulgaria"}, {"v": 5.82413724792847}]}, {"c" : [{"v": "Bosnia and Herzegovina"}, {"v": 1.96652241082105}]}, {"c" : [{"v": "Singapore"}, {"v": 17.564127612541}]}, {"c" : [{"v": "Malta"}, {"v": 16.1737518392535}]}, {"c" : [{"v": "Iran"}, {"v": 0.611166794297645}]}, {"c" : [{"v": "Slovakia"}, {"v": 2.55944740851418}]}, {"c" : [{"v": "Sri Lanka"}, {"v": 0.662415654838544}]}, {"c" : [{"v": "Lithuania"}, {"v": 14.5328093793667}]}, {"c" : [{"v": "Estonia"}, {"v": 42.2151903708514}]}, {"c" : [{"v": "Paraguay"}, {"v": 1.01306686691447}]}, {"c" : [{"v": "Hungary"}, {"v": 5.65538292551966}]}, {"c" : [{"v": "Peru"}, {"v": 1.10263416871329}]}, {"c" : [{"v": "Moldova"}, {"v": 1.95437879870323}]}, {"c" : [{"v": "Botswana"}, {"v": 3.11268445302353}]}, {"c" : [{"v": "Dominica"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Slovenia"}, {"v": 26.9233339410991}]}, {"c" : [{"v": "Pakistan"}, {"v": 0.178740477775467}]}, {"c" : [{"v": "Kazakhstan"}, {"v": 0.391146571303903}]}, {"c" : [{"v": "El Salvador"}, {"v": 3.19480880875329}]}, {"c" : [{"v": "Jamaica"}, {"v": 2.54993610921395}]}, {"c" : [{"v": "Ecuador"}, {"v": 0.417987076041062}]}, {"c" : [{"v": "Belarus"}, {"v": 6.57862418811075}]}, {"c" : [{"v": "Serbia"}, {"v": 3.92523361387584}]}, {"c" : [{"v": "Croatia"}, {"v": 4.97111795969029}]}, {"c" : [{"v": "Uganda"}, {"v": 0.188386188917079}]}, {"c" : [{"v": "Chile"}, {"v": 0.763428043214008}]}, {"c" : [{"v": "Cuba"}, {"v": 2.47143014084609}]}, {"c" : [{"v": "Bhutan"}, {"v": 8.92523849937978}]}, {"c" : [{"v": "Cyprus"}, {"v": 8.198469078716}]}, {"c" : [{"v": "United Arab Emirates"}, {"v": 1.40911187290431}]}, {"c" : [{"v": "Vietnam"}, {"v": 0.224728262448947}]}, {"c" : [{"v": "Mauritius"}, {"v": 5.49862917165655}]}, {"c" : [{"v": "Saudi Arabia"}, {"v": 0.223887784806559}]}, {"c" : [{"v": "Thailand"}, {"v": 0.211294647909894}]}, {"c" : [{"v": "Latvia"}, {"v": 3.54508030920587}]}, {"c" : [{"v": "Bangladesh"}, {"v": 0.0431093878835645}]}, {"c" : [{"v": "Niger"}, {"v": 0.335221014225076}]}, {"c" : [{"v": "San Marino"}, {"v": 81.9457102597392}]}, {"c" : [{"v": "Palestine"}, {"v": 1.4417313369622}]}, {"c" : [{"v": "Tunisia"}, {"v": 0.622543866964826}]}, {"c" : [{"v": "Kyrgyzstan"}, {"v": 1.14820319945641}]}, {"c" : [{"v": "Azerbaijan"}, {"v": 0.711814187860433}]}, {"c" : [{"v": "Venezuela"}, {"v": 0.223796140659211}]}, {"c" : [{"v": "South Korea"}, {"v": 0.137189030091987}]}, {"c" : [{"v": "Marshall Islands"}, {"v": 81.9457102597392}]}]});
    var options = {"legend":{"position":"none"},"width":1000,"height":600} 
    var chart = new google.visualization.GeoChart(document.getElementById('2f1227d9-f924-4eed-ad93-6fe640abde4c'));
    chart.draw(data, options);
}
</script>
<div id="2f1227d9-f924-4eed-ad93-6fe640abde4c" style="width: 800px; height: 600px;"></div>


------------------------------------------------------------------------------------------------

- data-background : images/dominican-republic.jpg

------------------------------------------------------------------------------------------------

- data-background : black

## (Sampling bias)

' only registered users
' only active users
' and out of them, only the ones that gave out their address

************************************************************************************************

# Tags + Users

<div class="fragment">

# = 
# Communities

</div>

' Users ask questions with specific tags & answer questions with specific tags
' No-one knows everything

' how to define relation between tags through posts & users, similar users - similar tags
' memory vs. distributed computing
' t-SNE visualization - how to create a meaningful visualization
' Networks
' technology: RProvider, Fable

------------------------------------------------------------------------------------------------

# Tags 

### define 

# relations



------------------------------------------------------------------------------------------------

|           | F# | C# | JS | R | Cobol |
|-----------|----|----|------------|---|---|
| Evelina   | 1  | 0  | 1          | 1 | 0 |
| Krzysztof | 1  | 1  | 1          | 0 | 0 |

------------------------------------------------------------------------------------------------

### 44 265 tags x  5 277 831 users

------------------------------------------------------------------------------------------------

#### Users with more than 1,000 posts
#### Tags with more than 5,000 posts

<div class="fragment">
## 807 tags, 1633 power users
</div>

------------------------------------------------------------------------------------------------

# t-SNE
## t-distributed Stochastic Neighbourhood embedding

' image
' run t-sne on my desktop at work

------------------------------------------------------------------------------------------------


- data-background: images/part1-once.gif

------------------------------------------------------------------------------------------------

- data-background: images/part1-1.png

------------------------------------------------------------------------------------------------

- data-background: images/part1-2.png

------------------------------------------------------------------------------------------------

- data-background: images/part1-3.png

------------------------------------------------------------------------------------------------

- data-background: images/part1-4.png

------------------------------------------------------------------------------------------------

- data-background: images/part2-once.gif

------------------------------------------------------------------------------------------------

- data-background: images/part2-1.png

------------------------------------------------------------------------------------------------

- data-background: images/part2-2.png

------------------------------------------------------------------------------------------------

- data-background: images/part2-3.png

------------------------------------------------------------------------------------------------

- data-background: images/part2-4.png

------------------------------------------------------------------------------------------------

# t-SNE in R

    [lang=R]
    library(tsne)

    ts <- tsne(m, perplexity=20)

    plot(ts)

------------------------------------------------------------------------------------------------

# t-SNE in F#

    open RProvider
    open RProvider.tsne(tsne)

    let ts = R.tsne(namedParams[ "X", box m; "perplexity", box 20])

    R.plot(ts)

------------------------------------------------------------------------------------------------

- data-background : images/rplot.png

------------------------------------------------------------------------------------------------

*The best thing about R is that it was written by statisticians. The worst thing about R is that it was written by statisticians.*

<br />

Bow Cowgill, 2009

------------------------------------------------------------------------------------------------

- data-background : images/tsne-full.png

------------------------------------------------------------------------------------------------

<img src="images/tsne-terminal.png" style="width: 600px" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-general.png" style="width: 960px" />

------------------------------------------------------------------------------------------------

<img src="images/tsne-datascience.png" style="width: 600px" />

------------------------------------------------------------------------------------------------

![](images/fable.png)

------------------------------------------------------------------------------------------------

[![](images/tsne-sample.png)](images/tsne-2.html)

' that's why it's good to have a proper language at hand as well!
' TODO visualization with D3

------------------------------------------------------------------------------------------------

# Quantifying Communities

' image showing how we can define a network using user data

------------------------------------------------------------------------------------------------

![Network](images/network-basic.png)

------------------------------------------------------------------------------------------------

![](images/network-tags.png)

------------------------------------------------------------------------------------------------

![](images/network-links.png)

------------------------------------------------------------------------------------------------

# No overlap

### iOS  - R
### Django - middleware

' So that when someone comes and says: I want someone to write a statistics app for iphone - now you know that one person knowing both is very rare to find
' Or they are avoidint StackOverflow

------------------------------------------------------------------------------------------------

# Most Central
### Based on number of connections

1. arrays 
2. string 
3. performance

------------------------------------------------------------------------------------------------

# Communities
### Clustering of nodes in a network

' idea of algorithms

------------------------------------------------------------------------------------------------

![](images/clusters1.png)

(depending on algorithm used)

------------------------------------------------------------------------------------------------

![](images/clusters2.png)

(depending on algorithm used)

------------------------------------------------------------------------------------------------

![](images/clusters3.png)

(depending on algorithm used)

************************************************************************************************

## ✔ Tags 
## ✔ Users
## ✔ Technologies

<br />

<div class="fragment">
# Questions and Answers
</div>

------------------------------------------------------------------------------------------------

## Is
![](images/so-logo.png)
## a meritocracy?

' now a provocative question
' How would we recognize meritocracy? Well, if you come and give a good answer, then you get higher score and reputation for your answer
' So I'll look at how good is author's reputation and other author properties related to the score of the question he answered

------------------------------------------------------------------------------------------------

![](images/reputation-score.png)

------------------------------------------------------------------------------------------------

![](images/reputation-score-log.png)

------------------------------------------------------------------------------------------------

# Machine learning

<table>
<tr>
<td class="noborder" style="width:50%;">

## Unsupervised

- Clustering
- Anomaly detection
- ...

*Data exploration*

</td>
<td class="noborder" style="width:50%;">

## Supervised

- Classification
- Regression
- ...

*Prediction*

</td>
</tr>
</table>

------------------------------------------------------------------------------------------------

# Regression 

### input data
# ⬇
### score

------------------------------------------------------------------------------------------------

# Input data 

18,100,293 rows

<div style="font-size:20pt" />
"Accepted" 
"Question Score" 
"Number of tags" 
"Answer Count"           
"Comment Count"           
"Question Favorite Count"
"Question View Count"     
"Author Reputation"      
"Author Profile Views"    
"Author Up Votes"        
"Author Down Votes"       
"Gold Badges"            
"Silver Badges"           
"Bronze Badges"          
"Author Number of Tags"   
"Time to Answer"        
</div>

# ⬇ 

"Score"  

------------------------------------------------------------------------------------------------

## Linear and non-linear Regression

![](images/lr.png)

------------------------------------------------------------------------------------------------

## Power-law distributions

<img src="images/power-law.png" style="height:400px" />

------------------------------------------------------------------------------------------------

# Most predictive

- Accepted
- Favourites

' TODO: Regenerate data with correct time to answer

------------------------------------------------------------------------------------------------

 - data-background : images/chucknorrisapproves.gif

------------------------------------------------------------------------------------------------


![](images/leverage.png)

------------------------------------------------------------------------------------------------

![](images/lever.png)

------------------------------------------------------------------------------------------------

<img src="images/leverage-illustration.png" style="width: 600px" />


' The 'Jon Skeet' effect
' The reputation is not really important, unless you are Jon Skeet

------------------------------------------------------------------------------------------------

![](images/jonskeet.png)

------------------------------------------------------------------------------------------------

- data-background : #f68024

## Quality of answer matters!

<div class="fragment">
### ... unless you are Jon Skeet
</div>

************************************************************************************************

' Summary

# Technological side of things


' Data science is about a lot of things - from preprocessing the data, through mathematical models, to visualization
' No single tool - but type providers are a great thing that basically make external data sources a part of your IDE

### Tool for the job

------------------------------------------------------------------------------------------------

' Summary

# Data science side of things
### Questions

------------------------------------------------------------------------------------------------

- Hobby projects vs. enterprise
- Communities
- Help others

<div class="fragment">
- Move to the Dominican republic
</div>

' think about your demographics - who are you targetting with your product
' if you're doing .NET - there's a world out there! And if you're doing JavaScript - it's not the only thing in the world!
' help people on StackOverflow - what matters is that answers are helpful, not who they come from (unless...)
' and if you want to do digital nomad thing - you can gather data where you can find likely minded people
' Sampling bias!!!

------------------------------------------------------------------------------------------------

- data-background : images/beach.jpg

<table>
<tr>
  <td class="noborder" style="width:60%;"></td>
   <td class="noborder" style="width:4%;">

<h2> <div style="color: white" > Evelina Gabasova </div> </h2>
<div style="color: white" >
@evelgab <br />
evelinag.com<br />
</div>
<br /><br /><br/><br/><br/><br/>
</td> 
</tr>
</table>