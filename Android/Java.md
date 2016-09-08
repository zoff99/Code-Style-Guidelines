# Code Style Guidelines for: ***Android / Java***


##File encoding
All Sourcefiles should be UTF-8

##Indentation
Use only tabs to indent. (not single spaces)

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

