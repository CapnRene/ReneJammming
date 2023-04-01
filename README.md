# Rene's Jammming project

This is my Codecademy Jammming project's first part. I used Youtube video for scripting.

## How to diff in VScode.

https://vscode.one/diff-vscode/

### Repairs I made to get it work.

1. In SearchBar.js component is added onClick(this.search) method to button element. -easy find
2. In Spotify.js where you map json response, there is typo on artist: track.artist[0].name. It should be artist: track.**artists**[0].name, "s" in the end. https://developer.spotify.com/documentation/web-api/reference/get-track -easy(browsers developer console showed me the error, but not always)
3. In App.js I added Spotify getAccessToken call. So that search button should work first time when you click it. - easy

**Next one are my mistakes, console did not show any errors.**

4. Spotify.js two URL-s had double //(slash) so the path was wrong - medium find.
5. App.js in some places there was typos with "searchResults" , I wrote "SearchResults". - hard find. I found it thanks to diffing with working app component.
