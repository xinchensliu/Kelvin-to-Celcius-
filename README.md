# Kelvin-to-Celcius-
//This is the constant temperature of today 
const kelvin = 293
//This is the temp in celcius
let celcius = 293 - 273
//temp in fahrenheit 
let fahrenheit = celcius * (9/5) + 32
//make not a decimal 
fahrenheit = Math.floor(fahrenheit)
console.log('The temperature is ' + fahrenheit + ' degrees Fahrenheit')
