# ozfortress server configuration files

**Click [here](https://github.com/ozfortress/server-configs/archive/master.zip) to download ozfortress's server configs.**

---

## ozfortress Sixes (6v6) Seasonal League
The following formats are used in the ozfortress Sixes Seasonal League and have an associated configuration file in the ozfortress configs.

#### 5 Control Points
Standard 5 Control Points (5CP) maps are played to 30 minutes with a 5 point difference mercy rule. The following configuration represents this format:
```
mp_windifference 5
mp_timelimit 30
mp_winlimit 0
```
Load this configuration using `rcon exec ozfortress_6v6_5cp` or simply `rcon ozf-6s-5cp` on ozfortress servers.

#### King of the Hill
King of the Hill (KOTH) maps are played first to 3 with no time limit. The following configuration represents this format:
```
mp_windifference 0
mp_timelimit 0
mp_winlimit 3
```
Load this configuration using `rcon exec ozfortress_6v6_koth` or simply `rcon ozf-6s-koth` on ozfortress servers.

#### Golden Cap
In formats where ties are not allowed, a golden cap may be used to determine the winner of a 5CP match tied at 30 minutes. Golden Cap rounds are played till the first capture of the last point with no time limit. The following configuration represents this format:

```
mp_windifference 0
mp_timelimit 0
mp_winlimit 1
```
Load this configuration using `rcon exec ozfortress_golden_cap` or simply `rcon golden` on ozfortress servers.

---

## ozfortress Highlander (9v9/HL) Seasonal League
The following formats are used in the ozfortress Highlander Seasonal League and have an associated configuration file in the ozfortress configs.

#### 5 Control Points
Standard 5 Control Points (5CP) maps are played to 30 minutes with a 5 point/round win limit. The following configuration represents this format:
```
mp_winlimit 5
mp_timelimit 30
mp_winlimit 0
```
Load this configuration using `rcon exec ozfortress_6v6_5cp` or simply `rcon ozf-6s-5cp` on ozfortress servers.

#### King of the Hill
King of the Hill (KOTH) maps are played first to 3 with no time limit. The following configuration represents this format:
```
mp_windifference 0
mp_timelimit 0
mp_winlimit 3
```
Load this configuration using `rcon exec ozfortress_6v6_koth` or simply `rcon ozf-6s-koth` on ozfortress servers.

#### Stopwatch
Stopwatch maps are played to a max of 2 rounds with no time limit. The following configuration represents this format:
```
mp_maxrounds 2
mp_timelimit 0
mp_tournament_stopwatch 1
```
Load this configuration using `rcon exec ozfortress_6v6_koth` or simply `rcon ozf-6s-koth` on ozfortress servers.

---

## Other

The following formats are also included in the ozfortress server configurations but do not have a respective active competition.

#### Ultiduo
Ultiduo maps are played with a Soldier and Medic pair on each team. There is a winlimit of 1 round.

```
mp_timelimit 0
mp_winlimit 1
```
Load this configuration using `rcon exec ozfortress_ultiduo` or simply `rcon ultiduo` on ozfortress servers.

---
[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)

This work by [ozfortress](http://ozfortress.com) is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
