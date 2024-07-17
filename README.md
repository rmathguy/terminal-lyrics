# terminal-lyrics
A command line .lrc song lyric presenter

# Goals:
Given song player metadata and a lyrics directory

1) Find the lyrics to a song via online respositories
   * Download and cache .lrc files.
2) Display the lyrics in sync with the player via playerctl.
   * Use playerctl's interface to get song times and metadata
3) Do this all via the command line
   * Keep it compatible.
   * Try to keep to bash and to the C-lang.
