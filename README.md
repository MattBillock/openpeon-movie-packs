# Movie Quote Sound Packs for PeonPing

20 CESP v1.0 sound packs featuring iconic movie quotes mapped to coding events. Built for [PeonPing](https://github.com/PeonPing/peon-ping) and any CESP-compatible player.

## Packs

### The Big Lebowski (1998)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| `lebowski_the_dude` | The Dude (Jeff Bridges) | 21 | Laid-back stoner philosophy meets coding notifications. |
| `lebowski_walter` | Walter Sobchak (John Goodman) | 19 | Unhinged Vietnam veteran energy for your coding errors. |
| `lebowski_jesus` | Jesus Quintana (John Turturro) | 12 | Maximum intimidation, minimum vocabulary. |
| `lebowski_maude` | Maude Lebowski (Julianne Moore) | 10 | Intellectual condescension as a notification sound. |
| `lebowski_big_lebowski` | The Big Lebowski (David Huddleston) | 13 | Wealthy bluster and achievement-worship. |

### Office Space (1999)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| `office_space` | Ensemble | 12 | TPS reports and red staplers. |
| `office_space_lumbergh` | Bill Lumbergh (Gary Cole) | 17 | Yeahhh, that'd be great. |
| `office_space_peter` | Peter Gibbons (Ron Livingston) | 15 | Corporate nihilism as notification sounds. |

### Anchorman (2004)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| `anchorman_burgundy` | Ron Burgundy (Will Ferrell) | 16 | San Diego's finest anchor, kind of a big deal. |
| `anchorman_brick` | Brick Tamland (Steve Carell) | 14 | Non-sequiturs as a service. |
| `anchorman_news_team` | Channel 4 News Team | 10 | Whammy! Sex Panther! 60% of the time, it works every time. |

### The Blues Brothers (1980)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| `blues_brothers_jake` | Jake Blues (John Belushi) | 17 | On a mission from God. |
| `blues_brothers_elwood` | Elwood Blues (Dan Aykroyd) | 11 | Hit it. |
| `blues_brothers` | Ensemble | 9 | The full Blues Brothers experience. |

### Starship Troopers (1997)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| `starship_rico` | Johnny Rico (Casper Van Dien) | 17 | Would you like to know more? |
| `starship_rasczak` | Lt. Rasczak (Michael Ironside) | 10 | Come on, you apes! You wanna live forever? |

### Super Troopers (2001)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| `super_troopers` | Vermont Highway Patrol | 14 | Meow what is so damn funny? |
| `super_troopers_farva` | Farva (Kevin Heffernan) | 8 | I don't want a large Farva! |

### Zoolander (2001)

| Pack | Character | Sounds | Description |
|------|-----------|--------|-------------|
| `zoolander_derek` | Derek Zoolander (Ben Stiller) | 15 | But why male models? |
| `zoolander_hansel` | Hansel (Owen Wilson) | 13 | So hot right now. |

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
brew install peonping/tap/peon-ping

# Install a pack
peon install mattbillock/openpeon-movie-packs/lebowski_walter

# Or clone and copy manually
git clone https://github.com/MattBillock/openpeon-movie-packs.git
cp -r openpeon-movie-packs/lebowski_walter ~/.openpeon/packs/
```

## License

Audio clips are used under fair use for brief, transformative notification sounds. See individual pack manifests for details.
