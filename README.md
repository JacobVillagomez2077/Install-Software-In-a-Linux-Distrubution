<p align="center">
<img src="https://images.credly.com/size/340x340/images/0bf0f2da-a699-4c82-82e2-56dcf1f2e1c7/image.png"/>
</p>

<h1>Install Software In a Linux Distrubution Lab 1 & 2</h1>
This tutorial outlines the Google Cybersecuirty Lab 1 & 2 and a break down of how to install software in a linux distrubtion.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- {If you have a Coursera account and are currently enrolled in the cert you may follow along}
- Coursera VM Lab

<h2>Operating Systems Used </h2>

- Windows 11</b>

<h2> Objectives</h2>

- Ensure that APT is installed  
- Install and uninstall the Suricata application
- Install the tcpdump application
- List the installed applications
- Reinstall the Suricata application

<h2>Steps</h2>

<p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/03201318-fe38-4286-ac12-d5b0a6299fb7"/>
</p>
<p>
First you need to check that the APT application is installed then you can use it to manage the application all you have to do is type apt in the command line then press enter.
</p>
<br /> 


<p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/eaad2b8c-30a0-4d67-8359-1f4b9ec36cd5"/>
</p>
<p>
Next we are going to install Suricata application go to the command line and type sudo apt install suricata.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/8f585b2b-7dba-4c72-a8ee-24de2a6e4e21"/>
</p>
<p>
Next you need to type in y for yes then suricata will install and show a progression bar on the bottom left.
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/d10bc1a4-7be7-4ec8-8d58-8c99b656faff"/>
</p>
<p>
Next once the progression bar say 100%. We need to then see if suricata is installed type in suricata in the command line.
</p>
<br />
<p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/7c971806-7321-495c-87a3-503844e02e99"/>
</p>
If you see the commands for suricata as shown in the image above then suricata is installed.
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/d7eefd34-7d9b-4c72-b297-15c803b9195d"/>
</p>
Next we are going to uninstall suricata type in sudo apt remove suricata
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/45e87889-23be-4a6f-a7bf-75701daf8b5b"/>
</p>
Next you need to type in y to allow suricata to be uninstalled
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/71da576b-4acd-45fe-8e71-4f25bd68cdaa"/>
</p>
Next type suricata in the command line it should say the following "No such file or directory"
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/968f748a-ff89-437b-9148-12db54adca9b"/>
</p>
Next we are going to install the tcpdump application type in sudo apt install tcpdump in the command line
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/0ab133dd-d9e6-4877-8c6e-668c0645075b"/>
</p>
Next we are going to list out the installed applications type apt list --installed in the command line
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/43c3afbb-723b-4a5a-be4b-830e6dea570f"/>
</p>
You can see tcpdump is installed in the image above
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/694ecf79-cd90-4e29-b104-034c13f673e9"/>
</p>
Next we are going to install suricata again type in sudo apt install suricata in the command line 
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/d6cb585d-86ab-4f72-8671-d87fec522bdc"/>
</p>
Type y for yes again to allow installation
</p>
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/15340c44-ae62-486d-b9eb-544d41617150"/>
</p>
We can see the list of all the applications type apt list --installed one more time in the command line
<img src="https://github.com/Jacobvillagomez1/Install-Software-In-a-Linux-Distrubution/assets/143027686/758824f2-e684-4beb-890f-7046b93b81a2"/>
</p>


