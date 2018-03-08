A simple example demonstrating how to create and configure a Web REST API connected to a Lambda function with Node.js and Claudia.js. To try it out, first [set up the credentials](https://claudiajs.com/tutorials/hello-world-lambda.html), then:

1. run `npm install` to grab the dependencies
2. run `npm start` to set up the lambda project under the default name on AWS 
3. Check out the API ID in `claudia.json` (the previous step creates the file)
4. Open https://API_ID.execute-api.us-east-1.amazonaws.com/latest/greet?name=Praveen in a browser (replace API_ID with the API ID from `claudia.json`)

super :
	Get superb like words
	https://www.npmjs.com/package/superb
	
	The word list itself is just a JSON file and can be used wherever.
	https://github.com/sindresorhus/superb/blob/HEAD/words.json