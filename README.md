# VHF / UHF radio stuff

<img align="right" height="200" src="https://github.com/kieran/radio/assets/3444/6042b686-85a3-444f-8054-591649ec1534">

Mostly a config for my [Baofeng UV-5R](https://share.temu.com/t8gaph1k8tA) radios in Victoria BC.

I bought them in Oct '23 for $31 CAD/ea with free shipping. You should be able to find a similar deal.

## CHIRP radio config for the BC coast

[CHIRP](https://chirp.danplanet.com/projects/chirp/wiki/Home) is a FOSS tool to program many models of radio.

My CHIRP config can be found here: [`bc-coast.csv`](https://raw.githubusercontent.com/kieran/radio/main/bc-coast.csv)

![image](https://github.com/kieran/radio/assets/3444/ead515a0-2d10-4cb4-96d9-3b170f10aaea)

| Channel(s) | description |
| --- | --- |
| 0 | NOAA weather station in Blaine WA - probably the most applicable one to Victoria (where I live) |
| 1-28 | Marine VHF channels, intended for easy use as a backup boat VHF radio |
| 60-74 | More marine VHF channels |
| 77-88 | Yet more marine VHF channels |
| 101-122 | GMRS Channels (each mapped to the GMRS channel + 100) |

### Channels worth mentioning
| Channel(s) | description |
| --- | --- |
| 16 | International distress + calling channel (monitor this on the boat) |
| 21 | Continuous Marine Broadcast (similar to NOAA weather, but for Canada?) |
| 66 | BC Marinas channel |
