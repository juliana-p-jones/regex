Regex is short for "regular expression"

It's a string of text that helps match, locate, and manage text.

I've already encountered regex!

In my own words... if I am trying to write code that finds key-words in a search BUT there might be many different spellings to account for, many different word combinations, part of a word like "james" and "jameson" both containing my search word james.

Also sometimes called a "pattern" specifies a set of strings required for a particular purpose.

Boolean "or":
regex using the | or operator:
"gray|grey" will match "gray" or "grey"
this can go on for too long and get messy- the example in the video went on to become too long and difficult to read

Grouping:
regex using Parenthesis (): gray|grey and gr(a|e)y are the same- this can help shorten the length of the search
Julia(n|n)a, because people spell my name wrong all the time

Quantification:
Conditional characters called QUANTIFIERS after TOKENS or a group, ie "?", "*", "+"
? = zero or one occurrence
* = zero or more occurrences
{n}- the character before is matched exactly n number of times
  {5}J Jones would return five J Joneses
{min,}- the character before would match up to max times
{,max}- character before matches up to max times
{min, max}   character before is matched at least min xs and no greater than max xs

Wildcard:
Uses a period like a dot operator to match ANY characters.
Seems dangerous.


\n matches new line
\s matches whitespace characer
\S matches a non-whitespace character
\w matches word character
\W matches a nonword character
\d matches one digit
\D matches one non-digit
[\b]- a backspace character
\c a control character
\n matches new line
\t- matches a tab
\r matches a carriage return
\ZZZ matches octal character ZZZ
\xZZ  matches hex character ZZ
\O a null character
\v a vertical tab
(xyz) grouping of characters
(?:xyz) non-capturing group of characters
[xyz] matches a range of character


