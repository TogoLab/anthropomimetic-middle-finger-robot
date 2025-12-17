# Anthropomimetic Middle Finger Robot

🌍 English version (this page)  
📘 [Japanese](./README.md)

---

## Overview

![Anthropomimetic Middle Finger Robot](overview.png)

This repository provides **open-hardware design data for a robotic finger that mimics the anatomical structure of the human middle finger**.

The project is designed for the following purposes:
- Comparison between anthropomimetic (biological) joint mechanisms and conventional robotic (revolute) joints
- Understanding of human anatomical structures (bones and joints)
- Educational and hands-on learning activities

This robot **does not use a microcontroller or any software**.  
It operates using only a servo motor, a servo tester, and batteries.

As a result, the system is easy to handle even for junior high and high school students with little or no prior experience in manufacturing or robotics.

For those who find it difficult to prepare parts, would like hands-on guidance, or have limited resources, hands-on workshops using this robot kit are offered through:
- The *Takumi Girl Project* at The University of Electro-Communications (for junior high and high school girl students in Japan)
  http://www.ge.uec.ac.jp  
- The *Spring Seminar* at the Brain and Life Science Center (for high school students in Japan)
  http://blsc.xsrv.jp/

At the Togo Laboratory, we further extend this approach to develop anthropomimetic robots for various body parts.  
If you find this project interesting, we warmly welcome you to join the Togo Laboratory.

---

## Features

- Two joint models: an anthropomimetic (biological) joint model and a revolute (robotic) joint model
- Reproduction of human finger anatomy from the distal phalanx to the metacarpal
- STL files for 3D printing and editable CAD data (STEP)
- Simple structure designed for educational use
- Software-free, fully hardware-based system

---

## Repository Structure

```
cad/        CAD data (STEP, F3D)
stl/        STL files for 3D printing
docs/       Assembly manuals
licenses/   License-related files
```

---

## Bill of Materials (BOM)

A list of required components is available here:

- [Bill of Materials (BOM)](./BOM_EN.md)

*This project is intended for educational use.  
Equivalent or alternative components may be used without issue.*

---

## Preparation

### 3D Printing of Plastic Parts

The parts have been tested using a **Bambu Lab A1 mini**.
Recommended printing parameters are as follows:

| Parameter        | Value                 |
| ---------------- | --------------------- |
| Filament         | Bambu Lab PLA Basic   |
| Layer height     | 0.2 mm                |
| Infill density   | 15 %                  |
| Infill pattern   | Grid                  |
| Nozzle diameter  | 0.4 mm                |

### Ligament Preparation

Ligaments are made by crocheting PE braided wire.  
Please refer to tutorial videos such as the following:

- https://youtu.be/j-NHvQiJupI

A **1 mm crochet hook** is used in our implementation.  
Secure the wire ends by tying knots or lightly melting them with a lighter.

---

## Assembly

For detailed assembly instructions, please refer to the following manual:

- Assembly manual: `docs/manual_en.pdf`

*This manual is a modified version of the one distributed during hands-on workshops.  
In the open-hardware version, laboratory and university logos have been removed from the base part.*

---

## License

Multiple licenses apply to different parts of this repository.  
Please make sure to check the license associated with each file before use.

- **Bone (human anatomy) models**  
  - `/cad/finger_*`, `/stl/finger_*`  
  - Creative Commons Attribution-ShareAlike 2.1 Japan (CC BY-SA 2.1 JP)  
  - Original data:  [BodyParts3D / Life Science Integrated Database Center](https://lifesciencedb.jp/bp3d/)

- **Original design parts (base, pulleys, etc.)**  
  - `/cad/base_*`, `/stl/base_*`  
  - Creative Commons Attribution 4.0 International (CC BY 4.0)

- **Assembly manuals (PDF)**  
  - © Togo Laboratory, All Rights Reserved

For details, see the `LICENSE` file and the contents of the `licenses/` directory.

*Laboratory logos, university logos, and names included in this repository are not covered by the above licenses.  
Separate permission is required for their use.*

---

## Notes and Disclaimer

- This data is provided for educational and research purposes.
- Use, modification, and redistribution are performed at your own risk.
- Be careful of pinch points and moving parts during operation.
- The authors and affiliated institutions assume no responsibility for any damage or loss resulting from the use of this repository.

---

## Author and Contact

Shunta Togo  

Associate Professor  
Department of Mechanical and Intelligent Systems Engineering  
Graduate School of Informatics and Engineering  
The University of Electro-Communications  

- [ResearchMap](https://researchmap.jp/shuntatogo?lang=en)  
- [Togo Laboratory](http://www.hi.mce.uec.ac.jp/togolab/)  
- [X (Twitter)](https://twitter.com/togo_lab/)  
- [Instagram](https://www.instagram.com/togolab_uec/)  
- [YouTube](https://www.youtube.com/channel/UC10spcvW8-pCTLKy5rrDHyw)

For questions or bug reports, please use GitHub Issues or contact:  
s.togo[at]uec.ac.jp

Support for educational and research activities at the Togo Laboratory is also welcome.  
- https://www.uec.ac.jp/kikin/archives/fund/togolab