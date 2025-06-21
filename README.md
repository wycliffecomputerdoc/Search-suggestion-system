# Search Suggestion System 🔍

This project implements a `SearchSuggestionSystem` using a Trie in JavaScript.

## Features

- Returns up to 3 lexicographically sorted product suggestions for each prefix.
- Efficient insertion and prefix lookup.
- Designed using Object-Oriented JavaScript.

## Example

```javascript
const system = new SearchSuggestionSystem(["money", "mouse", "moneypot", "monitor", "mousepad"]);
console.log(system.getSuggestions("mouse"));
