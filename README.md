<html lang="en">
  <head>
    <title>Binary Demo</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles/main.css">
  </head>
  <body>
    <h1 id="display">Hello!</h1>
    <svg xmlns='http://www.w3.org/2000/svg' width='5' height='5'>
<rect width='5' height='5' fill='#fff'/>
<rect width='1' height='1' fill='#ccc'/>
</svg>
<div id="code">
</div>
<script>
function svgToBase64Image(svgElement) {
  var div = document.createElement('div');
  div.appendChild(svgElement.cloneNode(true));
  var b64 = window.btoa(div.innerHTML);
  return 'data:image/svg+xml;base64,' + b64;
}
var svgs = document.getElementsByTagName('svg');
var urls = [];
for (var i = 0; i < svgs.length; i++)
  urls.push('url("' + svgToBase64Image(svgs[i]) + '")');
var url = urls.join(',');
var msg = + url + ';';
document.body.style.background = url;
</script>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 115.471">

      <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
      	 viewBox="0 0 360 360" enable-background="new 0 0 360 360" xml:space="preserve">
      </svg>
        <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
        	 viewBox="0 0 151 265" enable-background="new 0 0 151 265" xml:space="preserve">
           <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
           	 viewBox="0 0 151 265" enable-background="new 0 0 151 265" xml:space="preserve">
             <svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
             	 viewBox="0 0 151 265" style="enable-background:new 0 0 151 265;" xml:space="preserve">
             <style type="text/css">
             	.st0{fill:#8B6DD3;}
             </style>
             <g>
             	<polygon class="st0" points="104.7,21 134.5,10.5 104.7,0 45.3,0 15.5,10.5 45.3,21 	"/>
             	<polygon class="st0" points="20.5,101.2 20.5,41.8 10,12 -0.5,41.8 -0.5,101.2 10,131 	"/>
             	<polygon class="st0" points="140,12 129.5,41.8 129.5,101.2 140,131 150.5,101.2 150.5,41.8 	"/>
             	<polygon class="st0" points="15.5,132.5 45.3,143 104.7,143 134.5,132.5 104.7,122 45.3,122 	"/>
             	<polygon class="st0" points="45.3,244 15.5,254.5 45.3,265 104.7,265 134.5,254.5 104.7,244 	"/>
             	<polygon class="st0" points="20.5,163.8 10,134 -0.5,163.8 -0.5,223.2 10,253 20.5,223.2 	"/>
             	<polygon class="st0" points="129.5,163.8 129.5,223.2 140,253 150.5,223.2 150.5,163.8 140,134 	"/>
             </g>
             </svg>
           </svg>
           <g id="shape">
        	<polygon points="104.734,21 134.467,10.5 104.734,0 45.266,0 15.533,10.5 45.266,21 	"/>
        	<polygon points="20.5,101.234 20.5,41.766 10,12.033 -0.5,41.766 -0.5,101.234 10,130.967 	"/>
        	<polygon points="140,12.033 129.5,41.766 129.5,101.234 140,130.967 150.5,101.234 150.5,41.766 	"/>
        	<polygon points="15.533,132.5 45.266,143 104.734,143 134.467,132.5 104.734,122 45.266,122 	"/>
        	<polygon points="45.266,244 15.533,254.5 45.266,265 104.734,265 134.467,254.5 104.734,244 	"/>
        	<polygon points="20.5,163.766 10,134.033 -0.5,163.766 -0.5,223.234 10,252.967 20.5,223.234 	"/>
        	<polygon points="129.5,163.766 129.5,223.234 140,252.967 150.5,223.234 150.5,163.766 140,134.033 	"/>
        </g>
        </svg>
    </svg>
    <script src="scripts/main.js"></script>
  </body>
</html>
