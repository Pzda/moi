# moi

## the values
existence adds line to the code, the processing time it was created, and the memory resources in the stack.\
variables contains unique [pures](#the-pure) from being assigned.\
dictionaries has a key symbol to specify the location of the value, and an another value. (`a['0']=a` is recursive)\
temporal these are value that varies at anytime it depends.

    a;         a=0;       a['0']=a;    a                      =                                               await a;
existence < variables < dictionaries < temporal\
<sup><sub>these are valid modern js</sub></sup>

existence (values, procedures, symbols)\
variables (properties, functions)\
dictionaries (arrays, collections, tuples, enums)\
temporal (threads, async, reactive, generators)

## the pure
the V is a pure if it has a unique name, needs an input or a dependencies, and specifies the contents as the output.
its considered that primitive data types are pure if `needs` conforms the `contents` or vice versa.

V (name, needs, contents)
```
name(needs) {
    contents;
}
```
```
name: contents = needs;
```

## the track
the track is clasification of the behavior when the value is changed.

append
```
1 + '1' = '11'
a + '1'
```
override 
```
1 + 1 = 2
a + 1
```

cc by 4.0 share alike | [`@Pzda`](https://github.com/Pzda) & [`@gocs`](https://github.com/gocs)
