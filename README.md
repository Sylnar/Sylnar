<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=200&color=gradient&customColorList=0,2,6&text=Sylnar&fontSize=60&fontColor=00D4AA&fontAlignY=55&desc=PCIe%20Endpoint%20Engineering%20%E2%80%A2%20FPGA%20Firmware%20%E2%80%A2%20Windows%20Internals&descSize=14&descAlignY=78&descColor=6E7681&animation=fadeIn" width="100%"/>

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1200&color=00D4AA&center=true&vCenter=true&multiline=false&width=600&lines=Building+real+PCIe+endpoints+on+Artix-7+FPGAs;SystemVerilog+%7C+Vivado+%7C+Windows+Internals;C%23+%2F+.NET+8+%2F+Avalonia+desktop+tooling;Firmware+that+the+OS+believes+is+real+silicon" alt="Typing SVG"/>

<br/>

[![Followers](https://img.shields.io/github/followers/Sylnar?label=Followers&style=for-the-badge&logo=github&color=00D4AA&labelColor=0D1117)](https://github.com/Sylnar?tab=followers)
[![Stars](https://img.shields.io/github/stars/Sylnar?label=Stars&style=for-the-badge&logo=github&color=00D4AA&labelColor=0D1117)](https://github.com/Sylnar)
[![Focus](https://img.shields.io/badge/PCIe_%26_FPGA-Engineering-00D4AA?style=for-the-badge&labelColor=0D1117)](https://github.com/Sylnar)
[![Website](https://img.shields.io/badge/sylnar.com-00D4AA?style=for-the-badge&logo=internetarchive&logoColor=0D1117&labelColor=0D1117)](https://sylnar.com)

</div>

---

<br/>

### About

Hardware and firmware engineer designing PCIe endpoints that the host OS treats as real silicon. The work starts at the transistor boundary: RTL written in SystemVerilog, synthesized through Vivado, flashed to Artix-7 FPGAs.

**What I build:**

- Full PCIe config-space emulation including capability chains, BAR decode, and AHCI register sets
- C# / .NET 8 / Avalonia desktop apps with native JTAG and kernel driver interop
- Windows storage and kernel subsystem analysis to validate firmware correctness
- SystemVerilog AHCI and ATA engines with DMA descriptor rings

<br clear="right"/>

<br/>

---

### Projects

<table width="100%">
<tr>
<td width="50%" valign="top">
<h4>
  <img src="https://img.shields.io/badge/N-0D1117?style=flat-square&color=00D4AA&logoColor=0D1117" />
  NexusForge
</h4>

FPGA board management application built with Avalonia UI on .NET 8. Detects FPGA boards over JTAG via CH347, reads silicon DNA, and flashes firmware through an embedded OpenOCD instance. Ships as a single-file self-contained Windows binary with all drivers and tools bundled as encrypted resources.

<br/>

![C#](https://img.shields.io/badge/C%23-161B22?style=flat-square&logo=csharp&logoColor=00D4AA)
![Avalonia](https://img.shields.io/badge/Avalonia-161B22?style=flat-square&logoColor=00D4AA)
![.NET 8](https://img.shields.io/badge/.NET_8-161B22?style=flat-square&logo=dotnet&logoColor=00D4AA)

[![View](https://img.shields.io/badge/View_Repository-00D4AA?style=flat-square&logo=github&logoColor=0D1117)](https://github.com/Sylnar/NexusForge)

</td>
<td width="50%" valign="top">
<h4>
  <img src="https://img.shields.io/badge/L-0D1117?style=flat-square&color=00A88A&logoColor=0D1117" />
  LeechCore (fork)
</h4>

Fork of the open-source physical memory acquisition library with a targeted reliability fix for FPGA-based PCIe DMA hardware over FT601 USB. Eliminates intermittent device-not-found failures caused by read-pipe desync on cold opens, without touching the data path or adding re-init overhead.

<br/>

![C](https://img.shields.io/badge/C-161B22?style=flat-square&logo=c&logoColor=00D4AA)
![PCIe](https://img.shields.io/badge/PCIe_DMA-161B22?style=flat-square&logoColor=00D4AA)
![FPGA](https://img.shields.io/badge/FPGA-161B22?style=flat-square&logoColor=00D4AA)

[![View](https://img.shields.io/badge/View_Repository-00A88A?style=flat-square&logo=github&logoColor=0D1117)](https://github.com/Sylnar/LeechCore)

</td>
</tr>
</table>

---

### Tech Stack

<br/>

<div align="center">

**Hardware & Firmware**

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-0D1117?style=for-the-badge&logoColor=00D4AA&labelColor=0D1117&color=161B22)
![Vivado](https://img.shields.io/badge/Vivado_2022.2-0D1117?style=for-the-badge&labelColor=0D1117&color=161B22&logoColor=00D4AA)
![Artix-7](https://img.shields.io/badge/Artix--7_FPGA-0D1117?style=for-the-badge&labelColor=0D1117&color=161B22&logoColor=00D4AA)
![PCIe](https://img.shields.io/badge/PCIe_Endpoint-0D1117?style=for-the-badge&labelColor=0D1117&color=161B22&logoColor=00D4AA)

<br/>

**Software & Tooling**

![C#](https://img.shields.io/badge/C%23-0D1117?style=for-the-badge&logo=csharp&logoColor=00D4AA&color=161B22)
![.NET 8](https://img.shields.io/badge/.NET_8-0D1117?style=for-the-badge&logo=dotnet&logoColor=00D4AA&color=161B22)
![Avalonia](https://img.shields.io/badge/Avalonia_UI-0D1117?style=for-the-badge&logoColor=00D4AA&color=161B22)
![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00D4AA&color=161B22)
![PowerShell](https://img.shields.io/badge/PowerShell-0D1117?style=for-the-badge&logo=powershell&logoColor=00D4AA&color=161B22)
![Windows](https://img.shields.io/badge/Windows_Internals-0D1117?style=for-the-badge&logo=windows&logoColor=00D4AA&color=161B22)

</div>

<br/>

---

### GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Sylnar&show_icons=true&theme=dark&bg_color=0D1117&title_color=00D4AA&icon_color=00D4AA&text_color=6E7681&border_color=161B22&hide_border=false" width="48%"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sylnar&layout=compact&theme=dark&bg_color=0D1117&title_color=00D4AA&text_color=6E7681&border_color=161B22&hide_border=false" width="42%"/>

</div>

<br/>

---

<br/>

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Sylnar&color=00D4AA&style=for-the-badge&label=PROFILE+VIEWS&labelColor=0D1117)

<br/><br/>

<sub>Releases are unsigned. SmartScreen will warn on first launch. Source is available — build from source if preferred.</sub>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=80&color=gradient&customColorList=0,2,6&section=footer" width="100%"/>

</div>
