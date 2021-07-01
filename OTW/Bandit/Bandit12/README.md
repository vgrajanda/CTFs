# Solution guide

The way to get into Bandit12 is decipher the text encoded on ROT13 algorithm and the command that i use to solve this is:

> cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

it can be useful create an alias to decipher this kind of algorithms like:

> alias rot13='tr "A-Za-z" "N-ZA-Mn-za-m"'
