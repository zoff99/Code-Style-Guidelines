# Code Style Guidelines for: ***Android / Java***


##File encoding
All Sourcefiles should be UTF-8

##Indentation
Use only tabs to indent. (not single spaces)
always and ONLY use "Allman style" https://en.wikipedia.org/wiki/Indent_style#Allman_style

**a few examples of correct Allman style Indentation:**
```
if (x == y) 
{
  x++;
  foo();
} 
else 
{
  x--;
  bar();
}
```

```
@Override public void method()
{
  if (value == 12)
  {
    always_write_brackets(value);
  }
}
```

**never ever do these:**
```
if (x == y) {
  x++;
  foo();
} 
else x--;
```

```
@Override public void method()
{
  if (value == 12)
    always_write_brackets(value);
}
```

```
if (something)
  functionOne();
else 
  functionTwo();
```

##Comments
Use comments as often as possible.
Comment only in English

##Naming Conventions
Constants are in all CAPS
```
final static String CONSTANT_STRING_FOR_SOMETHING = "abcxd5";
```
Normal Identifiers (Variables) should be all lowercase and use only ASCII Letters and Digits and underscores.
Use only normal english words

**wrong:**
```
int Number = 1;
String funnyNameUpperAndLower = "x";
float aufDeutschGehtsAuch = 1.3f;
```
**correct:**
```
int number = 1;
String funny_name_upper_and_lower = "x";
float no_german_only_english = 1.3f;
```

##Grouping parentheses
always use parentheses often, so no confusion occurs

**wrong:**
```
if ( i + 3 * 4 == 12 / 3 + 12 )
```

**correct:**
```
if ( i + ( 3 * 4 )== ( 12 / 3 ) + 12 )
```

