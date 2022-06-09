# Institutes-Network-Designing

<h1>Campus Visited</h1>

![Screenshot 2022-06-08 at 9 18 12 PM](https://user-images.githubusercontent.com/91361896/172660915-b5b46a11-558a-4f06-8264-33704ec68e99.png)

![Screenshot 2022-06-08 at 9 18 21 PM](https://user-images.githubusercontent.com/91361896/172660934-aecf8b31-978f-4ec7-b0a8-e569e649d370.png)

<h1>Present Architecture</h1>

![Screenshot 2022-06-08 at 9 19 06 PM](https://user-images.githubusercontent.com/91361896/172661086-b1bb46c0-ca0c-4f1d-80e8-42246a7b80c4.png)

![Screenshot 2022-06-08 at 9 19 29 PM](https://user-images.githubusercontent.com/91361896/172661152-808fd090-8330-489e-bf04-29168cd0aea3.png)

<h2>Routers Used</h2>

<li>Juniper M10iE Router</li>

![Screenshot 2022-06-08 at 9 20 44 PM](https://user-images.githubusercontent.com/91361896/172661429-f3c0c8c8-dc2c-46a1-a2a4-698fb61ccf24.png)

<li>D-Link DIR-816 Wireless Router</li>

![Screenshot 2022-06-08 at 9 20 50 PM](https://user-images.githubusercontent.com/91361896/172661462-41386979-a6a1-4200-9c8f-852ebf781ff7.png)

<h2>Switches Used</h2>

<li>TP-LINK (TL-R480T+) Load Balancer</li>

![Screenshot 2022-06-08 at 9 22 00 PM](https://user-images.githubusercontent.com/91361896/172661751-15fb44eb-4585-459c-87ed-1c2a81ffe904.png)

<li>D-LINK Smart-Pro Switch</li>

![Screenshot 2022-06-08 at 9 22 05 PM](https://user-images.githubusercontent.com/91361896/172661793-2aa921e1-77fe-4e69-b772-37a5d81bef67.png)

<h2>Servers Used</h2>

<li>Library Server</li>

![Screenshot 2022-06-08 at 9 22 35 PM](https://user-images.githubusercontent.com/91361896/172662002-5acf465a-d475-4cde-978e-d95398e35329.png)

<li>Journal Server</li>

![Screenshot 2022-06-08 at 9 22 40 PM](https://user-images.githubusercontent.com/91361896/172662041-a6db2dec-9b4b-4efd-b058-52bc26329499.png)

<h1>About Survey</h1>

❖ No specific topology is being used.
❖ No firewall. It is Dependent on NIC for monitoring traffic.
❖ No AAA server has been used.
❖ Local DNS server has been used.
❖ 600 devices excluding Wi-Fi.
❖ 60-70 D-Link switches.

<h1>Gaps Identified</h1>

❖ No firewall for outbound traffic
❖ No antivirus
❖ No topology
❖ IP address is statically assigned to routers 
❖ Single ISP provides all the connections

<h1>Our Proposed model</h1>

![fullNet1](https://user-images.githubusercontent.com/91361896/172781642-00dc76d3-bad0-478b-908c-501612f1fdfc.PNG)

<h2>We Added</h2>
<li>AAA Server</li>
<li>Firewall</li>
<li>MultiLayer Switch</li>
<li>EIGRP enabled Network</li>
<li>Access Points</li>
