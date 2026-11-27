<div align="center">

<img src="assets/cover.svg" width="100%" alt="Heartbeat Test — hands-on electronics and PCB project">

# Heartbeat Test — Electronics & PCB Project

![ATmega328P](https://img.shields.io/badge/Controller-ATmega328P-A25733?style=flat-square&logo=microchip&logoColor=white)
![Proteus](https://img.shields.io/badge/Design-Proteus-52664B?style=flat-square)
![PCB](https://img.shields.io/badge/Hardware-Physical%20PCB-80623F?style=flat-square)

**Hassan Ali Janjua · Mechatronics Engineering · Air University, Islamabad**

[My approach](#from-the-design-to-the-workbench) · [My PCB](#my-physical-pcb) · [Demonstration](#project-demonstration) · [Proteus project](Hearbeat%20Test.pdsprj) · [Project report](Project%20Report.pdf)

</div>

## A project I built with my own hands

I wanted to take an electronics design beyond the screen and turn it into a physical circuit. My Heartbeat Test project gave me the opportunity to work with a microcontroller-based circuit, design its printed circuit board and work on the hardware myself.

What makes this project particularly important to me is the hands-on part. I did the practical work myself, rather than stopping at a simulation. Seeing the PCB take shape from the design was one of the most satisfying parts of the project.

This repository brings together my Proteus design, the photograph of my fabricated PCB, a demonstration recording and the original project report.

## My physical PCB

<p align="center">
  <a href="PCB.jpg"><img src="PCB.jpg" width="820" alt="Original photograph of my fabricated heartbeat-test PCB, showing physical traces and drilled component holes"></a>
  <br><em>The physical PCB I worked on — original project photograph.</em>
</p>

The photograph shows the board at the fabrication stage, with the conductive tracks, component pads and drilled holes visible. I wanted to preserve this part of the build because it shows the physical work behind the electronics design.

## From the design to the workbench

<img src="assets/build-process.svg" width="100%" alt="Project workflow: circuit design, PCB layout, physical board and demonstration">

### 01 / Circuit design in Proteus

I started with the electronics design in Proteus. The project is based on the ATmega328P microcontroller, which is the main controller identified in my project description. The Proteus project contains the schematic and the PCB layout.

[Open the original Proteus design](Hearbeat%20Test.pdsprj)

### 02 / PCB layout

Once the circuit design was in place, I worked on translating it into a physical board layout. For me, this was the point where the electrical connections had to become real tracks and component positions rather than just lines on a schematic.

The Proteus project archive contains both `ROOT.DSN` (schematic) and `ROOT.LYT` (PCB layout).

### 03 / Hardware implementation

I worked on the PCB myself. The original photograph shows the result at the bare-board stage, including the routed tracks and through-holes. I kept the original photo and recording here to document the actual hardware work.

### 04 / Demonstrating the project

I recorded a video of the project and kept it alongside the design and report so the practical work can be explored directly.

## Project demonstration

<table>
<tr>
<td width="48%" align="center">
<a href="PCB%20Video.mp4"><img src="assets/video-card.svg" width="100%" alt="Open my original PCB demonstration video"></a>
</td>
<td width="52%" valign="top">

<b>My original PCB demonstration</b>

<br><br>
A recording from the project, kept in its original format.

<br><br>
<a href="PCB%20Video.mp4"><b>Watch or download the video →</b></a>

<br><br>
<a href="Project%20Report.pdf">Read my project report →</a>

</td>
</tr>
</table>

GitHub may open the video file page or offer a download instead of playing it inside the README.

## What I learned from building it

Working on the circuit and PCB helped me connect the electronics theory I had studied with the practical side of building hardware. The design has to make sense electrically, but it also has to be possible to turn it into a real board.

| Area | Project experience |
| --- | --- |
| Electronics design | Working with a microcontroller-based circuit |
| PCB design | Translating electrical connections into a board layout |
| Practical electronics | Working on the physical PCB and inspecting the tracks and holes |
| Engineering documentation | Keeping the design file, photograph, recording and report together |

## Explore the project files

| File | What's inside |
| --- | --- |
| [Hearbeat Test.pdsprj](Hearbeat%20Test.pdsprj) | Original Proteus project, schematic and PCB layout |
| [PCB.jpg](PCB.jpg) | My original physical board photograph |
| [PCB Video.mp4](PCB%20Video.mp4) | Original project demonstration |
| [Project Report.pdf](Project%20Report.pdf) | Original academic project report |
| [Technical notes](docs/project-notes.md) | File structure, design review and scope |

<details>
<summary><b>How to open the design in Proteus</b></summary>

Download the original `Hearbeat Test.pdsprj` file and open it using a compatible Proteus installation. Inspect the schematic and PCB layout in the application. Review the report for the component details and testing context before reproducing the circuit.

The project archive contains design files, but no separately published microcontroller firmware source is included in this repository. Do not assume the schematic is ready for fabrication or programming without reviewing it.

</details>

## Project scope

This is an academic electronics prototype. I have not claimed a verified heart-rate accuracy, calibration result or clinical performance. It is not a validated medical device and should not be used for diagnosis or medical decisions.

---

<div align="center">

**Hassan Ali Janjua**  
Mechatronics Engineering · Embedded Electronics · PCB Design

[My engineering portfolio](https://github.com/HassanAliJanjua03)

</div>
