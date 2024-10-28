# Random-Digits
To generate High Quality Random Numbers.


Are you tired of using and initializing `rand()` , `srand()` or `std::mt19937`  everytime ? it's a hassle to generate some Random numbers for trivial tasks.

But not anymore , this header will provide 3 functions to genearate Random Numbers 

1. `xe:::randomi` to generate an Integer between a range
   Just give this function a range and it will generate a Random Integer
   ```cpp

   auto  randomInt{xe::randomi(0,100)}; // get Random number between 0-100

    ```


2. `xe::randomf` to generate a Float Digit between a range

   ```cpp

   auto randomFloat{xe::randomf(0.1f,99.8f);  // ger Random float between 0.1f - 99.8f

   ```

3. `xe::randomc` get a random engish char ( UPPERCASE OR LOWERCASE )

   ```cpp

   auto randomChar=(char)xe::randomi(65,90); // generate random UPPER chars
   auto rand_char=(char)xe::randomi(97,122); // generate random lower chars

   ```
