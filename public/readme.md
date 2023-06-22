
To create the custom file for creating out own css styles or color or etc ,we need to create a tailwinfconfig file 
and we can specify our required color or any other style we would like tbody
npx tailwindcss init 

it will create file tailwind.config.js

we you wwant to create a file with some other name(tailwindcss-config.js) you can do it as 
npx tailwindcss init tailwindcss-config.js

after that for compiling you have t run everytime as 
npx tailwindcss -c ./tailwindcss-config.js -i input.css -o output.css  //path can be different for you ,check that 


WE HAVE TO RUN THE BELOW COMMAND EVERYTING WE USE OUR CUSTOM CONFIG FILE -LESSON 5

npx tailwindcss -c tailwind.config.js -i ./src/styles.css -o ./dist/styles.css

