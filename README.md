# Fields of Mistria Data

Some data files for Fields of Mistria, used in my Guess-who Mistria game! 
Contains data.json file containing information on characters, image folder containing images of all portraits (from each season, and beach variations for dateable characters) and a background from the starting screen of the game.

If you want to use this data on your own coding project, a star on this repo or link in the README would be appreciated ;)
Happy coding!

This is accurate to the early access version.

## Data.json

Contains following data on each character:

- **name**: their name
- **gender**: either "F" or "M"
- **occupation**: [] array format (some characters have more than one)
- **relatives**: [] array format. If none or unknown contains "N/A"
- **martial_status**: either "Single", "Unavailable", or says who they are married to
- **birthday**: their birthday
- **romanceable**: either true or false
- **species**
- **appearance**: short description of physical appearance
- **personality**: short description of personality
- **story**: their role in the story
- **loved_gifts**: [] array format
- **liked_gifts**: [] array format
- **hated_gift**: each character has one unqiue hated gift
- **banned_gifts**: there are some banned gifts, but only for 5 characters:
  - Dozy and Henrietta cannot be given Alcohol, Caffeine or food with Chocolate.
  - The children in the game (Luc, Dell, Maple) cannot be given Alcohol or Caffeine related items.
- **default_filename**: the filename of the default portrait image. It is always set to the spring portrait. (Only Dozy and Henrietta don't have unique appearances)
- **spring_filename**: spring portrait image name
- **summer_filename**: summer portrait image name
- **fall_filename**: fall portrait image name
- **winter_filename**: winter portrait image name
- **beach_filename**: beach portrait image name (only dateable characters have this)

## Images

In the `characters/` folder, there is a folder of each character containing their portraits. Most characters have unique portraits for each season, and dateable characters also have a beach portrait. 
The filenames always start with the name of the season in lowercase: "spring", "summer", "fall", "winter" then followed with "_" and then the undercase name of the character. All files are png format.

*Credits: all of the portraits and info on characters are from [wiki.gg](https://fieldsofmistria.wiki.gg/)*

