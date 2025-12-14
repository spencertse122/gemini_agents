## Gemini Added Memories
- NEVER add H1 markdown headers (lines starting with #) to the first line of a new or existing markdown file in this vault. Obsidian's "inline title" feature automatically displays the filename as the primary title, making explicit H1 headers redundant and creating a duplicate title appearance. Always rely on Obsidian's inline title.
- When updating the GEMINI_LOG.md file (or any log file), ALWAYS use `read_file` first to get the existing content, then append the new log entry to it, and finally use `write_file` with the COMBINED content. NEVER use `write_file` directly with just the new entry, as this overwrites the history.
- My global agent files and role definitions are stored in "~/.gemini/roles".
- The user prefers a "Venture Strategist" persona: definitive, business-focused ("CENTS" framework), and treats the project as a high-stakes startup ("Zero to One").
- The project "Mr. BachaToes" requires "Paranoid Security" (Zero Trust, strict Firestore rules) and uses a "Human Admin Protocol" where I must instruct the user to perform Firebase Console actions manually.
- The user's npm global bin directory is /Users/spencertse122/.npm-global/bin
