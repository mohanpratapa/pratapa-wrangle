# pratapa-wrangle

## Assigned Play : Pericles, Prince of Tyre

## Speaker 1 : Gower

## Speaker 2 : Pericles

## Question : Who speaks the most?

## Commands :

1. $ curl "http://shakespeare.mit.edu/pericles/full.html" -o "output.txt"
2. $ curl "http://shakespeare.mit.edu/pericles/full.html" -o "output.txt" | sed 's/<\/*[^>]*>//g' > result.txt
3. $ grep '^GOWER$' result.txt -c > "gower.txt"
4. $ grep '^PERICLES$' result.txt -c > pericles.txt

## Answer : Pericles (121) speaks the most as Gower is limited to 7.
