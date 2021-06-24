## Node Ecosystem, TDD, CI/CD
-  Describe (in plain English) what Array.map() does
    - It returns a new array by calling a function on each element of the passed array.
- Describe (in plain English) what Array.reduce() does
    - Mainly, it can return a single value by calling a function on each element of the passed array, the return value of the function is stored in an accumulator. It also can return anything. 
- Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
    - With normal Promise .then() syntax
    > function getCharacters(){                    
superagent.get('https://swapi.dev/api/people/')                        
  .then( data => {                        
    data.body.results.map(result=>{                             
    console.log({key:result.name , value:result.url});                                
    })
  })                              
  .catch(err => console.error(err));                            
}                                


    - Again with async / await syntax
    > async function getCityLocation(cityName) {                                          
  let results = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);                      
  console.log(`Longitude: ${results.body.longt} & Latitude:${results.body.latt}`);                                   
};                    

- Explain promises as though you were mentoring a Code 301 level student
    - Promise is an object supports two properties: state and result, it uses callbacks and has three states: pendeing, fulfilled and rejected. We use it to handle asynchronous operations in JavaScript.
- Are all callback functions considered to be Asynchronous? Why or Why Not?
    - Not really, by the definitions of the two concepts; a callback function is a function that is passed as an argument to another function, and asynchronous means that each function is independent and has no relation with the others, so callBacks can be synchronous or asynchronous and they don't have anything to do with the async concept at all, 


