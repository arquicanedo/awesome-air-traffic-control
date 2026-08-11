# Awesome Air Traffic Control

Air traffic control simulators, radar clients, tools, and training software.

## Scope

Software a controller, a trainee, or someone studying the job would use or learn
from: simulators, network radar clients, data and navigation tooling, and training
material.

Out of scope: flight simulators and pilot-side add-ons, flight trackers, and
airline or airport management games where control is incidental.

Entries are alphabetical within each section. The ordering is not a ranking, and
there are no ratings, prices, or maintenance-status labels here on purpose.

## Contents

- [Simulators](#simulators)
  - [Open source](#open-source)
  - [Proprietary](#proprietary)
- [Network controller clients](#network-controller-clients)
- [Research](#research)
- [Tools and data](#tools-and-data)
- [Training and reference](#training-and-reference)
- [Adjacent](#adjacent)
- [Related lists](#related-lists)

## Simulators

### Open source

- [ATC-pie](https://sourceforge.net/projects/atc-pie/) - Simulation with solo, multiplayer and teacher-student sessions, connecting to FGMS and FSD networks and integrating with FlightGear.
- [Co-ATC](https://github.com/yegors/co-atc) - Simulator that uses local SDRs for ADS-B telemetry and VHF comms, with optional AI capabilities.
- [openScope](https://www.openscope.co/) - Browser-based radar simulator with community-contributed airports.
- [Vice](https://pharr.org/vice/) - Simulation of the STARS system for TRACON and the ERAM system for enroute, with single-player and multi-controller modes.

### Proprietary

- [Air Traffic Greenlight](https://store.steampowered.com/app/1861880/Air_Traffic_Greenlight/) - Control aircraft where radar coverage is limited, across 12 cities and 25 airports built on real elevation data.
- [Airflow](https://store.steampowered.com/app/1693800/Airflow/) - Approach control at Seattle ARTCC in early access, with Salt Lake City as a separate region.
- [Airport Madness 3D](https://store.steampowered.com/app/445770/Airport_Madness_3D/) - Tower control from a 3D tower cab, with airport layouts and terrain built from real-world data.
- [Airwave](https://arwv.cc/) - Open-world sim covering approach, departure, tower and ground at any airport, with voice control and multiplayer, in alpha.
- [ATC Simulator 2](https://www.atcsimulator.com/) - Standalone TRACON simulator for Windows, used at universities in the United States.
- [ATC-SIM](https://atc-sim.com/) - Browser-based approach control at major international airports, with adjustable difficulty and wind.
- [Endless ATC](https://store.steampowered.com/app/666610/Endless_ATC/) - Approach control at nine real-world airports, with wind, wake turbulence, go-arounds and pilot speech.
- [Flight Level](https://store.steampowered.com/app/2105450/Flight_Level/) - Area and approach control with built-in airspace and scenario editors, made by radar controllers.
- [Global ATC Simulator](https://store.steampowered.com/app/270830/Global_ATC_Simulator/) - Tower, approach and departure control at close to 14,000 airports, using the NavDataPro database.
- [I am an Air Traffic Controller 4](https://store.steampowered.com/app/1348390/) - Tower control at Tokyo Haneda, with scenario-based play across the airport's four runways.
- [London Control](https://londoncontrol.com/) - Area, terminal and approach positions across London, Scottish and Terminal Control airspace, with voice recognition and AIRAC-sourced flight plans.
- [MultiScope](https://store.steampowered.com/app/4832540/MultiScope_Air_Traffic_Control/) - Approach control at Amsterdam Schiphol, with push-to-talk voice recognition on Windows.
- [ProjectATC](https://www.projectatc.com/) - Browser-based simulator with five connected positions from clearance through approach, at ten US airports.
- [Radar Identified](https://radar-identified.com/) - Enroute control across five German and four US Northeast sectors, for Windows and macOS.
- [SECTOR.mx](https://sector.mx) - Approach and enroute control in Mexican and US airspace, with Spanish and English voice control.
- [Skybound ATC](https://etellal.itch.io/skybound-atc) - Browser-based approach control with ILS procedures and emergencies, at airports including St. Barth, Hamburg and Heathrow.
- [Tower! Simulator 3](https://store.steampowered.com/app/2176130/Tower_Simulator_3/) - Tower control from a 3D tower cab across eleven airports, with voice recognition and multiplayer splitting ground, tower and departure.
- [Unmatched Air Traffic Control](https://play.google.com/store/apps/details?id=com.vector3d.uatc) - Guide aircraft to landing, parking and takeoff at a busy airport, on Android and Windows.
- [vectorheavy](https://vectorheavy.com/play) - Free browser-based ATC simulator.
- [VoiceATC Simulator](https://store.steampowered.com/app/3529560/VoiceATC_Simulator/) - Arrival and departure traffic by voice or by clicking aircraft labels, with local speech recognition and Navigraph AIRAC support.
- [Xavius Air Traffic Control Center](http://www.xavius.com/atcc.html) - Approach and enroute radar sectors in the New York, Chicago and Los Angeles facilities.

## Network controller clients

Software for controlling on live virtual networks rather than against simulated
traffic alone.

- [CRC](https://vnas.vatsim.net/crc) - Controlling client simulating US National Airspace System displays including STARS, ERAM, ASDE-X and the tower cab, part of the vNAS suite.
- [EuroScope](https://www.euroscope.hu/wp/) - VATSIM radar scope, extensible through plugins.
- [vatSys](https://virtualairtrafficsystem.com/) - Controller client for VATSIM, modeled on the Eurocat/TopSky ATC system.
- [VRC](https://vrc.rosscarlson.dev/) - Radar client for VATSIM, designed for multi-monitor setups.

## Research

Simulators and environments built for studying the air traffic system rather than
for practising the job.

- [BlueSky](https://github.com/TUDelft-CNS-ATM/bluesky) - Open source air traffic simulator from TU Delft, for fast-time simulation of conventional and UTM traffic.
- [BlueSky-Gym](https://github.com/TUDelft-CNS-ATM/bluesky-gym) - Gymnasium-style environments for reinforcement learning research in air traffic management, built on BlueSky.
- [BluebirdATC](https://github.com/project-bluebird/BluebirdATC) - Digital twin of UK airspace for ATC simulation and a training environment for AI agents, from the NATS, Exeter and Alan Turing Institute partnership.

## Tools and data

- [runways-in-use](https://github.com/L13w/runways-in-use) - Parses D-ATIS to determine active runway configurations at US airports, available via API.
- [SimAware TRACON](https://github.com/vatsimnetwork/simaware-tracon-project) - Updated TRACON boundaries for SimAware.

## Training and reference

- [Visual Vectoring](https://visualvectoring.com/) - On-demand simulation training for air traffic control, aimed at ANSPs, training organizations and universities.

## Adjacent

- [Air Defender](https://store.steampowered.com/app/3985030/Air_Defender/) - Manage a nation's air defenses, analyzing radar contacts and scrambling interceptors.

## Related lists

- [awesome-vatsim](https://github.com/Epse/awesome-vatsim) - Open source projects for the VATSIM network.

## Contributing

Additions are welcome, including your own project. See
[CONTRIBUTING.md](CONTRIBUTING.md).

## License

[CC0 1.0 Universal](LICENSE). Contributions are released under the same terms.
