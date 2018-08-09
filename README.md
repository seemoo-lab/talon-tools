# Talon Tools: Practical IEEE 802.11ad Research
<img src="logos/talon.png" align="right" width=45% height=45%/>
The Talon Tools project consolidates a set of software tools for practical research with commodity IEEE 802.11ad devices. It bases on TP-Link's Talon AD7200, which is the first wireless router that supports the IEEE 802.11ad standard and was released in 2016. Using this platform allows to investigate various aspects of 60 GHz millimeter-wave communication in realistic on-site experiments. With our framework, we support various kinds of experiments and evaluations performed with multiple routers in arbitrary environments.

## Usage Report and Statistics
Our Talon Tools framework is a research project that we share with the community so that others can reproduce our results and benefit from it. We aim to record basic statistics on where and for what purpose our tools are used. Please consider filling our short [usage report](https://goo.gl/forms/QKU0ME98f2gYhs5B2) that will only take a few minutes. You can also use this to report your publications. Doing so, you support us to keep track on the usage and allow us to continuously refine our work. 

## Contents
* [lede-ad7200](https://github.com/seemoo-lab/lede-ad7200): LEDE environment ported to support TP-Link TALON AD7200 devices.
* [nexmon-arc](https://github.com/seemoo-lab/nexmon-arc): The nexmon C-based firmware patching framework adapted for the ARC architecture.
* [sector-patterns](https://github.com/seemoo-lab/talon-sector-patterns): Measured Antenna Sector Pattern from our CoNEXT 2017 paper.

## Getting Started
Please follow our [getting started](GettingStarted.md) tutorial to establish your first wireless gigabit link.
For individual documentations, consider the involved projects directly: For example, you can build your own LEDE image with [lede-ad7200](https://github.com/seemoo-lab/lede-ad7200)
and create custom patches for the wireless chip with [nexmon-arc](https://github.com/seemoo-lab/nexmon-arc). If you just want to use our antenna patterns in your evaluations, check out the [sector-patterns](https://github.com/seemoo-lab/talon-sector-patterns) repository. For detailed information on our platform and the framework, please consider our papers at CoNEXT '17 and MobiCom '18 (see below).

## WARNING
This software might damage your hardware and may void your hardware’s warranty. Use our tools at your risk and responsibility.

## Related projects
* [LEDE](https://lede-project.org): The “Linux Embedded Development Environment” is a Linux operating system based on OpenWrt.
* [Nexmon](https://nexmon.org): The C-based Firmware Patching Framework for Broadcom/Cypress WiFi Chips.

## Our papers using Talon Tools
* Daniel Steinmetzer, Milan Stute, and Matthias Hollick.
  **TPy: A Lightweight Framework for Agile Distributed Network Experiments.** 
  *12th International Workshop on Wireless Network Testbeds, Experimental evaluation & CHaracterization (WiNTECH ’18)*, October 2018, New Delhi, India.
* Daniel Steinmetzer, Saad Ahmad, Nikolaos Anagnostopoulos, Matthias Hollick, and Stefan Katzenbeisser.
  **Authenticating the Sector Sweep to Protect Against Beam-Stealing Attacks in IEEE 802.11ad Networks.**
  *2nd ACM Workshop on Millimeter Wave Networks and Sensing Systems (mmNets ’18)*, November 2018, New Delhi, India.
* Joan Palacios, Daniel Steinmetzer, Adrian Loch, Matthias Hollick, and Joerg Widmer.
  **Adaptive Codebook Optimization for Beam Training on Off-the-Shelf IEEE 802.11ad Devices.**
  *24th Annual International Conference on Mobile Computing and Networking (MobiCom ’18)*, October 2018, New Delhi, India.
* Daniel Steinmetzer, Yimin Yuan, and Matthias Hollick.
  **Beam-Stealing: Intercepting the Sector Sweep to Launch Man-in-the-Middle Attacks on Wireless IEEE 802.11ad Networks.**
  *11th ACM Conference on Security and Privacy in Wireless and Mobile Networks (WiSec ’18)*, June 2018, Stockholm, Sweden.
* Swetank Kumar Saha, Hany Assasa, Adrian Loch, Naveen Muralidhar Prakash, Roshan Shyamsunder, Shivang Aggarwal, Daniel Steinmetzer, Dimitrios Koutsonikolas, Joerg Widmer, and Matthias Hollick.
  **Fast and Infuriating : Performance and Pitfalls of 60 GHz WLANs Based on Consumer-Grade Hardware.** 
  *15th International Conference on Sensing, Communication, and Networking (SECON ’18)*, June 2018, Hong Kong.
* Guillermo Bielsa, Joan Palacios, Adrian Loch, Daniel Steinmetzer, Paolo Casari, and Joerg Widmer.
  **Indoor Localization Using Commercial Off-The-Shelf 60 GHz Access Points.**
  *IEEE International Conference on Computer Communications (INFOCOM ’18)*, April 2018, Honolulu, HI, USA.
* Daniel Steinmetzer, Daniel Wegemer, and Matthias Hollick.
  **A Practical IEEE 802.11ad Research Platform: The Hidden Potential of Off-the-Shelf Devices**.
  *3rd NSF Millimeter-Wave Research Coordination Network (RCN) Workshop*, January 2018, Tucson, AZ, USA.
* Daniel Steinmetzer, Daniel Wegemer, Matthias Schulz, Joerg Widmer, Matthias Hollick. 
  **Compressive Millimeter-Wave Sector Selection in Off-the-Shelf IEEE 802.11ad Devices**.
  Accepted for publication in *Proceedings of the 13th International Conference on emerging Networking EXperiments and Technologies (CoNEXT 2017)*, December 2017, Seoul/Incheon, South Korea.
* Daniel Steinmetzer, Adrian Loch, Amanda García-García, Joerg Widmer, Matthias Hollick. 
  **Mitigating Lateral Interference: Adaptive Beam Switching for Robust Millimeter-Wave Networks**.
  *1st ACM Workshop on Millimeter Wave Networks and Sensing Systems (mmNets 2017)*, October 2017, Snowbird, Utah, USA.

  [Get references as bibtex file](talon-tools.bib)

## Reference our project
Any use of the Software which results in an academic publication or other publication which includes a bibliography must include citations to the Talon Tools project and probably one of our papers depending on the code you use. Find all references in our [bibtex file](talon-tools.bib). The project should be cited as follows:

```
@electronic{talon-tools:project,
	author = {Steinmetzer, Daniel and Wegemer, Daniel and Hollick, Matthias},
	title = {Talon Tools: The Framework for Practical IEEE 802.11ad Research},
	url = {https://seemoo.de/talon-tools/},
	year = {2018}
}
```

## Give us Feedback
We want to learn how people use our platform and what aspects we might improve. Please report any issues or comments using the bug-tracker and do not hesitate to approach us via e-mail.

## Contact
* [Daniel Steinmetzer](https://seemoo.tu-darmstadt.de/dsteinmetzer) <<dsteinmetzer@seemoo.tu-darmstadt.de>>
* Daniel Wegemer <<dwegemer@seemoo.tu-darmstadt.de>>

## Powered By
<a href="https://www.seemoo.tu-darmstadt.de">![SEEMOO logo](logos/seemoo.png)</a> &nbsp;
<a href="https://www.nicer.tu-darmstadt.de">![NICER logo](logos/nicer.png)</a> &nbsp;
<a href="https://www.crossing.tu-darmstadt.de">![CROSSING logo](logos/crossing.jpg)</a>&nbsp;
<a href="https://www.crisp-da.de">![CRSIP logo](logos/crisp.jpg)</a>&nbsp;
<a href="http://www.maki.tu-darmstadt.de/">![MAKI logo](logos/maki.png)</a> &nbsp;
<a href="https://www.cysec.tu-darmstadt.de">![CYSEC logo](logos/cysec.jpg)</a>&nbsp;
<a href="https://www.tu-darmstadt.de/index.en.jsp">![TU Darmstadt logo](logos/tudarmstadt.png)</a>&nbsp;
