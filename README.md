var APP_ID     = "5e68d66090ef80faff2619b6"; 
var APP_KEY    = "uTedyjueyNuMazamuduLaJeravebyPe9uaaQ"; 
var API_HOST   = "https://api.enablex.io"; 
var API_PATH   = "/v1/rooms/"; 

var options = { 
      host: 'https://api.enablex.io', 
      path: API_PATH, 
      method: 'GET', 
      headers: { 
         'Content-Type': 'application/json', 
         'Authorization': 'Basic '+ btoa(APP_ID+':'+APP_KEY) 
     } 
 }
 var request = https.request(options, function(response) { 
     // Handle response
 });
