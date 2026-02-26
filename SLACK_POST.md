<!-- Slack announcement post for #peonping / #show-and-tell -->
<!-- Copy the raw text below into Slack. Links use mrkdwn format. -->

Remember PeonPing, the thing that yells Warcraft quotes at you while you code?

I made 23 movie sound packs for it. 273 clips, 10 films. Your build fails and Walter Sobchak screams "HAS THE WHOLE WORLD GONE CRAZY?" You spam too many prompts and Farva demands a liter of cola.

*The pipeline:*
1. Grab the source video, curate the most iconic quotes per character, locate timestamps
2. Trim 1-5 second audio clips, run through speech-to-text to verify the clip matches the expected quote
3. QA verification loop — listen, flag, re-trim, repeat until clean
4. Normalize audio levels, generate CESP manifests with SHA256 checksums

*The packs:*

:movie_camera: *The Big Lebowski* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_the_dude|The Dude> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_walter|Walter> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_jesus|Jesus> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_maude|Maude> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_big_lebowski|Big Lebowski> _(NSFW)_
:briefcase: *Office Space* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/office_space|Ensemble> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/office_space_lumbergh|Lumbergh> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/office_space_peter|Peter> _(mild)_
:mega: *Anchorman* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/anchorman_burgundy|Burgundy> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/anchorman_brick|Brick> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/anchorman_news_team|News Team>
:dark_sunglasses: *Blues Brothers* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/blues_brothers_jake|Jake> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/blues_brothers_elwood|Elwood> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/blues_brothers|Ensemble> _(mild)_
:boom: *Die Hard* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/diehard|McClane & Co.> _(NSFW)_
:scales: *A Few Good Men* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/afewgoodmen|Ensemble> _(NSFW)_
:rocket: *Starship Troopers* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/starship_rico|Rico> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/starship_rasczak|Rasczak>
:police_car: *Super Troopers* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/super_troopers|Ensemble> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/super_troopers_farva|Farva> _(NSFW)_
:airplane: *Airplane!* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/airplane|Ensemble>
:necktie: *Zoolander* — <https://github.com/MattBillock/openpeon-movie-packs/tree/main/zoolander_derek|Derek> · <https://github.com/MattBillock/openpeon-movie-packs/tree/main/zoolander_hansel|Hansel>

They're all in the <https://openpeon.com|openpeon> registry. Install any pack:
```
peon packs use --install lebowski_walter
```

Open source: <https://github.com/MattBillock/openpeon-movie-packs>
