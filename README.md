## In this repository i will present small part of funcionalities
## of new pyodide package which allows us to run python code directly in html code.

I want to check out how powerfull is pyodide and i will show how to use it directly in our html code:
1. Install pyodide with command "pip install pyodide"
2. Create html code which allows us to use scripts like js, but in this case we have to use <py-script> tags 
3. Write some python code, in my examle i use matplotlib module and i create simple charts.

Instead of easy using python in browsers we have to thing about effective.
Python code is tlanslating into js code so more effective way is write the same code in js.

## Three examples of using Py-script
1. Creating simple chart using python.
2. Create random number using Madelon method(implemented in make_classification function in sklearn module) and plot it using matplotlib module.
3. Simple guessing game. You have to guess the number and your guesses are counted.
