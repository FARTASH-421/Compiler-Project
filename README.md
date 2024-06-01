# LLVM Compiler Project 2024
Hi! This is MAS-Lang! A useless but tricky language and we have designed a compiler for it in C++!

This language supports:

## Defining integer or boolean variables    
```
// Examples:
int x;
bool y;

bool t = ture, f = false, d;
int a = 0, b = -1, c;
```

## Assigning integer variables    
```
// Examples:

a = 0;
a += 1;
a -= 2;
a *= 3;
b /= 4;
c %= 5;
```
## Unary operators
```
// Examples:
       x--
       x++    
```

## Comment
```
1. single line comment
        // Comment.......

2. multi line comment

      /* Comment1
         Comment2
         Comment3
          ....
      */

```

## If, Else if and Else   
```
// Examples:

if ( a > 3 and b == 10 or false) {
   a = 5;
} else if ( a==3 and true) {
   c *= 10;
}
else {
   c += 1;
}

if ( true and 2>1 ) {
   if ( a > 3 and b >= 10 or false) {
         a = 5;
   }
   else {
    c *= 1;
   }
}

```

## Loop   
```
// Examples:

while ( a > 3 and b <= 10 or false) {
   a = 5;
   a = 5;
   b = (a * 4) + 5 * (7 - 2) / 1;
   if ((a > 10) and b == 20 ){
      b *= 10;
    }
}

for ( i = 0; i < 10; i += 2) {
   .....
}

for ( i = 0; i < 10; i--) {
   .....
}
```
## Print
```
// Examples:

    print (name_variable);

```




You can find the details in this [document](https://docs.google.com/document/d/14S2qoImBrv2BumIKwbEJSnKZ7ZLcFPj7b25a0BNU_Cs/edit?usp=sharing).
# How to run?
Write your input in input.txt.
```
sudo chmod +x build.sh
./build.sh
sudo chmod +x run.sh
./run.sh
```
