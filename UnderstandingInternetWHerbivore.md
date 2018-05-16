## Understanding the Internet through Herbivore

### Authors
Herbivore is made and maintained by [Surya Mattu](https://github.com/samatt) and [Jen Kagan](https://github.com/kaganjd). [Ingrid Burrington](https://github.com/lifewinning), [Eve Weinberg](https://github.com/evejweinberg) and Pedro Galvao Cesar De Oliveira have also contributed to the project. Herbivore was made with the support of NYU's Interactive Telecommunications Program and their Something-In-Residence fellowship. Curriculum written by [Lauren Gardner](https://github.com/poohlaga).

### Essential Questions
- What information is my computer sharing about me or my online activity?
- How does HTTP vs. HTTPS really affect my online security?
- What information are my IoT devices at home sharing?

### Introduction
We will user [Herbivore](https://github.com/samatt/herbivore), an open source tool that aims to demistify the world of network packets for the uninitiated. Herbivore is a free, open source tool that shows users the data packets that travel between their computers and the internet. By surfacing this information, we hope to demystify how the internet works and make network literacy accessible to a much wider audience.

A handful of packet sniffing libraries and desktop applications already exist for analyzing network packets, but were designed for people who have programming experience or a network engineering background; they were not designed as educational tools for people without technical backgrounds. 

#### Target Audience / Prerequisite & Pre-Assessment
This workshop is intended for adults, young and old. This workshop is ideal for those who are interested in learning how to packet sniff or learn what that even means. 

### Outcomes & Goals
In this workshop we will go through the basics of what packet sniffing means and supply you with the knowledge and tools to enable you to monitor this activity at home. **This is not a hacking workshop,** *we will be teaching you skills to do packet sniffing on your home network.*

Students will learn how to install software used to monitor the internet traffic occuring on devices in your home network and how to interpret the data that is being passed. You'll also walk away with a better understanding of computer networking and the stack that is used in most commercial applications.

### Pacing / Duration
tbd

### Materials Needed & Exercises To Do Before Class
You will need a Mac to run Herbivore :( . But all is not lost! Even if you dont have a Mac you can still learn a whole bunch. We encourage participants to work together and share computers.
      
1. Install [Herbivore](https://github.com/samatt/herbivore) on your Mac. After you install and set permissions, restart the application and connect to your home network. Take a look around, make some notes about what you see:
   1. how many devices are connected - what are they?
   1. where there any devices on your home network that you can not identify?
   1. which device send the most information or communicates most frequently?
   1. what else do you see that surprises you or that you have questions about?

2. Read/watch before class:
   1. [How the Internet Works (in 5 minutes)](https://www.youtube.com/watch?v=7_LPdttKXPc&feature=youtu.be)
   1. [What is a Packet?](http://networks.land/reference/packets/), from Networks Land.
   1. [The House That Spied on Me](https://gizmodo.com/the-house-that-spied-on-me-1822429852)
   1. Whistleblower Mark Klein describes how the [NSA was collecting internet communications by interfering in an ISP's physical infrastructure.](https://www.wired.com/2013/06/nsa-whistleblower-klein/) 
   1. Read how ISPs are allowed [to sell our browsing data to private companies.](https://www.washingtonpost.com/news/the-switch/wp/2017/03/29/what-to-expect-now-that-internet-providers-can-collect-and-sell-your-web-browser-history/?utm_term=.e90fcb9af5f6)

### Exercise Descriptions
*this will be filled in after class*

### Vocabulary

* Network - A network is a collection of terminal nodes, links are connected to enable telecommunication between the terminals. The transmission links connect the nodes together. The nodes use circuit switching, message switching or packet switching to pass the signal through the correct links and nodes to reach the correct destination terminal.
Each terminal in the network usually has a unique address so messages or connections can be routed to the correct recipients. The collection of addresses in the network is called the address space.

* Node - A physical network node is an active electronic device that is attached to a network, and is capable of creating, receiving, or transmitting information over a communications channel.

* Router - the device that forwards, or routes, data packets along to where they’re supposed to go based on the addresses in the packet headers.

* Ethernet - is a computer networking technology commonly used in local area networks (LAN), metropolitan area networks (MAN) and wide area networks (WAN).

* Internet Service Provider (ISP) - There are many kinds of internet service providers, but in this case we're talking about access providers. These are the companies that install cable in your neighborhood and often supply your router when you set up your internet in your home. ISPs hold a lot of power because they physically control the flow of data. 

* Website - the collection of files—from style files, scripts, images, and plain text—that you request from the server and that are ultimately rendered on your computer by your browser.

* Server - the computer that hosts websites and makes them publicly available through a URL. the server responds to client requests. any computer can be both a server or client—it just depends what role the computer is playing. is the computer serving files or requesting files? when people use the metaphor of 'the cloud' to talk about file storage, they're talking about a server or just "another person's computer."

* Transmission Control Protocol (TCP) - is one of the main protocols of the Internet protocol suite, therefore the entire suite is commonly referred to as TCP/IP. TCP provides reliable, ordered, and error-checked delivery of a stream of octets (bytes) between applications running on hosts communicating via an IP network. Major Internet applications such as the World Wide Web, email, remote administration, and file transfer rely on TCP. 

* Hyper Text Transfer Protocol (HTTP) & HTTP Secure (HTTPS) - The protocol over which data is sent between your browser and the website that you are connected to. The 'S' at the end of HTTPS stands for 'Secure' and means all communications between your browser and the website are encrypted. 

* MAC address (media access control) - a unique identifier assigned to a device at the data link layer of a network segment. MAC addresses are used as a network address for most IEEE 802 network technologies, including Ethernet and Wi-Fi. 
MAC addresses are most often assigned by the manufacturer of a network interface controller (NIC) and are stored in its hardware, such as the card's read-only memory or some other firmware mechanism. In brief, MAC address is like a social security number which remains unchanged for a person's life time (here, the device), while an IP address is like a postal code which can be changed.

* IP address (Internet Protocol address) - Numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. An IP address serves two principal functions: host or network interface identification and location addressing. The IP address space is managed globally by the Internet Assigned Numbers Authority (IANA), and by five regional Internet registries (RIRs) responsible in their designated territories for assignment to end users and local Internet registries, such as Internet service providers. Each ISP or private network administrator assigns an IP address to each device connected to its network. Such assignments may be on a static (fixed or permanent) or dynamic basis. 

* Port - A port is an endpoint of communication in an operating system. A port is always associated with an IP address of a host and the protocol type of the communication. It completes the destination or origination network address of a message. Ports are identified for each protocol and address combination by 16-bit unsigned numbers, commonly known as the port number.

* Packets or Network Packet -  A network packet is a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data, which is also known as the payload. Control information provides data for delivering the payload, for example: source and destination network addresses, error detection codes, and sequencing information. Typically, control information is found in packet headers and trailers. 

* Packet Sniffer -  A packet inspection tool is software running on a computer that allows you to look at all the network traffic that is being sent and received on the network you are currently connected to. The range of activity this lets you monitor includes your browser traffic, your operating system sending bug reports, services like Dropbox and Spotify talking to their servers and content streaming to devices such as Apple Tvs and Sonos speakers, and your internet of things devices talking on the internet.

* Addresses - The routing of network packets requires two network addresses, the source address of the sending host, and the destination address of the receiving host.

* Payload - In general, payload is the data that is carried on behalf of an application. It is usually of variable length, up to a maximum that is set by the network protocol and sometimes the equipment on the route. When necessary, some networks can break a larger packet into smaller packets.


## Post Session 

### Takeaways & Next Steps
These are additional materials to leave with to dig deeper into the subject or additional exercises and challenges to help  progress your knowledge to the next level and gain mastery of the subject through independent study.

***First Steps***
- [The internet is made of packets - workshop](https://www.whatisit.tech/packets/index.html)
- [Your smart home is spying on you. Here's how to spy back](https://fieldguide.gizmodo.com/your-smart-home-is-spying-on-you-here-s-how-to-spy-bac-1822939698), a step by step tutorial by Surya on how to set up a RaspberryPi to monitor the digital emissions from your own homes.
- Read through [Networks.Land](http://networks.land/), tools and activities for understanding the internet from the ground up by Ingrid Burrington and Surya Mattu.
- [NYU ITP, Understanding Networks](https://itp.nyu.edu/networks/), the syllabus for Thomas Igoe's class taught at NYU ITP.

***Next Steps***
- [Debookee](https://debookee.com/) easy packet sniffer for mac
- Download [Wireshark](https://www.wireshark.org/) and dig deeper [How To Go From 0 to Sniffing Packets in 10 Minutes](https://motherboard.vice.com/en_us/article/jpgmxp/how-to-go-from-0-to-sniffing-packets-in-10-minutes)
- [Wireshark 101](http://samatt.github.io/all/teaching/2013/11/01/packet-sniffing/), a more advanced tutorial using wireshark  to sniff packets and inject them in a network. 

***Big Steps***
- [mitmproxy](https://mitmproxy.org) - Advanced but powerful packet sniffer

### Implementation Guidance &  Teaching Reflection
TBD... e.g. Please provide some guidance based on experience delivering the unit and potential modifications might you are considering making for future iterations of this unit. This is an opportunity for you as the unit author to give teachers practical guidance.

***With thanks and acknowledgement, we were inspired by the curriculuim templates shared by [NYCDOE](http://blueprint.cs4all.nyc/units/40/) and [NYC Open Data](https://github.com/datapolitan/Data_Analytics_Classes/blob/gh-pages/Excel_Tools_Summarizing_Data.md)***
