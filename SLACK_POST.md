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

:movie_camera: *The Big Lebowski* — <https://openpeon.com/packs/lebowski_the_dude|The Dude> · <https://openpeon.com/packs/lebowski_walter|Walter> · <https://openpeon.com/packs/lebowski_jesus|Jesus> · <https://openpeon.com/packs/lebowski_maude|Maude> · <https://openpeon.com/packs/lebowski_big_lebowski|Big Lebowski> _(NSFW)_
:briefcase: *Office Space* — <https://openpeon.com/packs/office_space|Ensemble> · <https://openpeon.com/packs/office_space_lumbergh|Lumbergh> · <https://openpeon.com/packs/office_space_peter|Peter> _(mild)_
:mega: *Anchorman* — <https://openpeon.com/packs/anchorman_burgundy|Burgundy> · <https://openpeon.com/packs/anchorman_brick|Brick> · <https://openpeon.com/packs/anchorman_news_team|News Team>
:dark_sunglasses: *Blues Brothers* — <https://openpeon.com/packs/blues_brothers_jake|Jake> · <https://openpeon.com/packs/blues_brothers_elwood|Elwood> · <https://openpeon.com/packs/blues_brothers|Ensemble> _(mild)_
:boom: *Die Hard* — <https://openpeon.com/packs/diehard|McClane & Co.> _(NSFW)_
:scales: *A Few Good Men* — <https://openpeon.com/packs/afewgoodmen|Ensemble> _(NSFW)_
:rocket: *Starship Troopers* — <https://openpeon.com/packs/starship_rico|Rico> · <https://openpeon.com/packs/starship_rasczak|Rasczak>
:police_car: *Super Troopers* — <https://openpeon.com/packs/super_troopers|Ensemble> · <https://openpeon.com/packs/super_troopers_farva|Farva> _(NSFW)_
:airplane: *Airplane!* — <https://openpeon.com/packs/airplane|Ensemble>
:necktie: *Zoolander* — <https://openpeon.com/packs/zoolander_derek|Derek> · <https://openpeon.com/packs/zoolander_hansel|Hansel>

Install any pack:
```
peon install mattbillock/openpeon-movie-packs/lebowski_walter
```

Open source: <https://github.com/MattBillock/openpeon-movie-packs>
