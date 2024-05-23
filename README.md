# Random-Digits
To generate High Quality Random Numbers.


Are you tired of using and initializing `rand()` , `srand()` or `std::mt19937`  everytime ? it's a hassle to generate some Random numbers for trivial tasks.

But not anymore , this header will provide 3 functions to genearate Random Numbers 

1. `arc::randomi` to generate an Integer between a range

Just give this function a range and it will generate a Random Integer

```cpp

auto  randomInt{arc::randomi(0,100)}; // get Random number between 0-100

```


2. `arc::randomf` to generate a Float Digit between a range

   ```cpp

   auto randomFloat{arc::randomf(0.1f,99.8f);  // ger Random float between 0.1f - 99.8f

   ```

3. `arc::randomc` get a random engish char ( UPPERCASE OR LOWERCASE )

   ```cpp

   auto randomChar{arc::randomc()}; // Doesn't take anyparameter

   ```
