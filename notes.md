Quotes = https://type.fit/api/quotes

fetch localy from quotes.js
function newQuote(){
    // pick a random quote from apiQuotes array
    const quote = localQuotes[Math.floor(Math.random() * localQuotes.length)];
    console.log(quote);
}

newQuote();