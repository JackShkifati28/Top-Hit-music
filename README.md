# Top-Hit-music

## Description
The purpose of this project is to generate a report for a record label company. The report lists the top hit music artist names of the last couple of weeks, sorted in alphabetical order.

## Instructions
The way we obtain this report is as follows:

First, we downloaded a CSV file from the Spotify website. Then we created a Java class called `SpotifyChart` that reads the data from the file, sorts the artist names in alphabetical order, and removes any duplicate artists.

Second, we created a second class called `Artist` that serves as a node representing an artist. We then created an inner class called `TopStreamingArtists`, which extends the `SpotifyChart` class. This enables us to retrieve the artist data from the `SpotifyChart` class. We then add the data of each artist to a new node, starting at the end of the artist report due to the properties of a linked list: first in, last out. Once we finish populating the linked list, we write all the data to a text file named `ArtistsSorted-10.05.2020`.

