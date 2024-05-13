**Introduction**

This Java project implements a simple music player utilizing Object-Oriented Programming principles. The primary classes include Album and Song, allowing users to create albums, add songs to them, and create playlists. The project also includes a Main class that simulates a basic user interface for interacting with the music player.

**Classes Overview**

Album.java

**Attributes:**

-> name (String): Name of the album.

-> artist (String): Name of the artist.

-> songs (ArrayList<Song>): List of songs in the album.

**Methods:**

-> findSong(String title): Song: Finds a song by title.

-> addSong(String title, double duration): boolean: Adds a new song to the album.

-> addToPlayList(int trackNumber, LinkedList<Song> PlayList): boolean: Adds a song to a playlist by track number.

-> addToPlayList(String title, LinkedList<Song> PlayList): boolean: Adds a song to a playlist by title.

**Song.java**

**Attributes:**

-> title (String): Title of the song.

-> duration (double): Duration of the song.

**Methods:**

-> getTitle(): String: Returns the title of the song.

-> getDuration(): double: Returns the duration of the song.

-> toString(): String: Returns a string representation of the song.

**Main.java**

**Attributes:**

-> albums (ArrayList<Album>): List of albums in the music player.

**Methods:**

-> play(LinkedList<Song> playList): void: Simulates the playback functionality of the music player.

-> printMenu(): void: Prints the available options in the music player.

-> printList(LinkedList<Song> playList): void: Prints the list of songs in the playlist.

-> main(String[] args): void: The main method initializing albums, adding songs, and creating playlists.

**Getting Started**

To use this music player, create instances of the Album and Song classes, add songs to albums, and create playlists. Run the main method in the Main class to simulate the music player interface. Follow the on-screen prompts to interact with the music player.

Feel free to expand upon this project by adding additional features and improvements.
