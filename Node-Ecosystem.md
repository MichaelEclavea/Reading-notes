# Node Ecosystem, TDD, CI/CD

1. Array.map() is a built in javascript function that goes over an array and returns a new array. The new array is determined by the code you write and specify what you want your new array to contain. 

2. Array.reduce() is the weird uncle. But to simply the weirdness, runs a function over an array. It contains a accumulator and a single ouput value. 

3.  superagent.get(url)
	.then(results =>{
	console.log(results.body);
}).catch(error){
	console.log(error);
}


4. async/await

 function demoCode (words){
	return new Promise( (resolve, reject) =>{
	if(words){
	resolve(words);
}
else {
	reject('there was an error');
}
}) 
}

async function runDemo(){
	let results = await demoCode('new word');
	console.log(results);
}
runDemo();

5.  A promise in JS is a stated code that tells JS to skip over a piece of code that will take some time to finish running. So it says skip over this code and continue on and come back to said code. This is good because we do not want js sitting and waiting for a certain code to finish when we know it will take a while to complete. So on certain scenarios, like an API call, a promise will be smart to utilize. 

6. js callback functions are synchronous. Though, if you run a callback within a async callback then it is asynchronous. stackoverflow link:
