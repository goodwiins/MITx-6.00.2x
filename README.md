

# Problem 1 - Song Playlist

Function Signature


The song_playlist function takes a list of songs, where each song is represented by a tuple ('song_name', song_len, song_size), and a maximum size (max_size) that represents the total size of songs you can fit. The function employs a greedy algorithm to select songs, starting with the first song in the list and then picking the next song as the one with the lowest file size that has not been already picked. The function returns a list of the subset of songs that fit within the given max_size, maintaining the order in which they were chosen.





## Usage/Examples

```python 
songs = [('song1', 3, 5), ('song2', 4, 8), ('song3', 2, 3), ('song4', 5, 10)]
max_size = 15

result = song_playlist(songs, max_size)
print(result)
# Output: ['song3', 'song1', 'song2']

```

