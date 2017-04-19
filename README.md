# dictionaries
Dictionaries of synonyms and ignored words curated via crowdsourcing

### Rules
- Insert items in alpabetical order, this will speed up lookup using binary search (for dictionaries of synonyms, the preferred name (first field); for stop words, the single word in one line)
- Use UTF8 and expand special characters in different synonyms or stopwords (`göthe,goethe` or `gübbörisch,guebbörisch,gübboerisch,guebboerisch`)
- checks are performed case insensitive, thus always write in lowercase (~~`Goethe`~~ --> `goethe`)
