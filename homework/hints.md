## Some general hints
- did you deal with NA values?
- the danceability % of some rows is invalid (greater than 100%)
- the streams column is an object and not a number for the Love Grows (Where My Rosemary Goes) song - did you deal with this?
- were you careful to extract all artists from the artist column? (some songs have multiple artists)
- When getting the top ranked songs, were you careful to not include songs that didn't make it to the charts at all (in_spotify_charts=0)?
- did you save the visualization as a PDF and did you check the PDF (some of the artist labels might be cut off ;))
- in the saved csv, did you strip() the whitespace from the beginning and end of the artist names (so " Taylor Swift" -> "Taylor Swift")?
- does the saved clean csv look ok?
- are your 5 randomly picked songs reproducible (do you always get the same 5 songs)?
