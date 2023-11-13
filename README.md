# Unit2.Testing

## Unit Test:
1. 
   ### Expectation
   - We should have a function called "Multiplication".
   - User should get a prompt to input the two numbers that will be multiplied.
   - Once numbers are inputted the sum of the numbers should show up on the console.
   ### pseudocode
   - two numbers need to be provided num1 num2
   - a function call it 
   - function returns a single number which is the sum of the two numbers provided(num1 and num2)
   -  function multplication(num1, num2) {
         return num1 * num2;
   
   }
   - prompt('What two numbers would you like to multiply?')
2. 
  ### Expectation 
  - function called "concatOdds" 
  - arguments are two arrays
  - create a for loop iterating through the two arrays 
  - use .concat
  - if statement != %2
  - if some odd numbers are repeated multiply then 
  - if user inputs a character indicate to the user that an error has ocurred
  - if all numbers are even indicate there are no odd numbers

  ### Pseudocode
  - function concatOdds(){
  - const arr = []
  - const arr1 = []
  - let  arrboth = arr.concat(arr1)
   for (let i = 0; i < arrboth.length;i++){
    if (i %2 !==0)
   }
  }
  - prompt('Below please provide your first array of numbers.')
  - if numbers are inputed prompt('Thank you. Next input the next set of numbers')
  - if characters or inputted ('Please only input numbers not characters or symbols')
## Functional Tests:
- Once "checkout" is clicked; user is prompt to login inputing email and 'continue' button
- next to 'continue' button have a register button 
- on the same page if you already have an account have an input section so user can put in email and password
- no account users can click on register button and it will redirect them to a form or checkout as guest button
- checkout section, will have form askin user to provide the necessary details for shipping; 
  - firstname 
  - lastname
  - phone number
  - shipping address
  - option is shipping address the same as billing address if not;
  - billing address 
  - submit button 
  - if user didnt fill something in they will be reverted back prompt stating what as not filled in  
  - if address is non existent prompt please review your address
  - if number does not have correct amount of numbers prompt please provide a correct phone number







