: {align="center"}

DEVAMITRA.BIN

ECE • EMBEDDED • ELECTRONICS • BUILD

A digital lab notebook of things I learn, break, debug, and build.




:::

00 // BOOT SEQUENCE

$ whoami

devamitra

$ system.profile

FIELD        Electronics & Communication Engineering
MODE         Learn → Build → Test → Debug → Repeat
INTEREST     Embedded Systems / IoT / Electronics
CURRENT      C Programming + Microcontrollers
WORKSTYLE    Hands-on • Curious • Experimental

01 // THE IDEA

I like the point where code becomes a physical system.

Instead of keeping programming, electronics, and hardware as separate
subjects, I am building projects that connect them:

        ┌─────────────┐
        │    IDEA     │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │    CODE     │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │  HARDWARE   │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │   SENSOR    │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │    DATA     │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │   ACTION    │
        └─────────────┘

02 // CURRENT LOADOUT

Area       Working With

LANG     C, Python
MCU      ESP32, Arduino, VEGA
IoT      Sensor systems, dashboards, connectivity
COMM     UART, SPI, I²C
SIM      Wokwi
DESIGN   PCB / electronics design
TOOLS    VS Code, Arduino IDE, Git, GitHub
LAB      Sensors, actuators, embedded prototypes

03 // REPOSITORY MAP

My GitHub is organized like a small engineering workspace:

devamitra-b/
│
├── code-with-c/          → C programming practice
├── Electronics_Playground/ → electronics experiments
├── 8085A_Toolkit/        → 8085A learning & programs
├── Maze_with_me/         → robotics / maze project
├── VEGA/                 → VEGA board experiments
│
└── project-lab/
    ├── sensors/
    ├── embedded/
    ├── iot/
    └── experiments/

Repositories will keep changing as the lab grows.

04 // BUILDS

01 --- Maze Robot

A robotics project focused on sensing, decision-making and movement.

Stack: Arduino Sensors Embedded C Robotics

02 --- Smart Street Light Fault Detection

An electronics/embedded concept for identifying abnormal street-light
conditions.

Stack: Sensors Microcontroller Embedded Systems IoT

03 --- Smart Poultry Farm Monitoring

A monitoring concept combining environmental sensing with automated
observation.

Stack: IoT Sensors Embedded Systems

04 --- Smart Dental Kit

A smart-device concept combining electronics, sensing and embedded
control.

Stack: Embedded Systems Sensors Microcontroller

05 --- VEGA Experiments

Hands-on experiments with the VEGA Aries IoT platform, serial
communication and embedded development.

Stack: VEGA UART Arduino IDE Embedded C

05 // DEBUG CONSOLE

The most useful part of embedded development is often the bug.

EXPECTED ────────────────┐
                         │
                         ▼
                    ┌─────────┐
                    │ TEST    │
                    └────┬────┘
                         │
                  ┌──────▼──────┐
                  │  WORKING?   │
                  └───┬─────┬───┘
                    YES│     │NO
                       │     │
                       ▼     ▼
                    SHIP   DEBUG
                             │
                ┌────────────▼────────────┐
                │ Check wiring             │
                │ Check voltage            │
                │ Check baud/protocol      │
                │ Check code               │
                │ Check assumptions        │
                └────────────┬────────────┘
                             │
                             └──────→ TEST

Rule: Don't guess the bug. Measure it.

06 // LEARNING QUEUE

[██████████░░░░░░░░░░]  C Programming
[███████░░░░░░░░░░░░░]  Embedded C
[██████░░░░░░░░░░░░░░]  Microcontrollers
[█████░░░░░░░░░░░░░░░]  Communication Protocols
[█████░░░░░░░░░░░░░░░]  IoT Systems
[████░░░░░░░░░░░░░░░░]  PCB Design
[███░░░░░░░░░░░░░░░░░]  Embedded AI

Progress bars represent learning focus, not formal skill ratings.

07 // ENGINEERING PRINCIPLES

01  Understand before copying.
02  Test hardware before blaming software.
03  Read the datasheet.
04  Use the serial monitor as a microscope.
05  Keep experiments reproducible.
06  Document the failure, not only the success.
07  Build small → test → improve → scale.

08 // 8085 → ESP32 → VEGA

One of the things I enjoy is seeing how the same fundamentals appear at
different levels:

8085
 │
 ├── Registers
 ├── Memory
 └── Instructions
       │
       ▼
   Microcontrollers
       │
       ├── GPIO
       ├── Timers
       ├── UART
       └── Interrupts
              │
              ▼
        Connected Systems
              │
              ├── Sensors
              ├── IoT
              ├── Data
              └── Automation

09 // GITHUB ACTIVITY

::: {align="center"}
<img src="https://github-readme-stats.vercel.app/api?username=devamitra-b&show_icons=true&hide_border=true&theme=transparent" width="48%"/>{=html}
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=devamitra-b&layout=compact&hide_border=true&theme=transparent" width="38%"/>{=html}
:::

10 // FIND ME

::: {align="center"}

:::

::: {align="center"}

┌─────────────────────────────────────────────┐
│                                             │
│   LEARN HARDWARE.                           │
│   WRITE CODE.                               │
│   DEBUG FEARLESSLY.                         │
│   BUILD SOMETHING REAL.                     │
│                                             │
└─────────────────────────────────────────────┘

SYSTEM STATUS: BUILDING

:::
