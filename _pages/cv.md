---
layout: archive
# title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<div class="full">
{% capture notice-2 %}
Work experience  <span style="color:#b5b5b5;font-size: 15px">Feb 2021 - Present</span>
======

* #### Senior Engineer - QA <span style="color:#b5b5b5;font-size: 12px">Jan 2024 - Present</span>
  * ###### _TCU board automation_ <span style="color:#b5b5b5;font-size: 11px">Feb 2024 - Present</span>

    Responsible for pytest framework plugin development based on requirement for the TCU testing. Automated TP-Link smart device using Kasa API.
    
    Leading automation team, where I am responsible for strategic planning and prioritizing automation tasks.
    
    Reviewing and approving peer pull requests. Automating and executing test cases. Qualifying release builds through sanity testing, followed by screening regression and full regression testing. Conducting MVP tests to validate the board and build for customer shipment. Collaborating with the DevOps team to develop and optimize the automation pipeline.

    Designed and integrated a custom DUT metadata(like SW version, CPU details...) widget into the Allure report's Overview page by programmatically modifying the generated HTML using BeautifulSoup (Python), significantly enhancing report readability and traceability for stakeholders during test result analysis.

    TCU - Trusted Control/Compute Unit.
    The Axiado AX3000/AX2000 SoC with built-in AI provides the industry’s most robust, hardware-anchored solution to detect and defend against ransomware and cyberattacks in cloud datacenters, 5G networks, and network switches.

    Connection:
    Windows machine -serial-conection-> TCU -pcie-connection-> Linux host/Server

    From automation server SSH to the Windows machine and then take the serial connection to the TCU and do our testing.

  * ###### _Network Test Platform automation_ <span style="color:#b5b5b5;font-size: 11px">Jan 2024 - Jan 2024</span>

    Developed library for automating the JDSU MTS-5800 Handheld Network Tester tool from ground up using Python. JDSU stands for JDS Uniphase Corporation, which is now known as Viavi Solutions Inc. Viavi Solutions is a company that manufactures network test, measurement, and assurance technology.

    E2E automation of the tool from traffic configuration to statistics collection using CLI. Traffics like Layer 2 to Layer 4 and Application traffics.

    Used Netmiko module for CLI conenction to the device.

* #### Senior Software Engineer <span style="color:#b5b5b5;font-size: 12px">June 2023 - Dec 2023</span>
  * ###### _Cisco Cyber Vision_ <span style="color:#b5b5b5;font-size: 11px">June 2023 - Dec 2023</span>

    Cisco Cyber Vision enables organizations to ensure the continuity, resilience, and safety of their industrial operations by providing continuous visibility into their Industrial Control Systems (ICS) to understand their security posture, improve their industrial networks efficiency, and extend IT security to their industrial operations.
    
    I am with the team of 3 members responsible for the Scale and Stress testing.

    Automation includes CV REST APIs and CLIs in pyATS framework

* #### Software Engineer <span style="color:#b5b5b5;font-size: 12px">June 2021 - May 2023</span>
  * ###### _CURWB - Cisco Ultra Reliable Wireless Backhaul (formerly Fluidmesh)_ <span style="color:#b5b5b5;font-size: 11px">Apr 2022 - May 2023</span>

    Cisco Ultra-Reliable Wireless Backhaul is a wireless technology that enables you to connect moving assets or extend your network where running fiber isn't feasible or affordable. It delivers up to a 7.8-Gbps data rate, 99.995% availability, less than 10-ms latency, and zero packet loss with seamless handoffs.
    
    I am with the team of 3 members responsible for the Solution testing of the Magnum and Jeroboam product.

    Automated the end to end Solution requirement of the product by configuring the device, passing the traffic streams, and performing the test scenarios(Failover and Failback scenarios).

    Handled different Layer Suites(L2, L3) and Verticals (rails, mining, windfarm) based on the customer deployment scenarios in the single script file. Wireless client impact on REP switch convergence validation in both manual and automation.

    GG - Global Gateway

    ME - Mesh end
    
    MP - Mesh point
    
    L2 topology : ME -> MP(comm tower) -> MP(backhaul) -> MP(vehicle).
    
    L3 topology : GG -> ME -> MP(backhaul) -> MP(vehicle)

    Automated the Ixia traffic profiles based on the requirement of the test scenarios.

    Pushed the testsuite end results to the DB and notified the WebEx teams with testsuite summary table with all the traffic statistics.

    Point to Point link distance testing. Configuring the radio with the distance (2kms, 3kms, 4kms, 6kms, 8kms, 10kms, 15kms, 20kms, 32.5kms) and getting the negotiated rate between the Point to Point radios and passing the 60% of the negotiated rate and verifying the results.

    Automation includes API and CLI using pyATS framework in Python.

  * ###### _Profinet traffic simulator_  <span style="color:#b5b5b5;font-size: 11px">Mar 2022</span>

    Developed a CLI app to simulate the Profinet traffic in Golang.

    On the receiver end, added the feature to calculate the Packet Loss and Packet Loss duration. 

  * ###### _Cisco SD-Access Fabric Wireless_  <span style="color:#b5b5b5;font-size: 11px">Nov 2021 - Feb 2022</span>

    SD-Access is Cisco’s next-generation enterprise networking access solution, designed to offer integrated security, segmentation, and
