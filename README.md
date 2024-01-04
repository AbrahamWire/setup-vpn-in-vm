<h1>Setting up a Virtual Private Network (VPN) within Azure Virtual Machine (VM)</h1>
<p>I'll be showing you how to set up and observe how a VPN operates within a Vitrtual Machine.</p>

<h1>Environments and technologies used</h1>

- Microsoft Azure
- Windows PC
- Remote Desktop Connection
- Proton VPN

<h2>Operating Systems used</h2>
Windows 10

-----

<h1>Part 1: Find out what is your IP address</h1>

<p>Visit https://www.whatismyipaddress.com/ and take a note of it plus your city.</p>

![VPN](https://github.com/AbrahamWire/setup-vpn-in-vm/assets/155400161/3d746d14-3c48-428c-981d-9b358e4d3f99)

<h1>Part 2: Create a VM within Azure and check the IP address</h1>

<p>Create a windows 10 VM in Azure and make sure to choose another region outside of your own.</p>

![VPN2](https://github.com/AbrahamWire/setup-vpn-in-vm/assets/155400161/ba0124e9-80fd-4c8f-acbc-686bc4e60293)

<p>Log into the VM and visit https://www.whatismyipaddress.com/ and take note of what you see</p>

![VPN3](https://github.com/AbrahamWire/setup-vpn-in-vm/assets/155400161/5e2515e7-afbc-46b7-a17a-950bae662df9)

<h1>Part 3: Sign up for Proton VPN and download it on your VM</h1>

<p>Back on your own computer sign up for Proton VPN</p>

<p>Once you sign up go back to your VM and download Proton VPN and sign in with the account you just created.</p>

<h1>Part 4: Choose a region and check IP Address</h1>

<p>Once you have the VPN running choose whichever the free option is and let it do its thing</p>

![VPN4](https://github.com/AbrahamWire/setup-vpn-in-vm/assets/155400161/0baafcc8-3332-4622-87f7-b5ef2e31145a)

![VPN5](https://github.com/AbrahamWire/setup-vpn-in-vm/assets/155400161/6d65689d-7081-4adb-b1fb-0f05269e47ec)

<p>Go to https://www.whatismyipaddress.com/ again and notice the changes</p>

![VPN7](https://github.com/AbrahamWire/setup-vpn-in-vm/assets/155400161/01bdcb58-9a83-4f1f-87da-522b08a468ec)

<p>Now visit whichever website you choose and notice the differences there!</p>

![VPN6](https://github.com/AbrahamWire/setup-vpn-in-vm/assets/155400161/4a9c072f-f995-4f73-ae0a-dd3ab153c2a8)

<h1>Conclusion</h1>
<p>And there you go! if you wrote down all 3 IP addresses and regions you should have 3 different IP addresses between yours, the VM and the VPN! Continue to mess around with it or do more research! Have a good one!</p>
