Introduction to Command Prompt and other programs on your device that you may not know about or know how to use! 😊

What we will be going over:

-Command prompt and what it is

-some of the most common command prompt commands, what they do, and how they relate to troubleshooting and your understanding of your device

-We will go over Task Manager and how it is a useful tool for understanding your device and its performance.

-We will go over Device Manager and Control Panel, as these are tools commonly used in troubleshooting as well.

___________________________________________________________________________________________________________________________________________________

Requirements to follow along- 

All of these programs are available on Windows 10 or 11 OS

__________________________________________________________________________________________________________________________________________________
COMMAND PROMPT

So, by the book, the answer to what a command prompt is is the following: a text-based interface where you interact with your computer's operating system by typing commands.

Now I would define it in relation to help desk and IT as a tool under your tool belt that you can use as a system administrator or help desk professional to find symptoms of an issue or the issue at hand. In simpler terms, it is a troubleshooting tool; however, it is not limited to just a troubleshooting tool.

To access the command prompt, all you need to do is press your Windows key and then type "Cmd" and press Enter. However, to run Command Prompt in Administrative mode, you will need to click the option below, open and click "Run as Administrator".

<img width="816" height="435" alt="Screenshot (132)1" src="https://github.com/user-attachments/assets/2bd1e006-0734-4a5b-99e1-0e53fef58c8a" />

Now, here is a list of some of the most common commands or the ones that we will be going over today, and what they do.

-Ping This command is used to test connectivity with websites or IP addresses 

<img width="604" height="248" alt="image" src="https://github.com/user-attachments/assets/d54c27fd-c588-4b39-9305-d759a8542061" />

-Ping -t This is also used to test connectivity with websites or IP addresses; however, it does not stop sending packets.

<img width="608" height="338" alt="image" src="https://github.com/user-attachments/assets/546add90-6485-4582-8572-4948afcba908" />

-Nslookup This command will query a server to find IP addresses or DNS records

<img width="636" height="324" alt="image" src="https://github.com/user-attachments/assets/34462e4b-9bef-4dea-9448-5f18087224d7" />

-ipconfig This command displays your currents ip address and adapter information.

<img width="743" height="710" alt="image" src="https://github.com/user-attachments/assets/9ba72651-4ae4-4c20-b690-7d076dbc23d4" />

-ipconfig /all This command displays any and all adapter information, including gateway, DNS server, DHCP server, MAC address, IP addresses.

<img width="857" height="1017" alt="image" src="https://github.com/user-attachments/assets/2c6eb3a1-a5ee-40c6-8ce1-e862bf618bec" />

-ipconfig /displaydns this does as the name says and displays your dns cache information as in the sites and whatnot that are saved in your DNS cache

<img width="584" height="966" alt="image" src="https://github.com/user-attachments/assets/6d1e4753-5a2e-464b-9007-dd82dabfb163" />

-ipconfig /flushdns This will flush your DNS cache and remove all previously cached routes

<img width="402" height="157" alt="image" src="https://github.com/user-attachments/assets/fddf8d86-9ba7-42cf-a3e5-1a37b46f1428" />

-netstat This will display your active network connections, active ports, and routing tables.

<img width="584" height="572" alt="image" src="https://github.com/user-attachments/assets/b96fe7c3-d866-4bbb-8776-99b38763648e" />

-tracert This command will map the path your packets took to reach their destination over a maximum of 30 hops

<img width="1038" height="639" alt="image" src="https://github.com/user-attachments/assets/12bbe66a-1333-4e8c-b663-f0f91b05e57b" />

Now, all of these commands are useful in their own way, and by following along, I think you may have gained more understanding of your device and what your device does daily. Now, let's go over how you can apply these commands in troubleshooting. 

Now, for example, say a device is not able to surf the internet at all. One of the first things you can check for is running the command ipconfig/all in the command prompt and ensuring all of the network information on the device is correct, meaning the IP address is correct, the DNS server is correct, the default gateway is correct, and the subnet mask is correct. 

Understanding these commands and what they do will allow you to think whenever you're facing an issue, and think about what tools (commands) you know are at your disposal, and can be run to better understand the issue that your network or device is facing. 
___________________________________________________________________________________________________________________________________________________________________

Task Manager- 

 The definition is: A built-in system monitoring and diagnostic tool. It allows you to view all running applications and background processes, and track how much CPU, memory, disk, and network resources your computer is using.

 In relation to help desk and troubleshooting, I define it as a software tool that allows you to view the performance and processes running on your device and manage them. It can allow you to close programs that are frozen or experiencing technical difficulties and restart them. 

 <img width="1080" height="571" alt="image" src="https://github.com/user-attachments/assets/96980ab3-6323-46b4-8fe8-d7214b85a762" />

This is what the performance tab shows you. As you can see, it shows the performance of the device and the utilization of each of the components. It shows the number of processes that the components are running and their speed. 

<img width="1080" height="580" alt="image" src="https://github.com/user-attachments/assets/040a7f79-de72-425a-a60a-177edae6e3e2" />

This tab shows the processes being run by the device and how much utilization each process is using on the device. In this tab, this is where you can close processes that are frozen, or you can find out what processes are using all of your computer's resources. This can be a very valuable tool for troubleshooting a slow computer. 

I would say that the processes and performance tabs are the most important and useful for troubleshooting; however, the startup tab can be useful as well, as it does what its name implies and shows all programs that are set to start running on startup or whenever you turn on your computer or device. 

______________________________________________________________________________________________________________________________________________________________________________________________________________________________

Device Manager- 

The definition is: a component of the Microsoft Windows operating system. It allows users to view and control the hardware attached to the computer.

In relation to the help desk, Device Manager is another tool that allows you to view hardware on or connected to your device. Manage that hardware and the software that comes with that hardware, for example, managing the drivers on your microphone. You can update or check for updates on drivers on your device, and can remove devices or roll back drivers if you please.

<img width="774" height="563" alt="image" src="https://github.com/user-attachments/assets/f50df99e-1362-4803-bd1c-3e632529f6c5" />

<img width="772" height="563" alt="image" src="https://github.com/user-attachments/assets/024acda2-3877-44ee-81cc-c74f9ac90e4b" />

Right-click and select Properties, and you can then you can go ahead and make your changes. 

<img width="771" height="564" alt="image" src="https://github.com/user-attachments/assets/d89885d1-17b5-4414-b220-1cf19fc92641" />

____________________________________________________________________________________________________________________________________________________________________________________________________________________________

Control Panel-

The definition is: a centralized interface that allows users to view, manage, and customize system settings on a device or platform 

In help desk control panel can be useful for helping users customise their computers. For example, if a user wants to turn on accommodation for low vision or something along those lines, you can use the control panel to do that. You can use it to edit and view network adapters and edit your device's IP address in the network and sharing center. You can make changes to the device's firewall or security parameters, or edit the device's battery settings in the system and security tab. 

<img width="1119" height="621" alt="image" src="https://github.com/user-attachments/assets/a0a9e98a-e1f2-4846-92dd-c34af4026ad4" />
