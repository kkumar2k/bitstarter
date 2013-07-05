var http = require('http');
var fs = require('fs');


fs.readFile('index.html', function (err, html) {
    if (err) {
        throw err; 
    }       
    http.createServer(function(request, response) { 
                response.write(html);  // <-- HERE!
        response.end();  
    }).listen(1337, '127.0.0.1');
});
