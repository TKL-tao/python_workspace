# Python Data Type
## int
    
```python
a = int(1.9) >>> a = 1
```
## float

```python
a = float(1) >>> a = 1.0
```
## bool
## string
Characters in string cannot be modified, such as ```mystring[0]=0``` is wrong.
### methods in string

- .center(**w**): 
- .ljust(**w**):
- .rjust(**w**):
- .lower():
- .upper():
- .count(**item**): 
- .find(**item**): return the place of the first occurrence of **item**
- .split(**item**): remove all **item**s in string and split string, return a list. Default **item**: \n, \t,...
- 
- 

# Basic Numeric Calculation
- /

No matter if input is *int* or *float*, the output is always *float*.

- //

If either divisor or dividend is *float*, the output is *float*; else, int.

- %

If either divisor or dividend is *float*, the output is *float*; else, int.

# Python Basic Class Type
## Set
### Operations in set
- "in": Check if an element is in a set
- "<=": Check if one set is a subset of another set
- "len":
- "&":
- "|":
- "-":

### Methods in set
- .union(): return a union.
- .intersection(): return an intersection.
- .difference(): return a difference.
- .issubset():
- .add(): *change the original list*
- .remove(): *change the original list*
- .pop(): *change the original list*
- .clear(): *change the original list*

## List
### Operators in list

- "+": Connect two lists
- "*": Repeat the list for ? times
- "in": Check if an item is an element of a list

### methods in list

- .append(**item**): *change the original list*
- .insert(**i**, **item**): *change the original list*
- .pop(**-1**): *change the original list*
- .sort(): cannot operate successfully when a list contains string and int/float *change the original list*
- .reverse(): *change the original list*
- .index(**item**): return the index of the first **item**
- .count(**item**):
- .remove(**item**): remove the first occurrence of **item**
- 

## Dict
### Operations in Dict

- "in": Check if an item is a dictionary key
- "del": ```del mydict['mykey']```

### Methods in Dict

- .keys(): The returned data type is *dict_keys*
- .values(): The returned data type is *dict_values*
- .items(): The returned data type is *dict_items*
- .get(**mykey**, ***myword***): Return the corresponding value, otherwise return ***myword***

## Tuple