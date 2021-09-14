# Regex Intro
- Regular expression is a sequence of characters that define a pattern. These patterns can be used in find and/or replace algorithms, or for input validation
- `/` : All regexes are enclosed within forward slashes to indicate where they begin and where the end
- `^` : The cicumflex accent matches the beginning of the string or the beginning of the line. This means your pattern will not match anything that has any text before it. Example: `/^Once upon a time/` will match any line beginning with that sequence
- `$` : The dollar sign matches the end of the string. The opposite of `^`. Example: `/ation$/` will match any line ending witht the string "ation".
- `[]` : Brackets are used to match a single character from the list enclosed in them. For example, `/[abc]/` will match either a,b, or c. Regexes accept ranges of letters as well, such as a-z or d-m, and even ranges like `/[a-f0-6]/`
- `*` : An asterick acts as a quantifier to specifiy that the preceding character may appear 0 to n times. Example `/[ab]\*/` will match abab, aaaaaaa, but will also match an empty string.
`+` : A plus sign is similar to `*`, except that the preceding character has to appear at least once, meaning it will match the same strings as the previous example, except for the empty string.
- `{}` : The braces are used when you want to specifiy the number of times the preceding character should appear. Writing a single number within the braces will match the strings that contain the preceding character or pattern that exact amount of times. They can also include ranges. `{4,8}` is a string that contains 4 to 8 characters
- Regex that validates only lower case letters? `/^[a-z]+$/`
- Regex that validates only upper case letters? `/^[A-Z]+$/`
- Regex that validates both lower and upper case letters? `/^[a-zA-Z]+$/`
- Regex that validates that only phone num accepts exactly 10 digits? `/*[0-9]{10}$/`
- Regex that validates username lower case letters & numbers? `/^[a-z0-9]{8}$/`
- Regex that validates username format both lower and upper case letter, numbers, and should contain between 3 to 10 characters? `/^[a-zA-Z0-9]{3,10}$/`