elastic service rollouts via a fabric-based infrastructure.

    With the team of 3 members responsible for testing the campus Wireless connectivity.

    Automated the Device onboarding scenario in the Cisco DNAC, image activation, providing Wireless connectivity and verifying the Segmentation (SGT).

    Topology : DNAC -> WLC -> AP -> Wireless clients

    Automation includes API, GUI and CLI using pyATS framework in Python.
  
  * ###### _SCADA t104_ <span style="color:#b5b5b5;font-size: 11px">Oct 2021</span>

    SCADA t104 (IEC 60870-5-104) protocol operates over IP interfaces.

    Simulated the t104 communication between the SCADA Master and SCADA Slave.

    Used Scapy to create the Packet from the ground up in Python.

    Developed the Python libraries from scratch for creating and parsing the Packets.

  * ###### _Fluidmesh_ (now part of Cisco) <span style="color:#b5b5b5;font-size: 11px">Jun 2021 - Sep 2021</span>

    Automated the Solution requirement scenarios of the Fluidmesh product.

    Automation includes configuring the Fluidmesh devices to form the mesh, passing the traffic and verifying the test scenarios in Python. 

    Worked on Dashboard API automation and device CLI automation.

* #### Project Intern <span style="color:#b5b5b5;font-size: 12px">Feb 2021 - May 2021</span>
  * ###### _Astral Cloud QA_

    I am with the team of 6 members responsible for testing the basic GUI functionality.

    Manually tested the network device registration functionality in the Astral Mobile APP and Web APP.


Education History
======

* #### Government College of Technology, Coimbatore <span style="color:#b5b5b5;font-size: 12px">Aug 2017 - Mar 2021</span>

  B.E. (EEE) <span style="color:#b5b5b5;font-size: 11px">CGPA 8 out of 10</span>

    


Main Skills
======
* Python
* pyATS
* Golang
* REST API, CLI, GUI testing (Automation and Manual)
* pytest
* Django basics

Tools
======

* Linux
* Git
* Postman
* Wireshark
* Scapy
* IxNetwork
* Jenkins

Protocols
======

* DHCP
* ARP
* DNS
* WPA/WPA2-PSK
* Trustsec
* TCP/UDP


Certifications
======

<div class="badgr-badge" style="font-family: Helvetica, Roboto, &quot;Segoe UI&quot;, Calibri, sans-serif;"><a href="https://api.badgr.io/public/assertions/0vHyxfNvSN6rCaYQh9yZZg?identity__email=logsak.12.34%40gmail.com"><img width="120px" height="120px" src="https://api.badgr.io/public/assertions/0vHyxfNvSN6rCaYQh9yZZg/image"></a><p class="badgr-badge-name" style="hyphens: auto; overflow-wrap: break-word; word-wrap: break-word; margin: 0; font-size: 16px; font-weight: 600; font-style: normal; font-stretch: normal; line-height: 1.25; letter-spacing: normal; text-align: left; color: #05012c;">Postman Student Expert</p><p class="badgr-badge-date" style="margin: 0; font-size: 12px; font-style: normal; font-stretch: normal; line-height: 1.67; letter-spacing: normal; text-align: left; color: #555555;"><strong style="font-size: 12px; font-weight: bold; font-style: normal; font-stretch: normal; line-height: 1.67; letter-spacing: normal; text-align: left; color: #000;">Awarded: </strong>7 May 2021</p></div><script async="async" src="https://badgr.com/assets/widgets.bundle.js"></script>
<br>
<div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="70f5f27c-d91d-4dc1-8ec7-134f8ae2403d" data-share-badge-host="https://www.credly.com"></div><script type="text/javascript" async src="//cdn.credly.com/assets/utilities/embed.js"></script>

<div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="0d9d1fe9-b81f-422e-bcb7-a7cde8a14739" data-share-badge-host="https://www.credly.com"></div><script type="text/javascript" async src="//cdn.credly.com/assets/utilities/embed.js"></script>
<br>
<a href="https://coursera.org/share/6f742dcbbedf8f165d0ecfdde8ef0a3d">
<img src="https://user-images.githubusercontent.com/69865283/194739355-474e5a54-706b-4d1e-a156-78cb55f43945.png" alt="Go" width="300" height="200">
</a>

{% endcapture %}

<div class="notice">{{ notice-2 | markdownify }}</div>

</div>