# PSTG – St. George Island, Old North Runway (MSFS 2024)

Scenery for **Microsoft Flight Simulator 2024** recreating the old north-side
gravel runway on St. George Island, Alaska (Pribilof Islands), as it was before
it closed in the early 1990s.

It is a separate add-on airport (**PSTG**) and does not replace the default
St. George airport (**PAPB**).

## At a glance

| | |
|---|---|
| Airport | PSTG – St. George Island, North side Runway |
| Runway | 08 / 26, about 4,175 ft (1,273 m), red volcanic gravel |
| Weather (AWOS) | 132.325 MHz |
| NDB / ADF | SRI, 391 kHz *(approximate, not the historical frequency)* |
| Fuel | 100 and Jet A |
| Parking | 2 small spots by the hangar (Navajo and smaller) |
| Tower / ILS / VASI | none – fly it visually |

## About the old runway

Until the early 1990s this short gravel strip was the main air link between
St. George Island and the mainland. It lay right beside the north side of
St. George village, close to the high cliffs on the northern shore and their
seabird colonies, so approaches passed very near houses and buildings.

In its heyday it handled scheduled service with DC-6s, C-130s, Beech 1900s and
Metroliners.

It was a difficult place to fly into. With high ground close by and the Bering
Sea just off the end, pilots met sudden fog, strong crosswinds and heavy
turbulence. Because the village was right alongside, there was no room to
lengthen it for larger cargo or emergency aircraft.

The strip was decommissioned around the end of 1992 to early 1993. The Alaska
DOT&PF built a new, larger St. George Airport (FAA: PBV, ICAO: PAPB), which
opened in 1993 and is the airport you will find in the sim by default.

## Download and install

1. Download the latest zip from the **[Releases](../../releases)** page
   (not the green "Code" button – that is the source).
2. Close MSFS 2024 and unzip.
3. Copy the folder `farwestlife-pstg-2025` into your **Community** folder.
   Press Windows key + R and paste one of these:
   - Microsoft Store / Xbox / Game Pass:
     `%LOCALAPPDATA%\Packages\Microsoft.Limitless_8wekyb3d8bbwe\LocalCache\Packages\Community`
   - Steam:
     `%APPDATA%\Microsoft Flight Simulator 2024\Packages\Community`
4. Start MSFS 2024 and search for **PSTG**.

**Updating from an older version:** delete any old `PASG_2025` or
`farwestlife-pstg-2025` folder from Community first, so you do not get two
copies.

**Uninstall:** delete `farwestlife-pstg-2025` from your Community folder.

## Notes

- **Which end you start on:** MSFS puts you on the runway that faces the current
  wind. To start on the other end (08 = west, by the main apron and hangar;
  26 = east), change the wind direction in the weather settings before loading in.
- The island has no trees; none are added.
- The small concrete pad south of the runway is just a pad, not a helipad.
- The sim's own road traffic may show a car or two on the strip. The strip was
  used as a road after it closed, and that road is in the sim's base map data.
- Dust on landing and takeoff depends on the aircraft.

## Building from source

1. Install the MSFS 2024 SDK (Developer Mode → Help → SDK Installer).
2. In MSFS 2024, open the Project Editor and open `PSTG.xml` from this repo.
3. Click **Build All in project**. The package is written to
   `Packages/farwestlife-pstg-2025`.

The scenery source is `PackageSources/sceneries/PSTG.xml`.

## License

[CC BY-NC 4.0](LICENSE) – free to use, share and adapt with credit;
please do not sell it.

Scenery by Cal (Farwestlife / Pribilof Hangar). Uses default objects that come
with MSFS 2024.
