# Movie Quote Sound Packs for PeonPing

23 CESP v1.0 sound packs, 273 clips across 10 films. Built for [PeonPing](https://github.com/PeonPing/peon-ping) and any CESP-compatible player.

## Packs

### A Few Good Men (1992)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`afewgoodmen`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/afewgoodmen) | Ensemble | 19 | You can't handle the truth. |

### Airplane! (1980)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`airplane`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/airplane) | Ensemble | 17 | I am serious. And don't call me Shirley. |

### Anchorman (2004)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`anchorman_burgundy`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/anchorman_burgundy) | Ron Burgundy (Will Ferrell) | 14 | San Diego's finest anchor, kind of a big deal. |
| [`anchorman_brick`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/anchorman_brick) | Brick Tamland (Steve Carell) | 8 | Non-sequiturs as a service. |
| [`anchorman_news_team`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/anchorman_news_team) | Channel 4 News Team | 9 | 60% of the time, it works every time. |

### The Big Lebowski (1998)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`lebowski_the_dude`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_the_dude) | The Dude (Jeff Bridges) | 19 | The Dude abides. |
| [`lebowski_walter`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_walter) | Walter Sobchak (John Goodman) | 17 | Unhinged Vietnam veteran energy for your coding errors. |
| [`lebowski_jesus`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_jesus) | Jesus Quintana (John Turturro) | 8 | Maximum intimidation, minimum vocabulary. |
| [`lebowski_maude`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_maude) | Maude Lebowski (Julianne Moore) | 7 | Intellectual condescension as a notification sound. |
| [`lebowski_big_lebowski`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/lebowski_big_lebowski) | The Big Lebowski (David Huddleston) | 11 | Wealthy bluster and achievement-worship. |

### The Blues Brothers (1980)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`blues_brothers_jake`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/blues_brothers_jake) | Jake Blues (John Belushi) | 16 | On a mission from God. |
| [`blues_brothers_elwood`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/blues_brothers_elwood) | Elwood Blues (Dan Aykroyd) | 9 | Hit it. |
| [`blues_brothers`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/blues_brothers) | Ensemble | 9 | The full Blues Brothers experience. |

### Die Hard (1988)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`diehard`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/diehard) | McClane & Co. | 16 | Yippee-ki-yay. |

### Office Space (1999)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`office_space`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/office_space) | Ensemble | 10 | TPS reports and red staplers. |
| [`office_space_lumbergh`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/office_space_lumbergh) | Bill Lumbergh (Gary Cole) | 14 | Yeahhh, that'd be great. |
| [`office_space_peter`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/office_space_peter) | Peter Gibbons (Ron Livingston) | 14 | Corporate soul-death as notification sounds. |

### Starship Troopers (1997)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`starship_rico`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/starship_rico) | Johnny Rico (Casper Van Dien) | 11 | Would you like to know more? |
| [`starship_rasczak`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/starship_rasczak) | Lt. Rasczak (Michael Ironside) | 8 | Come on, you apes! You wanna live forever? |

### Super Troopers (2001)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`super_troopers`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/super_troopers) | Vermont Highway Patrol | 12 | Meow what is so damn funny? |
| [`super_troopers_farva`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/super_troopers_farva) | Farva (Kevin Heffernan) | 6 | I don't want a large Farva! |

### Zoolander (2001)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| [`zoolander_derek`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/zoolander_derek) | Derek Zoolander (Ben Stiller) | 10 | But why male models? |
| [`zoolander_hansel`](https://github.com/MattBillock/openpeon-movie-packs/tree/main/zoolander_hansel) | Hansel (Owen Wilson) | 9 | So hot right now. |

## CESP Categories

Every pack covers all 7 event categories:

| Category | Coding Event |
|----------|-------------|
| `session.start` | Workspace opens |
| `task.acknowledge` | Agent accepts work |
| `task.complete` | Task finished |
| `task.error` | Something broke |
| `input.required` | Waiting for user input |
| `resource.limit` | Rate/quota limit hit |
| `user.spam` | Too many rapid prompts |

## Install

```bash
# Install peon-ping
curl -fsSL https://raw.githubusercontent.com/PeonPing/peon-ping/main/install.sh | bash

# Install and switch to a pack
peon packs use --install lebowski_walter
```

## License

Audio clips are used under fair use for brief, transformative notification sounds. See individual pack manifests for details.
