# polyglotdljs
This project is intended to enable extension of youtube-dl (and possibly other projects in the future) into polyglottal (i.e., multilingual) projects.

## How will you do this?
1. Transpile the youtube-dl Python code into whatever language we are going to use to extend it (we are starting with TypeScript/JavaScript)
2. Extend the transpiled code in the language of our choice to add additional functionality to youtube-dl (or other projects if this proves successful)
3. Transpile the extensions back to Python and either request to integrate them into the main project or allow this to remain a fork of youtube-dl
4. Build youtube-dl (or the fork)
5. Enjoy our new enhanced functionality, written in any language we want!

## Note
Once the code that trabspiles the necessary files is complete enough to create an extensible youtube-dl SDK, I wil pubish to the server.
