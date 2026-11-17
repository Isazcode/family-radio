# Family Radio

A map of Florida ham radio repeaters, plus ready-to-load CHIRP channel files for the family's radios.

**Live map:** https://isazcode.github.io/family-radio/
**Downloads:** https://isazcode.github.io/family-radio/#downloads

## Which file do I need?

| Area | Radio | File | Channels |
|---|---|---|---|
| South Florida | UV-5R and other 128-channel radios | [SouthFL_UV-5R_126ch.csv](files/SouthFL_UV-5R_126ch.csv) | 126 |
| South Florida | UV-17R and other large-memory radios | [SouthFL_Full_706ch.csv](files/SouthFL_Full_706ch.csv) | 706 |
| South Florida | UV-9G (GMRS) | [UV-9G_GMRS_117ch.csv](files/UV-9G_GMRS_117ch.csv) | 117 |
| Jacksonville | UV-5R and other 128-channel radios | [Jacksonville_UV-5R_108ch.csv](files/Jacksonville_UV-5R_108ch.csv) | 108 |
| Jacksonville | UV-17R and other large-memory radios | [Jacksonville_Full_754ch.csv](files/Jacksonville_Full_754ch.csv) | 754 |

The model name is on the label under the radio's battery.

## How to load a file

1. Install [CHIRP](https://chirpmyradio.com/projects/chirp/wiki/Download) (free). Get the "CHIRP-next" build.
2. Download the file for your radio from the table above.
3. Plug the radio in with its programming cable and turn it on.
4. In CHIRP, choose **Radio → Download from Radio**, then **File → Save As** to keep a backup of what was on the radio.
5. On the **Memories** tab, press **Ctrl+A**, then **Delete**, to clear the old channels.
6. Choose **File → Import**, pick the CSV file, then **Radio → Upload to Radio**.

## Family channels

| | South Florida files | Jacksonville files |
|---|---|---|
| Main family repeater | ch 5, N4RQY 147.210 (tone 131.8) | — |
| Backup family repeater | ch 6, W4MOT 146.790 (tone 88.5) | — |
| Family simplex (radio to radio) | ch 1, 146.550 (tone 100.0) | ch 4, 146.550 (tone 100.0) |
| **Statewide link between South Florida and Jacksonville (SARnet)** | **ch 26**, W4AB 442.850 (tone 110.9) | **ch 1**, N4FCU 444.700 (tone 127.3) |
| Backup statewide link | ch 25, N0LO 442.825 | ch 2, St Augustine 442.800 |

SARnet is shared with the whole state and with emergency nets. Keep calls short: make contact, then switch to a phone call or a local repeater for longer conversations. After you key up, wait a second or two before talking so the link can connect.

## Good to know

- An amateur radio license is required to transmit on the ham channels.
- Repeaters are set to **Tone**: your radio sends the tone the repeater needs, and you hear everything the repeater sends.
- In the large files, FRS, GMRS and MURS channels transmit and receive. Marine and business channels are receive only.
- Repeater status comes from RepeaterBook (November 2026). The first part of each file lists repeaters that were checked as on the air. Later channels came from a statewide list and may include some that are off the air.
- Family locations on the map are general areas only, not addresses.

Map data: Natural Earth (roads), US Census via us-atlas (counties and state outlines).
