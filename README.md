# Snippets
Helpful code snippets I'd like to remember

## Languages
### C snippets

##### Return string from a function
```c
char * stringReturn() {
    char * string = calloc(6, sizeof(char));
    string = "hello";
    
    return string;
}
```

##### Enumerations done right
```c
enum Car {
    Acura,
    Ford,
    Honda,
    Jaguar,
    Zonda
};
```
