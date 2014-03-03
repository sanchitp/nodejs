var express = require('express');
var routes = require('./routes');
var user = require('./routes/user');
var http = require('http');
var path = require('path');

var app = express();
var Question=require('./schema');




function linear(callback){



callback(c);
}
// all environments
app.set('port', process.env.PORT || 3000);
app.set('views', path.join(__dirname, 'views'));
app.set('view engine', 'ejs');
app.use(express.favicon());
app.use(express.logger('dev'));
app.use(express.json());
app.use(express.urlencoded());
app.use(express.methodOverride());
app.use(app.router);
app.use(express.static(path.join(__dirname, 'public')));
var c=' ';
var k=1;
// development only
if ('development' == app.get('env')) {
  app.use(express.errorHandler());
}


app.get('/',function(req,res){

	var Qid;
var data;



for(i=0;i<3;i++){
Qid=i+1;
	Question.getQuestion(Qid, function (err, question_data){
		k++;

		if( !err ){
						

						c=c+question_data.toString();				
						if(k==4)
						{
							res.render('ques',{title: 'printf()',question:c});
						}

					}	
		else{
				console.log('inside /retrive while getQuestion');
			}
			

	});
	
}
});



http.createServer(app).listen(app.get('port'), function(){
  console.log('Express server listening on port ' + app.get('port'));
});
