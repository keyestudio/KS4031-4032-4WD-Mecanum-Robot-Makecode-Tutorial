#  **Makecode Tutorial**

![](media/718228ea3ade238b6d0fc30b45bfa8d9.png)

## Get Started with Micro:bit

The following instructions are applied for Windows system but can also serve as a reference if you are using a different system.

#### 1 Write code and program：

This chapter describes how to write program and load the program to the Micro: Bit main board V2.

You are recommended to browse the official website of Micro:bit for more details, and the link is attached below:

[https://microbit.org/guide/quick/](Https://microbit.org/guide/quick/)

**Step 1: connect the Micro: Bit main board with your computer**

Firstly, link the Micro: Bit main board with your computer via the USB cable. Macs, PCs, Chromebooks and Linux（including Raspberry Pi）systems are all compatible with the Micro: Bit main board.

Note that if you are about to pair the board with your phone or tablet, please refer to this link: [https:/microbit.org/get-started/user-guide/mobile/](https://microbit.org/get-started/user-guide/mobile/)

![](media/b5a90ee5338cd7fb96e135fe71a79a61.png)
![](media/c4748dd952bb0562a9c879bdd8e198c7.png)

Secondly, if the red LED on the back of the board is on, that means the board is powered. When your computer communicates with the main board via the USB cable, the yellow LED on it will flashes. For example, it will flicker when you burn a
“hex”file.

Then Micro: bit main board will appear on your computer as a driver named “MICROBIT(E:)”. Please note that it is not an ordinary USB disk as shown below.

![](media/a2b53f93f4c24b81fc5cdb5986fd100d.png)

**Step 2: write programs**

View the link <https://makecode.microbit.org/> in your browser. Click ‘New Project’;

The dialog box‘Create a Project’ appears, fill it with‘heartbeat’and click ‘Create √’to edit.

(If you are running Windows 10 system, it is also viable to edit on the APP MakeCode for micro:bit , which is exactly like editing in the website. And the link to the APP is:[https://www.microsoft.com/zh-cn/p/makecode-for-micro-bit/9pjc7sv48lcx?ocid=badgep&rtc=1&activetab=pivot:overviewtab](https://www.microsoft.com/zh-cn/p/makecode-for-micro-bit/9pjc7sv48lcx?ocid=badgep&rtc=1##activetab=pivot:overviewtab))

![](media/fd741a4a932cf25b5165c8135b512848.png)

![](media/f76062b0607cfca5d20bc26199b2f711.png)

Write a set of micro:bit code. You can drag some modules in the Blocks to the editing area and then run your program in Simulator of MakeCode editor as shown in the picture below which demonstrates how to edit ‘heartbeat’ program .

![](media/215b27bc1633c62d16fe208e06e39ad9.png)

Click the arrow behind “JS JavaScript”to choose between“JavaScript”or “Python”and you will find the corresponding program in JavaScript language or Python language as shown below:

![](media/67b86dacacfb0d716068af592d79382a.png)

![](media/c3950b45a80b660c60d4ca8544c6acbd.png)

**Step 3: download code**

If your computer is Windows 10 and you have downloaded the APP MakeCode for micro:bit to write program, what you will have to do to download the program to your Micro: Bit main board is merely clicking the ‘Download’ button, then all is done.

If you are writing program through the website, following these steps:

Click the ‘Download’ in the editor to download a "hex" file, which is a compact program format that the Micro: Bit main board can read. Once the hexadecimal file is downloaded, copy it to your board just like the process that you copy the file to the USB driver. If you are running Windows system, you can also right-click and select ‘Send to → MICROBIT(E:) ‘to copy the hex file to the Micro: Bit main board.

![](media/c5b462b6e3acbfedf6c9b22e4651d69a.png)

![](media/a81d4430eb152346d13bf67b2233b9db.png)

You can also directly drag the "hex" file onto the MICROBIT (E:) disk.

![](media/fe0f2de72ba0b38f00403f1aaef7f514.png)

![](media/b4f3602c0e192646f77b150e2acaf947.png)

During the process of copying the downloaded hex file to the Micro: bit main board, the yellow signal light on the back side of the board flashes. When the copy is completed, the yellow signal light will stop flashing and remain on.

**Step 4: run the program：**

After the program is uploaded to the Micro: bit main board, you could still power it via the USB cable or change to via an external power. The 5 x 5 LED dot matrix on the board displays the heartbeat pattern.

| ![](media/d61a26d2f2367f0378974832f679efe1.png) |
|--------------------------------------------------|--------------------------------------------------|
| Power via USB cable                              | Power via external power (3V)                    |

**Caution:**

When you programs each time, the driver of Micro: bit will automatically eject and return and your hexadecimal files will disappear . And the board can only have access to hexadecimal files (hex) and save no other files.

**Step 5：about other programming languages**

This chapter has described how to use the Micro:bit main board.

But except for the Makecode graphical programming introduced you can also write Micro:bit programs in other languages. Go to the link: https://microbit.org/code/> to know about other programming languages , or view the link: <https://microbit.org/projects/>, to find something you want to have a go.

#### 2.Makecode：

Browse <https://makecode.microbit.org/> and enter Makecode online editor or open the APP MakeCode for micro:bit of Windows 10.

![](media/285f5ee70c3d95855f87a17d227b8675.png)

Click“New Project”, and input“heartbeat”, then click “create √”to enter Makecode editor, as shown below:

![](media/5d8174f605724953bcb4a00edade8f30.png)

There are blocks“on start”and“forever”in the code editing area.

When the power is plugged or reset,“on start”means that the code in the block only executes once, while“forever”implies that the code runs cyclically.

#### 3. Quick Download

As mentioned before, if your computer is Windows 10 and you have downloaded the APP MakeCode for micro:bit to write programs, the program written can be quickly downloaded to the Micro: Bit main board by selecting ‘Download’.

While it is a little more trickier if you are using a browser to enter Makecode. However, if you use Google Chrome, suitable for Linux，macOS and Windows 10, the process can be quicker too.

We use the webUSB function of Chrome to allow the internet page to access the hardware device connected USB.

You could refer to the following steps to connect and pair devices.

**Device pairing:**

Connect micro:bit to your computer by USB cable.

Click“...”beside“Download”and tap“Connect device”;

![](media/39effe268391a9a64558a0438f5f2fe5.png)

Click“Next”;

![](media/e843e223f125fdd0448c49d80e576d39.png)

Click another“Next”;

![](media/fe5c6991e1ba8bd46f0bc6b7069b91c1.png)

Then select the corresponding device and click“Connect”. If no devices shows up
for selection, please refer to: [https://makecode.microbit.org/device/usb/webusb/troubleshoot](https://makecode.microbit.org/device/usb/webusb/troubleshoot%20)

And for updating the firmware of the Micro:bit:
[https://microbit.org/guide/firmware/](https://microbit.org/guide/firmware/%20)
.

If the links are too troublesome for you , then you can also turn to our ‘Troubleshooting Downloads with WebUSB’and“upload the firmware”in the folder we provided in the link:

https://fs.keyestudio.com/KS4031-4032![](media/4cf10fecd346658a9943e900eef2e265.png)

Click“Done”to finish the pairing.

![](media/0b3776a491c27034738926b3f958b3f0.png)

![](media/37f01f5a75b4127a193a1099bdd142d3.png)

**Download program:**

After the pairing, click “download”to directly download the program to the board. If it is successfully downloaded, the icon ![](media/af296c6d48f189a98fcb96522182ffa9.png) will shift to ![](media/c55e4d43d82301258cbc0367cb3b3d49.png).

![](media/96fbd5a50eb87de8ad464cbbd09624f1.png)

#### 4.Makecode extension libraries:

We have made a makecode extension library for this Mecanum robot car.

**Add an extension library of the Mecanum robot car:**

Please follow the following steps to add extension files:

Open Makecode to enter a certain project→click the gear-shaped icon(for setting) in the upper right corner→choose“Extensions”;

![](media/9bee14f94789507ec63f56c322c8ad88.png)

Or click”Advanced”to select“Extensions”as shown below:

![](media/b78a1ba52cf7d70976961bbf12e846ba.png)

Input the link <https://github.com/keyestudio2019/mecanum_robot> to search;

Tap the searching result“MecanumRobot”to download and install it;

This process may take a few seconds.

![](media/935efb0853803d5089ad4d0855c34906.png)

After the installation, you can find the extension files **Mecanum Robot** and
**IrRemote** on the left side.

And extension file Neopixel is also installed.

![](media/19c5f037f020a5ea4df236ce2785d9b9.png)

![](media/cbe287a68f43ba991b3a2df2f0bf2bc2.png)

Note: the extension files added are only available for this project. Therefore, when you create a new **MecanumRobot** project, you will need to add these extension files again.

**Update or delete the MecanumRobot extension files:**

Please follow the following steps to update or delete extension files:

Click "Js JavaScript" to change to textual version:

![](media/9277623e759fe36727804da74a8fbb02.png)

Click the“Explorer”on the left side:

![](media/16117dc3b1f8521457f18185c1de57fa.png)

You can find these added files in the list;

Click the dustbin icon beside the file to delete the corresponding file;

Tap the refresh icon to update the corresponding MecanumRobot extension file.

![](media/b5a036316ec5869cc4c37b69115f1be2.png)

#### 5.Resources and test code

We also provide a link：https://fs.keyestudio.com/KS4031-4032

You can obtain relevant test codes, tutorials and troubleshooting methods as well, as shown in the figure below:

![](media/6ddb789cdf2000b0aa722d56000cbf6f.png)

#### 6.Input test code

We provide hexadecimal code files (project files) for each project. The file contains all the contents of the project and can be imported directly, or you can manually drag the code blocks to complete the program for each project. For simple projects, dragging a block of code to complete the program is recommended.For complex projects, it is recommended to conduct the program by importing the hexadecimal code file we provide.

Let's take the "Heatbeat" project as an example to show how to load the code.

Open the Web version of Makecode or the Windows 10 App version of Makecode;

![](media/40e8e36d4a7e9b8a726ff1a832393df5.png)

Click“Import File”;

![](media/3358909f898dd9898923f72945613851.png)

![](media/ff66d0d78d170913676e361a62078faf.png)

Select“../Makecode Code/Project 1\_ Heart beat/Project 1\_ Heart beat.hex”

Then click“Go ahead”.

![](media/c919527e842cb6dd603a03b8f850a7f8.png)

![](media/b5f985386359a415c102d3deefecce53.png)

In addition to importing the test code file provided into the Makecode compiler above, you can also drag the the test code file provided into the code editing area of the Makecode compiler, as shown in the figure below:

![](media/115cceaf5de0eb4f2079ca09681dbb7c.png)

After a few seconds, it is done.

![](media/a451132713cbd16f3f7957c5312673ba.png)

Note: if your computer system is Windows7 or 8 instead of Windows 10, the pairing cannot be done via Google Chrome. Therefore, digital signal or analog signal of sensors and modules cannot be shown on the serial port simulator.

However, you need to read the corresponding digital signal or analog signal.So what can we do? You can use the CoolTerm software to read the serial port data of the microbit. Next chapter is about how to install CoolTerm.

#### 7.Install CoolTerm：

CoolTerm program is used to read the data on serial port.

Download CoolTerm program:

<https://freeware.the-meiers.org/>

After the download, we need to install CoolTerm program file, below is PC Window system taken as an example.

1.  Choose“win”to download the zip file of CoolTerm

2.  Unzip file and open it. (also suitable for Mac and Linux system)

![](media/97f831d38df9ee01dcfedac244bfe281.png)

![](media/e77548d01727e523e9e8c900d2fa962d.png)

3. Double-click![](media/5f29eed25fc16602cfc0716f047c2da1.png).（Please make sure that the driver of Micro:bit is installed and the main board is connected with the computer.)

![](media/74fd81c83f0c0a26b4e299b93ce4ede4.png)

The functions of each button on the Toolbar are listed below: <http://wiki.keyestudio.com/index.php/File:IDE.png>

![](media/70bebd79d7cd20336ae394c916500a28.png)

| ![](media/2b728375ed2b8cd288c884e553418001.png)        | Open up a new Terminal                           |
|--------------------------------------------------------|--------------------------------------------------|
| ![](media/5f972f2eac5050ca0107416b2be067c2.png)        | Open a saved Connection                          |
| ![](media/be6f8b560e0afc447f9c32b4474f633f.png)        |  Save the current Connection to disk             |
| ![](media/52257d028694a313fc4eea4d9c2469d7.png) | Open the Serial Connection                       |
| ![](media/6ad366842b18084553a142ab82a613cf.png) | Close the Serial Connection                      |
| ![](media/8fa3ac342549d33b6c9aa5a9e4688bea.png) | Clear the Received Data                          |
| ![](media/c8d1dd8c3356b4938e143de1022e5842.png) | Open the Connection Options Dialog               |
| ![](media/36e13c266fd4b9723d9db40fe30cd203.png) | Display the Terminal Data in Hexadecimal Format  |
| ![](media/b505c71c3344036730b1d67f0c62a354.png)        | Display the Help Window                          |

## Projects

(Note: project 8.1 to 8.12 will be conducted with the built-in sensors and LED dot matrix of the Micro:bit main board V2)

### Project 1: Heartbeat

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Description**

This project is easy to conduct with a micro:bit V2 main board, a Micro USB cable and a computer. The micro:bit LED dot matrix will display a relatively big heart-shaped pattern and then a smaller one. This alternative change of this pattern is like heart beating. This experiment serves as a starter for your entry to the programming world.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile (How to import?)

Or click“New Project”and drag blocks step by step

![](media/b14ace883d757d0dffb2adae9a035aaa.png)

**(3)Test Code**

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                  | File Name                |
|-----------|---------------------------------------------------------------------------------------|--------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 1：Heartbeat | Project 1：Heartbeat.hex |

Or you could edit code step by step in the editing area.

Go to“Basic”→“show icon”.

Copy it again and place into“forever”block.

Click“❤”to select“![](media/04fdfc9060943954e7938bb1a741d626.png)”.

![](media/7b7e9577c6993f443060015e141f9189.png)

Complete Program：

![Img](./FILES/KS4031-KS4032.md/img-20230414153026.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414153051.png)
                                                                                                                                                                                                                                                                                                                  |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/00e2115f7e171c91af90f27889395dde.png)

**(4)Test Results**

Download code to micro:bit and keep USB cable connected. The LED dot matrix will display ![](media/14472c7e1c80818889bb47bfc709f053.png) and ![](media/04fdfc9060943954e7938bb1a741d626.png) ceaselessly.

([How to download?] [How to quick download?])

If the download is not success, try to disconnect micro:bit from your computer and then reconnect them and reopen Makecode to try again.

### Project 2: Light A Single LED

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Description**

The LED dot matrix consists of 25 LEDs arranged in a 5 by 5 square. In order to locate these LEDs quickly, as the figure shown below, we can regarded this matrix as a coordinate system and create two aces by marking those in rows from 0 to 4 from top to bottom, and the ones in columns from 0 to 4 from the left to the right. Therefore, the LED sat in the second of the first line is (1,0）and the LED positioned in the fifth of the fourth column is (3,4）and others likewise.

![](media/41c834c1592b4ecbec3066082c25f10b.png)

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码)

Or click“New Project”and drag blocks step by step

**(3)Test Code**

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                           | File Name                         |
|-----------|------------------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 2：Light A Single LED | Project 2：Light A Single LED.hex |

Or you could edit code step by step in the editing area.

A. Click“Led”→“more”→“led enable false”

B. Put it into the“on start”block, and click the drop-down triangle button to select“true”.![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*
(2) A. Enter“Led”→“toggle x 0 y 0”block;

B. Combine it with“forever”，alter“x 0”into“x 1”.

![](media/70e6ac6cc25d9f0f313c670383c718dd.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

(3) A. Enter“Basic”→“pause (ms) 100”from“

B. Then move it below the“toggle x1 y0”block, and set to 500ms.![](media/b3cf902a00a442590d9e81b3d963b856.png)

(4) Duplicate code string![](media/a19713fcfe99bbdc3b7d2448e42d3b47.png)once and place it into“forever”block.![](media/6fa24a7c1348d775f70f3c3e65294091.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Enter“Led”→“plot x 0 y 0”

B. Keep it beneath block“pause(ms)500”, then set to“plot x 3 y 4”:
![](media/2d573bedbe650cae075dea31bfd509a4.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Replicate“pause (ms) 500”once and keep it below the block“plot x3y4”

![](media/14aa140cf450499f11035dc8313bd83c.png)

Click“Led”→“unplot x 0 y 0”and set to“unplot x3 y 4”;

Lay down it beneath“pause (ms) 500”block

Copy“pause (ms) 500”block once, and keep it below the“unplot x3 y 4”block.
![](media/523b04d16b1e2755b488b05a82c6da71.png)

![](media/56b1ee20b10053ada305a20ec3a3c7b2.png)

Complete Program：                                                 |
![Img](./FILES/KS4031-KS4032.md/img-20230414153244.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414153318.png)

Click“JavaScript”to switch into corresponding JavaScript code:

![](media/472b93b10b3d00bef040ae15892f9c5d.png)

**(4)Test Results:**

After uploading test code to micro:bit main board V2 and powering the main board via the USB cable, the LED in (1,0) lights up for 0.5s and the one in (3,4) shines for 0.5s and repeat this sequence.

([How to download?] [How to quick download?])

### Project 3: LED Dot Matrix

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Description**

Dot matrices are very commonplace in daily life. They have found wide applications in LED advertisement screens, elevator floor display, bus stop announcement and so on.

The LED dot matrix of Micro: Bit main board V2 contains 25 LEDs in a grid. Previously, we have succeeded in controlling a certain LED to light by integrating its position value into the test code. Supported by the same theory, we can turn on many LEDs at the same time to showcase patterns, digits and characters.

What’s more, we can also click”show icon“ to choose the pattern we like to display. Last but not the least, we can design patterns by ourselves.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码)

Or click“New Project”and drag blocks step by step

**(3)Test Code**

**Code 1：**

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                          | File Name                    |
|-----------|-----------------------------------------------------------------------------------------------|------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 3： LED Dot Matrix-1 | Project 3： LED Dot Matrix-1 |

Or you could edit code step by step in the editing area.

A. Enter“Led”→“more”→“led enable false”

Click the drop-down triangle button to select“true”
![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png)

Combine it with “on start” block

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Click“Led”to move“plot x 0 y 0”into“forever”，then replicate“plot x 0 y 0”for 8 times, respectively set to“x 2”y 0”,“x 2”y 1”,“x 2”y 2”,“x 2”y 3”,“x 2”y 4”,“x 1”y 3”“x 0”y 2”,“x 3”y 3”,“x 4”y 2”.

![](media/d44a44c5708aa9ea67a70220d3afde02.png)

Complete Program：

![Img](./FILES/KS4031-KS4032.md/img-20230414153406.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414153638.png)
                                              |

Select“JavaScript" and“Python”to switch into JavaScript and Python language code:

**Code 2：**

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                          | File Name                    |
|-----------|-----------------------------------------------------------------------------------------------|------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 3： LED Dot Matrix-2 | Project 3： LED Dot Matrix-2 |

Or you could edit code step by step in the editing area.

A. Enter“Basic”→“show number 0”block,

Duplicate it for 4 times, then separately set to“show number 1”,“show number 2”,“show number 3”,“show number 4”,“show number 5”.

![](media/5b8bc5bbc3f5e84aeb19d4dc7d7d2ffd.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Click“Basic”→“show leds”, then put it into“forever”block，tick blue boxes to light LED and generate“↓”pattern.

![](media/9c1ecc0a6db98f37533c9deec935b717.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Move out the block“show string” from“Basic”block, and leave it beneath the“show leds” block.

![](media/3f638ac0f3f088a2adefa1ad17cea38a.png)

Choose“show icon”from“Basic”block, and leave it beneath the block“show string“Hello!”block

![](media/e989a69cc6fea0a3faa6c1f491b40e69.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Enter“Basic”→“show arrow North”;

B. Leave it into“forever”block，replicate“show arrow North”for 3 times，respectively set to“North East”,“South East”, “South West”,“North West”.

![](media/008c4281fabc99c159c52fcf4ab28bf2.png)

Click“Basic”to get block“clear screen”then remain it below the block “show arrow North West”.

![](media/94182fcc1ee9e1998ef16b2925ea082b.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Drag“pause (ms) 100”block from“Basic”block and set to 500ms, then leave it below“clear screen”block.

![](media/e782704754471e5db06937017e5022d0.png)

Complete Program:

![Img](./FILES/KS4031-KS4032.md/img-20230414153816.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414154121.png)
                                                 |

Select“JavaScript" and“Python”to switch into JavaScript and Python language code:

![](media/4c537c2e073066441fb23219619ecf09.png)

**(4)Test Results:**

Upload code 1 and power the board , we will see the icon![](media/d4e278da768e447ed344d581e671f57a.png)

Upload code 2 and plug micro:bit in power, Micro: bit starts showing number 1, 2, 3, 4, and 5, then cyclically display![](media/d4e278da768e447ed344d581e671f57a.png),“Hello!”,
![](media/66b31365d42274ef94ce9a3fcea1cd6c.png),![](media/39fe4029acb5fb675d875c58e382d148.png),![](media/45fcde65eb80a942d3903e400a346587.png),![](media/9e34fdb19d72918bde242994a3c94c1f.png) and ![](media/2a45fca9d836ce38674c347c70c81e02.png)patterns.

([How to download?] [How to quick download?])

### Project 4: Programmable Buttons

![](media/06be84fb11b1fd07cd0cbb392132b903.png)

**(1)Project Description**

![](media/2ff75a1d81bfe0228b83931a0b7cc860.png)

Buttons can be used to control circuits. In an integrated circuit with a push button, the circuit is connected when pressing the button and it is open the other way around.

Micro: Bit main board boasts three push buttons, two are programmable buttons(marked with A and B), and the one on the other side is a reset button. By pressing the two programmable buttons can input three different signals. We can press button A or B alone or press them together and the LED dot matrix shows A,B and AB respectively. Let’s get started.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)]

Or click“New Project”and drag blocks step by step

**(3)Test Code**

**Code 1：**

Press buttons on micro:bit, micro:bit will display character strings.

The route to get test code（[How to load?]）

| File Type | Path                                                                                               | File Name                         |
|-----------|----------------------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 4：Programmable Buttons-1 | Project 4：Programmable Buttons-1 |

Or you could edit code step by step in the editing area.

Delete“on start”and“forever”firstly，then click“Input”→“on button A pressed”

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Click“Basic”→“show string”;

B. Then place it into“on button A pressed”block, change “Hello!”into“A”.![](media/aebeefcca33e544db91944881f0a9a68.png)

Copy code string![](media/aebeefcca33e544db91944881f0a9a68.png)once, tap the drop-down button“A”to select“B”and modify character“A”into“B”.![](media/6c6bcb6bbeaf8ed55b985e44fc734d61.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Copy![](media/aebeefcca33e544db91944881f0a9a68.png)once，and set to“on button A+B pressed”and“show string “AB”

![](media/3e8bde170db9e02e9cee36b3ede184b7.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

**Complete Code:**

![Img](./FILES/KS4031-KS4032.md/img-20230414154207.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414154224.png)
                                           |

Select“JavaScript" and“Python”to switch into JavaScript and Python language code:

![](media/50c59105d5a2409eea809e6ce73cf740.png)

**Code 2：**

The route to get test code[How to load?]

| File Type | Path                                                                                               | File Name                         |
|-----------|----------------------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 4：Programmable Buttons-2 | Project 4：Programmable Buttons-2 |

Or you could edit code step by step in the editing area.

A. Click“Led”→“more”→“led enable false”,

B. Put it into the block“on start”，click drop-down triangle button to select“true” ![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png).

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Tap“Variables”→“Make a Variable...”→“New variable name：”

B. Enter“item”in the dialog box and click“OK”，then variable“item”is produced. And move“set item to 0”into“on start”block

![](media/a4d4a625424427a8f2d628db1f9417ae.png)

A. Click“Input”→“on button A pressed”.

B. Go to“Variables”→“ change item by 1 ”

C. Place it into“on button A pressed”and 1 is modified into 5.
![](media/81ec128a3a4bb86fed7d2f78bab20447.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Duplicate![](media/81ec128a3a4bb86fed7d2f78bab20447.png)code string once，click the drop-down button to select“B”，then set“change item by -5”.
![](media/a53f0e6deb299ba15c494547dec19259.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Enter“Led”→“plot bar graph of 0 up to 0”

B. Keep it into“forever”block

C. Go to“Variables”to move“item”into 0 box，change 0 into 25.

![](media/3232608700bf086dd0474de156a9116d.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Go to“Logic”to move out “if...true...then...”and “=”blocks，

B. Keep“=”into“true”box and set to “\>”

C. Select“item”in the“Variables”and lay it down at left box of “\>”，change 0 into 25；

D. Enter“Variables”to drag“set item to 0”block into“if...true..then...”, alter 0 into 25.

![](media/75a22c2c7eaf03a6d0ffaadf1d9f2fe9.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

(7) A. Replicate code string![](media/e0de4c7488b48605b292df5d3dd798dc.png)once

B.“\>”is modified into“\<”and 25 is changed into 0,

C. Leave it beneath ![](media/e0de4c7488b48605b292df5d3dd798dc.png)code string.

![](media/678059d480a41d372a6b70175b5a3225.png)

**Complete Program：**

![Img](./FILES/KS4031-KS4032.md/img-20230414154311.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414154418.png)
                                                |

Click“JavaScript" to switch into JavaScript code:

![](media/21704f7ef37d6ed440545c28dbd93211.png)

**(4)Test Results:**

After uploading test code 1 to micro:bit main board V2 and powering the main board via the USB cable, the 5\*5 LED dot matrix shows A if button A is pressed, B if button B pressed, and AB if button A and B pressed together.

After uploading test code 2 to micro:bit main board V2 and powering the main board via the USB cable, when pressing the button A the LEDs turning red increase by 5 while when pressing the button B the LEDs turning red reduce.

([How to download?] [How to quick download?])

### Project 5: Temperature Measurement

**(1)Project Description**

The Micro:bit main board V2 is not equipped with a temperature sensor, but uses the temperature sensor built into NFR52833 chip for temperature detection. Therefore, the detected temperature is more closer to the temperature of the chip, and there maybe deviation from the ambient temperature.

Note: the temperature sensor of Micro:bit main board is shown below:

![](media/206c8ec1c3f11d2de8d0f42fdf5b6b47.png)

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile (How to import?)

Or click“New Project”and drag blocks step by step.

**(3)Test Code**

**Code 1**：

Micro:bit detects temperature

The route to get test code（How to load?）

| File Type | Path                                                                                                  | File Name                            |
|-----------|-------------------------------------------------------------------------------------------------------|--------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 5：Temperature Measurement-1 | Project 5：Temperature Measurement-1 |

Or you could edit code step by step in the editing area.

Go to“Advanced” →“Serial” →“serial redirect to USB”

Place it into “on start”

![](media/07637ee0425802f6a59eb6f6dd62ea5c.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Click“Serial”to drag out“serial write value x=0”

Move it into“forever”block

![](media/0e709be8f6acc9521f1f76a0fc32c792.png)

Go to“Input” →“temperature(℃)”

Place it into 0 box

Change x into Temperature

![](media/2143a993b073f763a2e770a7eea628d6.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Move“pause (ms) 100”from“Basic”block and place it under block“serial
write.....temperature(℃)”

![](media/0c03bc986e186751ac33b92e5052b26f.png)

Complete Program：

![Img](./FILES/KS4031-KS4032.md/img-20230414154500.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414154537.png)
                                                |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/0cb83e9f83fa0fd0344685f38913cb43.png)

Download code 1 to micro:bit board and keep USB cable connected, then tap button
![](media/e0580d7886af95d2a4ea7cd9d40759ff.png):

( How to quick download?)

![](media/0d3198e0cb5460c9820bc2f016c0d7c1.png)

Temperature data is shown below:

![](media/6177222069a9583f2d8314d592fdb916.png)

Through the test, the room temperature is 35℃when touching the NFR51822 chip of micro:bit; however, the temperature rises to 37℃ when it touches water cup.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud rate(the baud rate of USB serial communication of Micro:bit is 115200 through the test). Click“OK”and“Connect”.

The serial monitor shows the current ambient temperature value, as shown below:

![](media/b3a18bca1b2a7b5337470735e5a0c5aa.png)

![](media/f78128c148de3862a3fe10d86f063e22.png)

![](media/13238e98c31d620f4ffd7742dd71c78d.png)

![](media/9c88bb875124738a55e5e0fd5bf957ca.png)

**Code 2：**

Micro:bit display different pictures by temperature(the temperature value in the code could be adjusted).

The route to get test code（How to load?）

| File Type | Path                                                                                                  | File Name                            |
|-----------|-------------------------------------------------------------------------------------------------------|--------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 5：Temperature Measurement-2 | Project 5：Temperature Measurement-2 |

Or you could edit code step by step in the editing area.

You could set temperature based on real situation.

Click“Led”→“more”→“led enable false”into“on start”，click drop-down triangle button to select“true” ![](media/976aaaf61e578c48e2f00f6d2a3fccc0.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Go to“Logic”→“if..true...then...else”and “=” block;

B. Move“if..true...then...else” into“forever”block，then place“=”into“true”box.

![](media/28c4cf38fbacb05ca0e457146767757d.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Change“=”into“≥”

B. Go to“Input”→“temperature(℃)”and move it into left 0 box;

C. Change 0 into 35.

![](media/2b0e3775540415849bf36f7d118a8599.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Tap“Basic”→“show icon”，copy it once and lay down them under the“if ...then” and else blocks, then click the drop-down triangle button to select“![](media/9fa58029eb504582ee5a915f591ea583.png)”.
![](media/43df31dacdcc06623c6e2289f1623461.png)

Complete Program：

![Img](./FILES/KS4031-KS4032.md/img-20230414154605.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414154713.png)

Click“JavaScript", the corresponding JavaScript code is shown below:

![](media/9424f8456bb544ca25a7c5a4ea6e852c.png)

**(4)Test Results:**

Upload the Code 1 and plug in power. And 5\*5LED displays the ambient temperature. When pressing the temperature sensor, the temperature will grow on dot matrix.

Upload the code 2 plug in micro:bit via USB cable, when the ambient temperature is less than 35℃, 5\*5LED will show![](media/4b1765e12b413dc5d562f2a16d32392f.png). When the temperature is equivalent to or greater than 35℃, the pattern![](media/f2705fbc4886efcfaac96589ca255f66.png) will appear.

([How to download?] [How to quick download?])

### Project 6: Geomagnetic Sensor

![](media/24c31bb0174e2ac672203e5c36c6875e.png)

**(1)Project Description**

This project mainly introduces the use of the Micro:bit’s compass. In addition to detecting the strength of the magnetic field, it can also be used to determine the direction, an important part of the heading and attitude reference system (AHRS) as well.

It uses FreescaleMAG3110 three-axis magnetometer. Its I2C interface communicates with the outside, the range is ±1000µT, the maximum data update rate is 80Hz. Combined with accelerometer, it can calculate the position. Additionally, it is applied to magnetic detection and compass blocks.

Then we could read the value detected by it to determine the location. We need to calibrate the Micro:bit board when magnetic sensor works. The correct calibration method is to rotate the Micro:bit board.

In addition, the objects nearby may affect the accuracy of readings and calibration.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码) Or click“New Project”and drag blocks step by step

**(3)Test Code**

**Code 1：**

Press A on micro:bit, the value of compass is shown.

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                             | File Name                       |
|-----------|--------------------------------------------------------------------------------------------------|---------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 6：Geomagnetic Sensor-1 | Project 6：Geomagnetic Sensor-1 |

Or you could edit code step by step in the editing area.

A. Click“Input”→“more”→“calibrate compass”

B. Lay down it into block“on start”.

![](media/f0973c3116eb4faf2d4ca138bd057d45.png)

A. Go to“Input”→“on button A pressed”.

B. Enter“Basic”→“show number”, put it into“on button A pressed”block;

C. Tap“Input”→“compass heading(℃)”， and place it into“show number”

![](media/0d9b5a65740d9406848d9a360635982b.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Complete Program：

![Img](./FILES/KS4031-KS4032.md/img-20230414154748.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414154810.png)
                                                    |

Select“JavaScript" and“Python”to switch into JavaScript and Python language code:

![](media/a3fa9018b3e83be04515297b5fd94b42.png)

**Code Description：**

Upload the code 1, plug in micro:bit via USB cable.

As the button A is pressed, LED dot matrix indicates that“TILT TO FILL SCREEN”then enter the calibration interface. The calibration method: rotate the micro:bit to make LED dot matrix draw a square (25 LEDs are on), as shown in the following figure:

([How to download?] [How to quick download?])

![](media/acf3b8c0dee027d9e555fc708831f874.jpeg)

The calibration will be finished until you view the smile pattern![](media/a4faf86fb027b2f4c3dacaeee5d47d2b.png)appear.

The serial monitor will show 0°, 90°, 180° and 270° when pressing A.

**Code 2：**

Make micro: bit board point to the north, south, east and west horizontally , LED dot matrix displays the corresponding direction patterns. The route to get test code（How to load?）

| File Type | Path                                                                                             | File Name                       |
|-----------|--------------------------------------------------------------------------------------------------|---------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 6：Geomagnetic Sensor-2 | Project 6：Geomagnetic Sensor-2 |

![](media/66c4482e3bcd71e712a54f4d73044104.png)

This module can keep reading data to determine direction, so does point to the current magnetic North Pole by arrow.

![](media/d1a4e9f62bdf690ba809ae35c347b233.png)

For the above picture, the arrow pointing to the upper right when the value ranges from 292.5 to 337.5. Because 0.5 can’t be input in the code, the values we get are 293 and 338.

Link computer with micro:bit board by micro USB cable, and program in MakeCode editor:

Enter“Input”→ “more”→“calibrate compass”

Move“calibrate compass”into“on start”

![](media/f0973c3116eb4faf2d4ca138bd057d45.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Click“Variables”→“Make a Variable...”→“New variable name：”

B. Input“x”in the blank box and click“OK”, and the variable “x” is generated.

C. Drag out“set x to”into“forever”block

![](media/0ecd067449d3d52ce3ba751632129b54.png)

A. Go to“Input”→“compass heading(℃)”, and keep it into“0”box

![](media/a97f7ff675fc62533a9053b6c415652b.png)

Tap“Logic”→“if...then...else”, leave it below block“sex x to compass heading”, then click![](media/bf972b006ad6d05686352c4785e54994.png)icon for 6 times.

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Place“and”into“true”block

B. Then move“=”block to the left box of “and”

C. Click“Variables”to drag“x”to the left “0”box, change 0 into 293 and set to “≥”;

D. Then copy“x≥293”once and leave it to the right “0”box and set to“x\<338”

![](media/cf2d8d1d74b5f485abd4843f92b52672.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Go to“Basic”→“show leds”

B. Lay it down beneath ![](media/6dbd99f5a6e4abe8ffd450d19b8a857b.png)block, then click“show leds”and the pattern ![](media/eab025b80ef24f1d5351bd3e06221bad.png)appears.

![](media/fe40fd39ae6abce0721d19cf86ef136d.png)

A. Duplicate ![](media/6dbd99f5a6e4abe8ffd450d19b8a857b.png)for 6 times.

B. Separately leave them into the blank boxes behind “else if”.

C. Set to“x≥23 and x\<68”,“x≥68 and x\<113 ”,“x≥113 and x\<158 ”,“x≥158 and x\<203 ”,“x≥203 and x\<248 ”,“x≥248 and x\<293 ”respectively.

D. Then copy “show leds”for 7 times and keep them below the “else if.......then” block respectively.

E. Click the blue boxes to form the pattern“![](media/4c73992fa4dfc6a2735b49ea8f000ed6.png)”,“![](media/0771b8fd797a3e945a01ec1525ba4a9d.png)”,“![](media/41eb716a282d52483e8467704613d034.png)”,“![](media/2cae18294b329c10ecdefd768d6954e0.png)" />”,“![](media/14b893d1a7157d72209b975d0df8d890.png)”,“![](media/c362406f55115926523a0f60e16828b6.png)”and“![](media/3977e13fdec2bfbc7fc55f5dce4969a9.png)”.

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Complete Program：

![Img](./FILES/KS4031-KS4032.md/img-20230414152258.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414152312.png)
“on start”: command block only runs once to start program. Calibrate compass

The program under the block “forever” runs cyclically.

Store the angle of the compass heading into the variable x

When 293≤x<338，the next program will be executed
![Img](./FILES/KS4031-KS4032.md/img-20230414152427.png) appears on the dot matrix
When 23≤x<68，the next program will be executed

![Img](./FILES/KS4031-KS4032.md/img-20230414152659.png) is displayed on dot matrix

When 68≤x<113, the next program will be executed
![Img](./FILES/KS4031-KS4032.md/img-20230414152717.png) is shown on dot matrix

When 113≤x<158，the next program will be executed

![Img](./FILES/KS4031-KS4032.md/img-20230414152615.png) pattern appears

![Img](./FILES/KS4031-KS4032.md/img-20230414152735.png)

![Img](./FILES/KS4031-KS4032.md/img-20230414152744.png)

When 158≤x<203, the next program will be executed.
Dot matrix shows![Img](./FILES/KS4031-KS4032.md/img-20230414152819.png)

When 203≤x<248,  the next program will be executed.
Dot matrix displays![Img](./FILES/KS4031-KS4032.md/img-20230414152831.png)

When 248≤x<293, the next program will be executed.
Dot matrix shows ![Img](./FILES/KS4031-KS4032.md/img-20230414152838.png)

When x is not among the above rang, the next program will be executed under else block.

Select“JavaScript" and“Python”to switch into JavaScript and Python language code:

![](media/7140a86db633ec1bb6ec7e07a109a0dc.png)

![](media/1d4fdac44bf4e1629145fac97f627c24.png)

**(4)Test Results:**

Upload code 2 and plug micro:bit into power. After calibration, tilt micro:bit board, and the LED dot matrix displays the direction signs.

([How to download?] [How to quick download?])

### Project 7: Accelerometer

![](media/24c31bb0174e2ac672203e5c36c6875e.png)

**(1)Project Description**

The micro:bit board has a built-in Freescale MMA8653FC three-axis acceleration sensor (accelerometer). Its I2C interface works on external communication, the range can be set to ±2g, ±4g, and ±8g, and the maximum data update rate can reach 800Hz.

When the Micro:bit is stationary or moving at a constant speed, the accelerometer only detects the gravitational acceleration; when the Micro:bit is slightly shaken, the acceleration detected is much smaller than the gravitational acceleration and can be ignored. Therefore, in the process of using Micro:bit, the main purpose is to detect the changes of the gravitational acceleration on the x, y, and z axes when the attitude changes.

For this project, we will introduce the detection of several special postures by the accelerometer.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码) Or click“New Project”and drag blocks step by step

**(3)Test Code**

**Code 1：**

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                        | File Name                  |
|-----------|---------------------------------------------------------------------------------------------|----------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 7：Accelerometer-1 | Project 7：Accelerometer-1 |

Or you could edit code step by step in the editing area.

(1) A. Enter“Input”→“on shake”，

B. Click“Basic”→“show number”, place it into“on shake”block, then change 0 into 1.![](media/b86b68744e64e4e9907ccb1fa0cb2af7.png)

(2) A. Copy code string ![](media/b86b68744e64e4e9907ccb1fa0cb2af7.png)for 7 times; separately click the triangle button to select“logo up”,“logo down”,“screen
up”,“screen down”,“tilt left”,“tilt right”and“free fall”, then respectively change 1 into 2, 3, 4, 5, 6, 7, 8.

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Complete Program：

![Img](./FILES/KS4031-KS4032.md/img-20230414155412.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414155444.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414155503.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414155522.png)

Click“JavaScript", you will view the corresponding JavaScript code:

![](media/ffd55d004aee7f100e1a2608c90f1c7c.png)

**Code 2：**

Detect the value of acceleration speed at x, y and z axis

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                        | File Name                  |
|-----------|---------------------------------------------------------------------------------------------|----------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 7：Accelerometer-2 | Project 7：Accelerometer-2 |

Or you could edit code step by step in the editing area.

A. Go to“Advanced”→“Serial”→“serial redirect to USB”

B. Drag it into“on start”

![](media/8c0cfdd76322ebf7febafa519e98b76f.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Enter“Serial”→“serial write value x =0”

B. Leave it into“forever”block

![](media/1dcff6f8c61c0c7ac220ded584bcf988.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*A.
Click“Input”→“acceleration(mg) x”；

B. Keep it into“0”box and capitalize the“x”

![](media/3f132064ad2081eabf6269eb4c0e698b.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Go to“Basic”and move out“pause (ms) 100”below the block![](media/aa23874d61a27c3af5263746851f6fef.png), then set to 100ms.

![](media/98c688ae175b0c5eca6bed1d95f7b301.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Replicate code string![](media/c013533f2e3a02f26116f176ba6f975b.png) for 3 times and keep them into“forever”block，separately set the whole code string as follows:

![](media/e11b467aef3999050e8a3b5cd175dce9.png)

Complete Program：

![](media/57fec5e7a6bda76b8ddc6c3538b58010.png) ![Img](./FILES/KS4031-KS4032.md/img-20230414155624.png)

Click“JavaScript" to view the corresponding JavaScript code:![](media/381a6d80fa940cb21ad6963469eef351.png)

Download code 1 to micro:bit board, keep USB cable connected and click![](media/e310a9105faecbe6ed8400101a4e852d.png)

([How to quick download?])

![](media/821a64a53c3a9709ff556e71b070f4dd.png)

After referring to the MMA8653FC data manual and the hardware schematic diagram of the Micro: Bit main board V2, the accelerometer coordinate of the Micro: Bit V2 motherboard are shown in the figure below:

![](media/6303a0ac122680207fe856d9be38d01c.png)

The following interface shows the decomposition value of acceleration in X axis, Y axis and Z axis respectively, as well as acceleration synthesis (acceleration synthesis of gravity and other external forces).

![](media/ded4e05f2b15d694e2061159628574dc.png)

If you're running Windows 7 or 8 instead of Windows 10, via Google Chrome won't be able to match devices. You'll need to use the CoolTerm serial monitor software to read data.

You could open CoolTerm software, click Options, select SerialPort, set COM port and put baud rate to 115200 (after testing, the baud rate of USB SerialPort communication on Micro: Bit main board V2 is 115200), click OK, and Connect. The CoolTerm serial monitor shows the data of X axis, Y axis and Z axis , as shown in the figures below :

![](media/b4f4201cccf6ac0dadffb952b7596895.png)

**(4)Test Results:**

After uploading the test code 1 to micro:bit main board V2 and powering the board via the USB cable, if we shake the Micro: Bit main board V2. no matter at any direction, the LED dot matrix displays the digit “1”.

([How to download?] [How to quick download?])

When it is kept upright （make its logo above the LED dot matrix）, the number 2 shows.

![](media/1600323e3e61e331c248cbeda5ccdcfc.jpeg)

When it is kept upside down( make its logo below the LED dot matrix) , it shows as below.

![](media/3be80acf957e53117f695801ce19c449.jpeg)

When it is placed still on the desk, showing its front side, the number 4 appears.

![](media/5797dd7be9a9c2d3226123e0c29db0bd.jpeg)

When it is placed still on the desk, showing its back side, the number 5 exhibits.

When the board is tilted to the left , the LED dot matrix shows the number 6 as shown below.

![](media/326095934bcff0a925b4f9a09d6cf7d2.jpeg)

When the board is tilted to the right , the LED dot matrix displays the number 7 as shown below

![](media/185b0ac204e9b2c54dd8fa93d852568c.jpeg)

When the board is knocked to the floor, this process can be considered as a free fall and the LED dot matrix shows the number 8. (please note that this test is not recommended for it may damage the main board.)

Attention: if you’d like to try this function, you can also set the acceleration to 3g, 6g or 8g. But still ,we do not recommend.

### Project 8: Light Detection

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

**(1)Project Description**

In this project, we focus on the light detection function of the Micro: Bit main board V2. It is achieved by the LED dot matrix since the main board is not equipped with a photoresistor.

When the light irradiates the LED matrix, the voltage change will be produced. Therefore, we could determine the light intensity by voltage change.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码)

Or click“New Project”and drag blocks step by step

**(3)Test Code**

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                        | File Name                  |
|-----------|---------------------------------------------------------------------------------------------|----------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 8：Light Detection | Project 8：Light Detection |

Or you could edit code step by step in the editing area.

(1)A. Enter“Advanced”→“Serial”→“serial redirect to USB”;

B. Drag it into“on start”block.![](media/8c0cfdd76322ebf7febafa519e98b76f.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

(2) A. Go to“Serial”→“serial write value x =0”;

B. Move it into“forever”![](media/1dcff6f8c61c0c7ac220ded584bcf988.png)

A. Click“Input”→“acceleration(mg) x”

B. Put“acceleration(mg) x”in the“0”box and change “x”into“Light intensity”.

![](media/38447eae9d3e190496b9a24baea6cbe7.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

A. Click“Basic”→“pause (ms) 100”;

B. Lay it down into“forever”and set to 100ms.

![](media/9ba8558c0d520cc80b01080e437ddff5.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Complete Program：

![Img](./FILES/KS4031-KS4032.md/img-20230414155844.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414155946.png)
                                                |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/7739b4e9b0603e04cdeb1c7051b9d2f8.png)

**(4) Test Results：**

Download code to micro:bit board don’t plug off USB cable and click![](media/e310a9105faecbe6ed8400101a4e852d.png)

([How to quick download?])

![](media/04b472326485cf676cdb4dd61ca6ef1a.png)

The intensity value is 0 when covering LED dot matrix. And the value varies with the light intensity. When placing micro:bit under the sunlight, the stronger the light is, the larger the intensity value is. As shown below:

![](media/d7f1751ea1e6f251376dee5390ed21fa.png)

Open“CoolTerm”, click“Options”to select “SerialPort”, and set “COM” port and 115200 baud rate(the baud rate of USB serial communication of micro:bit is 115200 through the test).

Then click“OK”and“Connect”. The light intensity value is shown below:

![](media/77a6de8ab9b171353693610a09f3a83c.png)

### Project 9: Speaker

![](media/ac515b9ae8891dc32f368a29f194a2fb.png)

**(1)Project Description**

The Micro: Bit main board V2 has an built-in speaker, which makes adding sound to the programs easier. We can program the speaker to air all kinds of tones, like playing the son *Ode to Joy.*

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?))

Or click“New Project”and drag blocks step by step

**(3)Test Code:**

The route to get test code（[How to load?]）

| File Type | Path                                                                                | File Name          |
|-----------|-------------------------------------------------------------------------------------|--------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project Code/Project 9：Speaker | Project 9：Speaker |

Or you could edit code step by step in the editing area.

Enter“Basic”module to find “show icon”and drag it into“on start”block;

Click the little triangle to find “![](media/7f7aa904c35f83b61c7c560ad1e40d2a.png)”

![](media/fed4c4f6e66e6d53fa2d8e10f01268fd.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

(2) Enter“Music”module to find and drug“play sound giggle until done” into “forever”block;

Enter“Basic”module to find and drug“pause(ms) 100” into “forever” block ;

Change 100 into 1000;

![](media/2a264656778216144131c75fabbbabf2.png)

( 3 ) Copy ![](media/39f8b940e6a1a3e8dbfa8eae70aa10c3.png) three times and place it into “forever” block ;

Click the little triangle to select “happy”,”hello”,”yawn”;

![](media/a8cee1c98866343f817d29e2ed97c584.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Complete Program：

![](media/ebd84db5c527208b9fa4c7bfd91c50a5.png)

Select “JavaScript" and “Python” to switch into JavaScript and Python language code:

![](media/984405217312d495104129a784ef76de.png)

![](media/99449615712dcb5903fe116a8255204b.png)

**(4)Test Results:**

After uploading the test code to micro:bit main board V2 and powering the board via the USB cable, the speaker utters sound and the LED dot matrix shows the logo of music.

([How to download?] [How to quick download?])

### Project 10: Touch-sensitive Logo

![](media/644695850097c5ade080bb4848b4b481.png)

**(1)Project Description**

The Micro: Bit main board V2 is equipped with a golden touch-sensitive logo, which can act as an input component and function like an extra button.

It contains a capacitive touch sensor that senses small changes in the electric field when pressed (or touched), just like your phone or tablet screen do.When you press it , you can activate the program.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码)

Or click“New Project”and drag blocks step by step

**(3)Test Code**

The route to get test code（[How to load?](##_5.5.导入代码：)）

| File Type | Path                                                                                 | File Name              |
|-----------|--------------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 10：Touch-sensitive Logo | Project 9：Speaker.hex |

Or you could edit code step by step in the editing area.

( 1 ) Delete block“on start”and“forever”;

( 2 )Enter“Input”module to find and drag“on logo pressed” ;

Click the little triangle to find“touched”;

![](media/b228ddd2c400e6cc11be3a87636c27be.png)

( 3 ) Enter module“Variables”→choose“Make a Variable”→input“start”→click“OK”

The variable“start”is established;

Enter“Variables”module to find and drag “set start to 0” into “on logo touched”block;

![](media/f425f9f9545f2d8300fbb0c8946b9ea3.png)

( 4 )Enter“Input”module →click “more”→ find and drag“running time(ms)”into the“0”of“set start to 0”block;

![](media/7af1f7fa05580ed5d588daf80351182c.png)

( 5 )Enter“Basic”module to find and drag“show icon![](media/f496ba08ff8af3164cdbd5fc56cc5abb.png)” into “on logo touched”block;

![](media/931663a2485eca2baa411b43484e5cc3.png)

( 6 )Enter“Input”module to find and drag“on logo pressed”→choose “released”→establish variable “time”;

Enter“Variables”module to find and drag “set time to 0”into “on logo pressed”block;

Enter“Math”module to find and drag “0-0”into the “0”of“set start to 0”block;

![](media/f2b9c02043be64c98da2e0ded2181082.png)

( 7 )Enter“Input”module→ “more” → find and drag “running time(ms)” into “0”on the left side of “0-0”;

Enter“Variables”module to find and drag“start” into “0”on the right side of “0-0”;

![](media/09e205a5774658821e5a988b63b39203.png)

( 8 )Enter“Basic”module to find and drag“show number” into “on logo released”block;

Enter“Math”module to find and drag“square root 0” into“0”; Click the little triangle to find”integer÷”;

![](media/5056fe4add2914acf570df6706ce0bb7.png)

( 9 ) Enter“Variables”module to find and drag“time”into“0”on the left side of“0-0”and change the“0”on the right side to”1000”;
![](media/a2247b14f9957f856485a927cfa7186e.png)

Complete Program：

![](media/bb847ad951cd721972d24fe0b90631a1.png)

Select“JavaScript" and“Python”to switch into JavaScript and Python language code:

![](media/15d6364778e29d2a05442c6cf01cc88d.png)

![](media/f63f0917317e2f8542961a88a5e6827f.png)

**(4)Test Results:**

After uploading the test code to micro:bit main board V2 and powering the board via the USB cable, the LED dot matrix exhibits the heart pattern when the touch-sensitive logo is pressed or touched and displays digit when the logo is released.

([How to download?] [How to quick download?])

### Project 11: Microphone

![](media/7f0741158e734ff8449d5b87d5ba85f4.png)

**(1)Project Description**

The Micro: Bit main board V2 is built with a microphone which can test the volume of ambient environment. When you clap, the microphone LED indicator turns on. Since it can measure the intensity of sound, you can make a noise scale or disco lighting changing with music. The microphone is placed on the opposite side of the microphone LED indicator and in proximity with holes that lets sound pass.When the board detects sound, the LED indicator lights up.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码)

Or click“New Project”and drag blocks step by step

**(3)Test Code**

**Code 1**

The route to get test code（[How to load?]）

| File Type | Path                                                                         | File Name                    |
|-----------|------------------------------------------------------------------------------|------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 11：Microphone-1 | Project 11：Microphone-1.hex |

Or you could edit code step by step in the editing area.

(1 ) Delete block“on start”and“forever”;

( 2 ) Enter“Input”module to find and drag“on loud sound”;

Enter“Basic”module to find and drag “show number”into “on loud sound”block ;

![](media/4fc47e876fa715d7e18b42f81aaf2f75.png)

( 3 )Copy ![](media/c7e2c46845a453f1de63b5e6f16af7fc.png) once;

Click the little triangle of “lond” to choose”quiet”;

Click the little triangle of “![](media/f496ba08ff8af3164cdbd5fc56cc5abb.png)” to choose”![](media/9a40d2f51ed0a372a82e559cdb2ca0dd.png)”;

![](media/2aa3293670d895afc772871026303399.png)

Complete Program：

![](media/b48689241988a3fda8de4e26ebd9a4ed.png)

Select“JavaScript" and“Python”to switch into JavaScript and Python language code:

![](media/e366483e9d5c574f3ec520f30e31e5cd.png)

![](media/fcba6eada2f29e11eee49a42987ab23e.png)

**(4)Test Results 1:**

After uploading test code to micro:bit main board V2 and powering the board via the USB cable, the LED dot matrix displays pattern “![](media/f496ba08ff8af3164cdbd5fc56cc5abb.png)”when you claps and pattern![](media/04fdfc9060943954e7938bb1a741d626.png) when it is quiet around.([How to download?] [How to quick download?])

**Code 2:**

The route to get test code（[How to load?]）

| File Type | Path                                                                         | File Name                    |
|-----------|------------------------------------------------------------------------------|------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 11：Microphone-2 | Project 11：Microphone-2.hex |

Or you could edit code step by step in the editing area.

Enter“Advanced”module→ choose“Serial”to find and drag“serial redirect to USB”into “on start”block ;

![](media/8c0cfdd76322ebf7febafa519e98b76f.png)

Enter“Variables”module→ choose“Make a Variable”→ input “maxSound”→click “OK”,variable ”maxSound”is established;

Enter“Variables”module to find and drag“set maxSound to 0”into “on start”block ;

![](media/39347e31badf7d15710fc12f581ce7e1.png)

Enter“Logic”module to find and drag“if true then...else”into “forever” block ;

Enter“Input”module to find and dragbutton A is pressed”into “then” ;

![](media/643d739679dd8891a240feda70868302.png)

Enter“Basic”module to find and drag“show number”into “then” ;

Enter“Variables”module to find and drag“maxSound”into “0” ;

![](media/eff0b22497be40e1826bccef95ceb0a4.png)

Establish variable“soundLevel”;

Enter“Variables”module to find and drag“set soundLevel to 0”into “else”;

Enter“Input”module to find and drag“sound level” into “0”;

![](media/c84fcdd7bfc4b545e420fa2d6a975bfe.png)

Enter“Led”module to find and drag“plot bar graph of 0 up to 0” into “else”;

Enter“Variables”module to find and drag“soundLevel”into the“0”behind “of”;

Change the “0”behind “up” to “255”;

![](media/adc684949503c334c505157743fdbc7b.png)

Enter“Logic”module to find and drag“if true then”into “else”block ;

Enter“Logic”module to find and drag“0 \> 0”into “then” ;

Enter“Variables”module to find and drag“soundLevel”into “0”on the left side of “0-0” ;

Enter“Variables”module to find and drag“maxSound” into “0” on the right side;

![](media/928f828756c965def348b56ef5299749.png)

Enter“Variables”module to find and drag“set maxSound to 0”into the second “then”;

Enter“Variables”module to find and drag“soundLevel”into the “0” ;

![](media/d62369e61dcc9dba69b80c93b1c7c7e8.png)

Complete Program：

![](media/c42455108c20d4ae51546957ab4198bb.png)

Select“JavaScript" and“Python”to switch into JavaScript and Python language code:

![](media/4e327f5f9ed716e6cf27cccba674f1c3.png)

![](media/e4adb50417583440e2620c1bb50528e1.png)

**(5)Test Results 2:**

Upload test code to micro:bit main board V2, power the board via the USB cable and click “Show console Device”as shown below.

( [How to quick download?])

![](media/e22507af4953df977269bbdb2463d69e.png)

When the sound is louder around, the sound value shows in the serial port is bigger as shown below.

![](media/50b81518d9f7925b0c20476ab1f64185.png)

What’s more, when pressing the button A, the LED dot matrix displays the value of the biggest volume( please note that the biggest volume can be reset via the Reset button on the other side of the board ) while when clapping, the LED dot matrix shows the pattern of the sound.

### Project 12: Bluetooth Wireless Communication

![](media/55b2424d88ba1ba8a711c49418ca8dc6.png)

**(1)Project Description**

The Micro: Bit main board V2 comes with a nRF52833 processor (with a built-in BLE(Bluetooth Low Energy) device Bluetooth 5.1 ) and a 2.4GHz antenna for Bluetooth wireless communication and 2.4GHz wireless communication. With the help of them, the board is able to communicate with a variety of Bluetooth devices, including smart phones and tablets.

In this project, we mainly concentrate on the Bluetooth wireless communication function of this main board. Linked with Bluetooth, it can transmit code or signals. To this end, we should connect an Apple device (a phone or an iPad) to the board.

Since setting up Android phones to achieve wireless transmission is similar to that of Apple devices, no need to illustrate again.

**(2)Experimental Preparation：**

-   Connect micro:bit to computer with the USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)](##_7.6.导入代码)

Or click“New Project”and drag blocks step by step

**(3)Procedures:**

For Apple devices, enter this link <https://www.microbit.org/get-started/user-guide/ble-ios/> with your computer
first, and then click “Download pairing HEX file”to download the Micro: Bit firmware to a folder or desk, and upload the downloaded firmware to the Micro: Bit main board V2.

![](media/cfaf7f8ae83cbe2636c39162a78adc7f.png)

![](media/6c1cef08d31fe3c4876b90ecc11554ff.jpeg)

![](media/63f1faf124af4949b31d7a84cee19a92.png)

Search “micro bit”in your App Store to download the APP micro:bit.

![](media/66d1f34d8d4c52e2b7c0ce10e602a063.png)

Connect your Apple device with Micro: Bit main board V2:

Firstly, turn on the Bluetooth of your Apple device and open the APP micro:bit to select item “Choose micro:bit”to start pairing Bluetooth.

Please make sure that the Micro: Bit main board V2 and your computer are still linked via the USB cable.

![](media/34f5fbb1c0c371970d1aec6c59c5cbb5.png)

Secondly, click“Pair a new micro:bit”;

![](media/e20270a0ade9c00b61198b26fc2fd83b.png)

Following the instructions to press button A and B at the same time(do not release them until you are told to) and press Reset & Power button for a few seconds.

Release the Reset & Power button, you will see a password pattern shows on the LED dot matrix. Now , release buttons A and B and click Next.

![](media/c00520400ecd1f20f958c1c6d1a3c907.png)

![](media/cabc60d7f8a030f5c9d86ac7de6c7bd7.png)

Set the password pattern on your Apple device as the same pattern showed on the matrix and click Next.

![](media/9411a5280e6f3b0d45306a31f80c1b38.png)

Still click Next and a dialog box props up as shown below. Then click "Pair". A few seconds later, the match is done and the LED dot matrix displays the "√" pattern.

![](media/803cb5cf5f7d595581a11f5e6b7e61ed.png)
![](media/f72e83dc6276d520e82c349659106e1a.png)

After the match with Bluetooth, write and upload code with the App.

Click “Create Code” to enter the programming page and write code. Click ![](media/f3e9cc7884f7bba807fa4633c429422b.png) and the box
![](media/e081360be7c91b7a156b01a787e4a58c.png) appears, and then select “Create √”.

![](media/d54bf2d1c01cd3c18544009b1f9dc5a0.png)

![](media/4e7a5d06a5f9a5a209ef5fbc005e9f62.png)

![](media/5bd84e8d293bf8c0c999c7f4e756cf30.png)

![](media/bd19bb4c97ad2a5bc300412b8eb93ede.png)

Name the code as “1 “and click ![](media/a32c2d832ab38d19eb623108143c744e.png) to save it.

![](media/25cf76f891c5eac7381b8095363a2748.png)

Click the third item“Flash”to enter the uploading page. The default code program for uploading is the one saved just now and named "1" and then click the other "Flash" to upload the code program "1".

![](media/c1661720ea2eaa521ff31a778501eb23.png)

![](media/350abcbb09d431d40427f34c3764f2eb.png)

![](media/4863bf826f119805a6a9bf9c12d5ec81.png)

If the code is uploaded successfully a few seconds later, the App will emerge as below and the LED dot matrix of the Micro: Bit main board V2 will exhibit a heart pattern.

![](media/ebfd31347a0553de0be4e01636652a15.png)

Projects above all conduct with the built-in sensors and the LED dot matrix of the main board while the following ones will carry out with the help of external sensors of this turtle car. **（Attention：to avoid burning the the Micro:bit main board V2, please remove the USB cable and the external power from the board before fix it with the shield of the car; likewise, the USB cable and the external power should be cut from the main board before disconnect the shield from the board.)**

### Project 13：Colorful Lights

![](media/f54b4dd3c57326c5f3a09e967c0e9ec1.png)

**(1)Project Description**

This module consists of a commonly used LED with 7colors but in white
appearance. It can automatically flash different colors to create fantastic
light effects when high level is input like a normal LED.

**(2)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?), or click “New Project”and drag blocks step by step(add MecanumRobot extension library first)

[**(How to add Mecanum_Robot extension?)**

**(3)Test Code**

**Code1**

Make the RGB light flash 7 lights alternatively.

Code path:

| File Type | Path                                                                                  | File Name                         |
|-----------|---------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 13：Colorful Lights-1.hex | Project 13：Colorful Lights-1.hex |

Or you could edit code step by step in the editing area.

Click“MecanumRobot”→find and drag![](media/1b7d690949953b411f6c2e623b51f0a9.png)指to“on start”;

Copy ![](media/1b7d690949953b411f6c2e623b51f0a9.png) once;

Click the little triangle behind “Left”to choose“Right”：![](media/1b065b7fa2d2ddf1a6baafad8bf5c064.png)

Compete Program:

![](media/1b065b7fa2d2ddf1a6baafad8bf5c064.png)

Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/76919447bd642ad2d6ccdcc02cd67110.png)

**Code 2：**

| File Type | Path                                                                                  | File Name                         |
|-----------|---------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 13：Colorful Lights-2.hex | Project 13：Colorful Lights-2.hex |

Or you could edit code step by step in the editing area.

Click“MecanumRobot” to find and drag![](media/1b7d690949953b411f6c2e623b51f0a9.png)to“forever”;

Copy ![](media/1b7d690949953b411f6c2e623b51f0a9.png) once;

Click the little triangle behind “Left”to choose“Right”：![](media/0baf5f83bcc2439212eba4d85eaa8a5d.png)

Click“Basic”to find and drag![](media/4acf410cb1c252408cf02c249890051e.png) and tap the little triangle to choose “1 second”![](media/c97a860956311188998d075dcc6871c9.png);

Copy ![](media/d0ce7b23b6f4546cfd8b146a4f1153dd.png)once and choose OFF
![](media/7d8a250effe60388a24f8b07a663e06d.png);

Put them in forever.

Complete Program:

![](media/bdce981c0ae66ebe881ff85892b06384.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414161255.png)

![](media/1d6fb6b29bd519440ec1ae7c83bccffb.png)

**(4)Test Results:**

Download code 1 to micro:bit board and dial POWER switch to ON end, 2 RGB lights of smart car emit red, green, blue, indigo, dark red, yellow and white color cyclically.

Download code 2 to micro:bit board, 2 RGB lights show different color cyclically.

([How to download?] [How to quick download?])

### Project 14：WS2812 RGB LEDs

![](media/eecf79fe278bc8107ce6827f9668f560.png)

**(1)Project Description**

The driver shield cooperates 4 pcs WS2812 RGB LEDs, compatible with micro:bit board and controlled by P8. In this lesson, we will make RGB LEDs display different colors by P8. In this lesson, 3 sets of test code are provided to make the 4 WS2812 RGB LEDs display different effects.

**(2)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

Import Hex profile (How to import?), or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

[**(How to add Mecanum_Robot extension?)**

**(3)Test Code**

**Code 1：**

| File Type | Path                                                                                  | File Name                         |
|-----------|---------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 14：WS2812 RGB LEDs-1.hex | Project 14：WS2812 RGB LEDs-1.hex |

Or you could edit code step by step in the editing area.

a. Enter“Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB (GRB format)”

b. Place it into“on start”block，

c. Signal end P8 of WS2812 RGB is controlled by P8 of micro:bit . So we set to P8.

d. Smart car has 4 pcs WS2812 RGB lights, so set to 4 leads

![](media/253b37d2d45744f944fc3521af50855c.png)

Click“Neopixel”to move block“strip clear”into“on start”block.

![](media/9287db5ccffb51dd82e5d2a15d2fd2fc.png)

Enter“Neopixel”to move block“strip show color red” into “forever” block

![](media/88de3d44c971c2369711430a893d7821.png)

Click“Basic”to move“pause (ms) 100”block into“forever”block

Then set to 1000ms

![](media/ba93a1de285dc713513a788b420e3ce6.png)

Copy code string ![](media/e553a68f56eba016892b29528e711907.png)for eight times, and click red to respectively set to orange, yellow, green, blue, indigo, violet, purple and white.

Tap the triangle icon to select orange, yellow, green, blue, indigo, violet, purple and white.

![](media/156cd64dce0b25f741f7d2f9a08f8e5d.png)

Complete Code

| ![](media/b2cdf8ccae177a77965bb692e7f0bff1.png)     |
![Img](./FILES/KS4031-KS4032.md/img-20230414161502.png)

Click“JavaScript" to switch into the corresponding JavaScript
code:![](media/b6d38140d551a1c946e82f1da11edb1c.png)

**Code 2：**

| File Type | Path                                                                                  | File Name                         |
|-----------|---------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 14：WS2812 RGB LEDs-2.hex | Project 14：WS2812 RGB LEDs-2.hex |

a. Enter“Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB (GRB format)”

b. Place it into“on start”block，

c. Signal end P8 of WS2812 RGB is controlled by P8 of micro:bit . So we set to P8.

d. Smart car has 4 pcs WS2812 RGB lights, so set to 4 leads

![](media/1b10418150f245ba56a4208755729094.png)

Click“Loops”to drag“for index from 0 to 4...do”into“forever”block

Change 4 into 3

![](media/9c42b551fc532d473414871e64c8a5ee.png)

Click“Neopixel”to move block“strip clear”into block“for index from 0 to 3...do”

![](media/aa478b7456e1860d1665cab16014fc13.png)

Tap“Neopixel”→“more”→“strip set pixel color at 0 to red”

Place it into“for index from 0 to 3...do”block

Click“Variables”to move“index”into 0 box

![](media/360081c03f2f475441c442a601334ce2.png)

Click“Neopixel”to move“strip show”into“for index from 0 to 3...do” block

![](media/51d0ac03e131f1c42b67f4fd2631a7a0.png)

Tap“Basic”to move “pause (ms) 100”block into“index from 0 to 3...do”

![](media/eda2a23160cf34a76c1f4ab73118151d.png)

Replicate code string![](media/b8590766809462fa433eb907d60e8908.png)for eight times and place them into“forever”block

Click red to respectively choose orange, yellow, green, blue, indigo, violet, purple and white

Complete Code：

| ![](media/f06b9905088a3d39373f78c947e64be3.png)  |
|------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                      |

Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/e504dfc47f7d7bdd5f55e8d191e10ed2.png)

![](media/7ef1503e633be63a18bb5128f0784a6e.png)

**Code 3：**

| File Type | Path                                                                                  | File Name                         |
|-----------|---------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 14：WS2812 RGB LEDs-3.hex | Project 14：WS2812 RGB LEDs-3.hex |

Or you could edit code step by step in the editing area.

a. Enter“Neopixel” →“set strip to Neopixel at pin P0 with 24 leds as RGB (GRB format)”

b. Place it into“on start”block，

c. Signal end P8 of WS2812 RGB is controlled by P8 of micro:bit . So we set to P8.

d. Smart car has 4 pcs WS2812 RGB lights, set to 4 leads

![](media/1b10418150f245ba56a4208755729094.png)

Click“Variables”→“Make a Variable...”

Input R to build up variable R

We create variable“G”and“B”in same way

Drag“set B to 0”into“on start”block

Copy“set B to 0”twice and click triangle button to choose G and B

![](media/0e2475d942586c2733a8fced49c3b26b.png)

Click“Loops”to get block“for index from 0 to 4...do”

Leave it into “forever”and change 4 into 3

![](media/00751ac422252c11b90e88d1dd5e5e1b.png)

Move block“set B to 0”into“for index from 0 to 3...do”block,

Click B to choose R

Go to“Math”to drag block“pick random 0 to 10”into 0 box

Change 0 into 10, 10 into 255

![](media/808240f2784ec6bf5cd696813178ad51.png)

Replicate block ![](media/141700e2baf4f6ec06126a7eabdd15c3.png)twice and place
them into“for index from 0 to 3...do”block.

Click R to select G and B

![](media/18c0be6843e83bf51f99c240d0faa45c.png)

Tap“Neopixel”and move“strip clear”into“for index from 0 to 3...do” block.

![](media/cbc6b59e73365b0038a11a465b775f18.png)

Go to“Neopixel”→“more”→“strip set pixel color at 0 to red”

Leave it in the block“for index from 0 to 3...do”block

Drag block“red 255 green 255 blue 255”into“red”box

Tap“Variables”to move“index”block into 0 box

Separately drag R , G and B into 255 box, as shown below:

![](media/965b62ff435a6c5b35ef77745474b976.png)

Click“Basic”to drag“pause (ms) 100” under block “strip.....B”

Set to 500ms.

![](media/ef0a30f6ea2627dbee666c6a7139c404.png)

Click“Neopixel”to move“strip show”block under “pause(as) 500”

![](media/7d0ee3ddfa68a63b292c77709dc20e89.png)

Complete Code:

![Img](./FILES/KS4031-KS4032.md/img-20230414161828.png)
                                                |
![Img](./FILES/KS4031-KS4032.md/img-20230414161729.png)

![Img](./FILES/KS4031-KS4032.md/img-20230414161850.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414162011.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414162059.png)

Click“JavaScript" to switch into the corresponding JavaScript code:![](media/a2680aaeb505419bb229de36ffc8a48d.png)

**(4)Test Results:**

Download code 1 to micro：bit, and dial POWER to ON end. All four WS2812RGB LEDs light up a different color a time cyclically.

Download code 2 to micro：bit, WS2812RGB LEDs display like flow light.

Download code 3 to micro：bit, every WS2812RGB light shows random color one by one.

(How to download?] [How to quick download?)

### Project 15：Servo

![](media/ae51208a3f560ad6edefe370eb588c13.png)

**(1)Project Description**

For those DIY smart cars, they often have the function of automatic obstacle avoidance. In the DIY process, we need a servo to control the ultrasonic module to rotate left and right, and then detect the distance between the car and the obstacle, so as to control the car to avoid the obstacle. If other microcontrollers are used to control the rotation of the servo, we need to set a
certain frequency and a certain width of pulse to control the servo angle. But if the micro:bit main board is used to control the servo angle, we only need to set the control angle in the development environment where the corresponding pulse will be automatically set to control the servo rotation.

In this project, you will learn how to control the servo to rotate back and forth between 0° and 90°.

**(2)Background Information of the Servo**

Servo motor is a position control rotary actuator. It mainly consists of housing, circuit board, core-less motor, gear and position sensor. Its working principle is that the servo receives the signal sent by MCU or receiver, and produces a reference signal with a period of 20ms and width of 1.5ms, then compares the acquired DC bias voltage to the voltage of the potentiometer and obtains the voltage difference output.

![](media/69be958142b773acdae33eeef12afed7.png)
For the servo used in this project, the brown wire is the ground, the red one is the positive wire, and the orange one is the signal wire.

The rotation angle of servo motor is controlled by regulating the duty cycle of PWM (Pulse-Width Modulation) signal. The standard cycle of PWM signal is 20ms (50Hz). Theoretically, the width is distributed between 1ms-2ms, but in fact, it's between 0.5ms-2.5ms. The width corresponds to the rotation angle from 0° to 180°. But note that for different brand motor, the same signal may have different rotation angle.

![](media/49467dfa70799401a5a5acc691014aee.png)

**More details:**

![](media/ddc74f62dc936c925d28d70a1a9c2214.png)

**(3)Parameters:**

-   Working voltage: DC 4.8V \~ 6V

-   Operating angle range: about 180 ° (at 500 → 2500 μsec)

-   Pulse width range: 500 → 2500 μsec

-   No-load speed: 0.12 ± 0.01 sec / 60 (DC 4.8V) 0.1 ± 0.01 sec / 60 (DC 6V)

-   No-load current: 200 ± 20mA (DC 4.8V) 220 ± 20mA (DC 6V)

-   Stopping torque: 1.3 ± 0.01kg · cm (DC 4.8V) 1.5 ± 0.1kg · cm (DC 6V)

-   Stop current: ≦ 850mA (DC 4.8V) ≦ 1000mA (DC 6V)

-   Standby current: 3 ± 1mA (DC 4.8V) 4 ± 1mA (DC 6V)

**(4)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile **(How to import?)** , or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add Mecanum_Robot extension?)**

**(5)Test Code:**

Code path:

| File Type | Path                                                                      | File Name             |
|-----------|---------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 15：Servo.hex | Project 15：Servo.hex |

Or you could edit code step by step in the editing area.

(1)Click“Variables”; motor“Make a Variable name” create a variable named“angle”; set the value to 0：![](media/6f5afff91a08cadd05caa1dbfda3a566.png); and then put it into“on start”![](media/84aa43c617547629c6ab018cdc5dedf6.png);

(2)Click“Loops”to find and drag![](media/931d144427e762093f77c1ccf0f25422.png)to“forever”and change the
number to“180”; click“MecanumRobot”to find and drag![](media/44064d42ba3784766ed2b3bd7f9a5bde.png)and put variable“angle”into
![](media/620f22e6a5c51998bac55eb189e93641.png); put into![](media/0746e3def9d7062499d34f5dfe16be04.png);

Click![](media/bc874b1942f1a9471481445e610d665b.png) of “Variable” and ![](media/e6064b33ba089a52a096df76f0ac5673.png) of “Math”;put variable”angle” on the left and change the umber on the right to 1:![](media/ba828b1c44af9db7c09d7a3da822eb52.png);put it into![](media/2e15452c0b7780dce74438e03575f989.png);

Put behind![](media/620f22e6a5c51998bac55eb189e93641.png)and add delay in 10ms![](media/ab7ef2718c3ba5241c90eb2bfd1247dc.png);

Copy ![](media/ab7ef2718c3ba5241c90eb2bfd1247dc.png)once and change the “+”of ![](media/ba828b1c44af9db7c09d7a3da822eb52.png) to “-”：![](media/2945c3f78c0a9eb3cc5e552361fd1039.png).

Complete Program:

![](media/087e18229bba5f7a01520f80f8c8187c.png)
① The "on start" command block runs only once to start the program.

②Set the initial value of the angle variable to 0.

③In the "forever" command box, the program runs cyclically

④Cycle 180 times

⑤Rotate the servo to angle

⑥ Angle variable increases 1

⑦ Delay in 10ms

⑧ Cycle 180 times

⑨The servo rotates to angle

⑩Angle angle variable minus 1

⑪ Delay in 10ms


Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/ff552b6c0cc5df28394b7b621f033073.png)

**(6)Test Results:**

After uploading the test code and dial POWER switch to ON end, the servo rotates from 0 degree to 180 degrees.

(How to download?] [How to quick download?)

### Project 16：Motor

![](media/02a16adfdabb92d6de1796019e909b44.png)

**(1)Project Description**

The Keyestudio 4WD Mecanum Robot Car is equipped with 4 DC reduction motors, also called gear reduction motor, which is developed on the ordinary DC motor. It has a matching gear reduction box which provides a lower speed but a larger
torque. Furthermore, different reduction ratios of the box can provide different speeds and torques.

Gear motor is the integration of gearmotor and motor, which is applied widely in
steel and machine industry

Micro:bit motor driver shield comes with PCA9685PW and TB6612FNG chip. In order to save the IO port resource, we control the rotation direction and speed of two DC gear motors with TB6612FNG chip.

**Details about chips:**

![](media/b061e1e1de11c11a3cb574be828d5aeb.jpeg)

**Front**

![](media/52abdd5c7c1729900fa74e60b6723509.jpeg)

**Back**

![](media/c375b465ed06b0aae6db7239e059439a.jpeg)

![](media/bb34948dc48790c4a86ac67e531a93e1.jpeg)

**(2)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile [(How to import?)], or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**How to add MecanumRobot extension?)**

**(3)Test Code：**

**Code 1：**

| File Type | Path                                                                        | File Name               |
|-----------|-----------------------------------------------------------------------------|-------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 16：Motor-1.hex | Project 16：Motor-1.hex |

Or you could edit code step by step in the editing area.

(1)Click“ MecanumRobot”to find and drag![](media/3017a4c47b2a4799211969fc4ce21431.png) into“forever”;click the number behind speed to choose 75![](media/985053c970402019e2b0afe192bc75e0.png);

(2)Copy![](media/985053c970402019e2b0afe192bc75e0.png)four times;click the little triangle behind “Motor”to choose Lower_left，Upper_right，Lower_right respectively; and put them all in forever![](media/4840d3f08ec9f7c0275fd434508c912a.png);

(2)Click“Basic”to find and drag“pause (ms) 100”to“forever”;set delay in 2000ms![](media/a25e088e3c77ee16fe1b0935d9edf225.png);

(3)Click“MecanumRobot”to find and drag![](media/150c1bfa02df1e644c84ba32fb889fee.png) to ![](media/a25e088e3c77ee16fe1b0935d9edf225.png); copy ![](media/a25e088e3c77ee16fe1b0935d9edf225.png) once and put it behind![](media/150c1bfa02df1e644c84ba32fb889fee.png).

Complete Program:

![](media/3a759dd8c19a12c8294cd4a56348e0b2.png)
① In the "forever" instruction block, the program runs cyclically.

②Set the front left motor speed to 75, and rotate clockwise.

③Set the speed of the rear left motor to 75 and the direction to rotate clockwise.

④Set the front right motor speed to 75 and the direction to rotate clockwise.

⑤Set the right rear motor speed to 75 and the direction to rotate clockwise

⑥The delay time is 2000 milliseconds

⑦4 motors stop rotating

⑧ Delay time 2000 milliseconds


Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/ea1088e16bf16c9dcdab0151da6fdc0a.png)

**Code2：**

Code path:

| File Type | Path                                                                        | File Name               |
|-----------|-----------------------------------------------------------------------------|-------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 16：Motor-2.hex | Project 16：Motor-2.hex |

Or you could edit code step by step in the editing area.

Drag and copy![](media/e91c5fef0c025bd9de44a28cf59d3aa2.png)three times; click the little triangle behind”run”to choose as shown![](media/cf2444064b87720b5b46594f5ed6a1c2.png)，
![](media/b5270c6c0e52b74e77cf4cd9e139f076.png)，![](media/d69b7c823cc3d2f2dfae31c4bec643a4.png)

And then put they all in forever and add ![](media/44b76cae1d08f206e202e53e84191baf.png).

Complete Program:

![](media/a3a9d39aafc4162630ad4740cbc08462.png)

![](media/c3697cf4e65ba9983bfc4a4bd3892a94.png)

① In the "forever" instruction block, the program runs cyclically.

②Set the front left motor speed to 75 and the direction to rotate forward.

③Set the speed of the rear left motor to 75 and the direction to rotate forward.

④Set the front right motor speed to 75 and the direction to rotate forward.

⑤Set the right rear motor speed to 75 and the direction to rotate forward.

⑥Wait for 2 seconds

⑦Set the front left motor speed to 75, and the direction is reversed.

⑧ Set the motor speed at the rear left to 75, and the direction is reversed.

⑨Set the front right motor speed to 75, and the direction is reversed.

⑩Set the right rear motor speed to 75, and the direction is reversed.

⑪Wait for 2 seconds

⑫Set the front left motor speed to 75, and the direction is reversed.

⑬Set the motor speed at the rear left to 75, and the direction is reversed.

⑭ Set the front right motor speed to 75 and the direction to rotate forward.

⑮ Set the right rear motor speed to 75, the direction is forward.

⑯Wait for 2 seconds

⑰ Set the front left motor speed to 75 and the direction to rotate forward.

⑱ Set the speed of the rear left motor to 75 and the direction to rotate forward.

⑲Set the front right motor speed to 75, and the direction is reversed.

⑳ Set the right rear motor speed to 75, and the direction is reversed.

㉑Wait for 2 seconds

㉒The car stops

㉓Wait for 2 seconds


Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/d78d64696e9441e70a40c137754095a4.png)

**(4)Test Results:**

Download code 1 to micro:bit board, dial POWER switch to ON end. Smart car goes forward for 2s and stops for 2s.

Download code 2 to micro:bit board, the car goes forward for 2s, turns back for 2s, turn left for 2s, turn right for 2s and stops for 2s and repeats this pattern.

([How to download?] [How to quick download?])

### Project 17：Line Tracking Sensor

 **17.1: Detect Line Tracking Sensor**

![](media/bca630b5637ffb27422d810cf983dd23.png)

**(1)Project Description**

The motor driving board of the Keyestudio 4WD Mecanum Robot Car comes with a dual-channel line tracking sensors which adopt TCRT5000 IR tubes and 2 potentiometers. TCRT5000 IR tube has an IR emitting tube and a receiving tube.

Low level(0) is output when IR transmitting tube emits IR signals to receiving tube; high level(1) will be output when smart car runs along black line.

When smart car drives on the white ground, TCRT5000 IR tube will emit IR signals which will be reflected by white ground and received by receiving tube, consequently output low level(0); on the contrary, when driving on the black surface, the high level is output.

**(2)Working Principle:**

When the car runs above a white road, the infrared transmitter tube installed under the car emits infrared signals to detect the road and the receiver tube receives signals sending back. Then the output end outputs low level(0); when it
detects black lines, it outputs high level(1).

The 2-way tracking sensor integrated port on the 4WD Mecanum Robot Car is connected to the collection port of G ,5V ,P1 and P2 on the micro:bit expansion board, which is controlled by the P1 and P2 of the micro:bit. The left TCRT5000 infrared pair tube on the sensor is controlled by P1, and the right one by P2.

After putting a white paper on the bottom of the 4WD Mecanum Robot Car,we rotate the two potentiometers on the 2-way tracking sensor. When the indicator light on the sensor module is on, pick up the car to make the two wheels on the 4WD
Mecanum Robot Car separate. The height of the white paper is about 1.5cm, the indicator light on the sensor module is off, and then the sensitivity is adjusted.

**(3)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?) , or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)**

**(4)Test Code:**

**Code1：**

| File Type | Path                                                                                            | File Name                                   |
|-----------|-------------------------------------------------------------------------------------------------|---------------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 17.1：Detect Line Tracking Sensor-1 | Project 17.1：Detect Line Tracking Sensor-1 |

Or you could edit code step by step in the editing area.

Click“Advanced”→“Serial”→“serial redirect to USB”

Place it into“on start”

![](media/73b63660eb8f378dea4930f354d04de6.png)

Enter“Advanced”→“Serial”→![](media/9eb34e5ce5a67b9327096c00fb9036bc.png)

Leave it into“forever”block.

Go to“Pins”→“digital read pin P0 ”

Move“digital read pin P0”into 0 box

The right tracking sensor is controlled by P14. Then change P0 into P14 and“x”into“digital signal”.

Click“Advanced”→“Serial”to find and drag![](media/9eb34e5ce5a67b9327096c00fb9036bc.png)t“forever”;

input”left:”![](media/e8983c9a50c5adce42954a3e59e3b259.png) and drag it again;

Click“MecanumRobot”to find and drag![](media/49b8d87a5ea9bea061c76df982013622.png) to![](media/f563baf7a888a937afb40dc40031b795.png);

Copy ![](media/e8983c9a50c5adce42954a3e59e3b259.png)once and change ”left:” to “ right:”![](media/05335c3123a1b348b8d973a7568888f1.png);

Copy![](media/f563baf7a888a937afb40dc40031b795.png)once and change Leftto
Right![](media/a601e50542947b818d8122a2fc44bb87.png);

Drag ![](media/e16ec6add35ef78b91f5da5266b2ef86.png);

Click“Basic”to find and drag“pause (ms) 100”to“forever”and set delay in 200ms: ![](media/a3c3d352b42fd3337805de73a97e778b.png)

Complete Program:

![](media/3683d83f8320256e3c74aa9a79aea314.png)
① The "on start" command block runs only once to start the program.

②Serial redirection USB.

③In the "forever" instruction block, the program runs cyclically.

④Write string "left:" serially

⑤Serially write the output value of the tracking sensor on the left

⑥Serial write string "right:"

⑦Serially write the output value of the tracking sensor on the right

⑧Writing in line break

⑨ Delay time 200 milliseconds


Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/7e08b5bccce6ddb228991e79f05f55c3.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud rate. Click“OK”and“Connect”.

The CoolTerm serial monitor displays the digital signals read by right line tracking sensors.

![](media/2fe11256f4491511fbc7a6d5381895f0.png)

**Code 2：**

Code path:

| File Type | Path                                                                                            | File Name                                   |
|-----------|-------------------------------------------------------------------------------------------------|---------------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 17.1：Detect Line Tracking Sensor-2 | Project 17.1：Detect Line Tracking Sensor-2 |

Or you could edit code step by step in the editing area.

Click“Variables” and then click“Make a Variable...”;

The dialog box“New variable name：”pops up and fill it with “LL”;

Click“OK”to establish variable“LL”;

To establish variable “RR” in the same way;

Find and drag“set RR to 0”to“on start”;

Copy“set RR to 0”once and place it to “on start”;

Click the little triangle behind “RR” to choose “LL”:

![](media/f7f2c03977db2533023b04aac17bddd4.png)

Click“Variables”to find and drag “set RR to 0”to“forever”;

Click the little triangle behind “RR”to choose LL；

Click“MecanumRobot”to find and drag![](media/e8127d7dca199be6ab37125b77eceba3.png)to the “0”behind “to”;

Copy![](media/1e7830f494273fa198395ae1fe17560e.png)once and place it to“forever” and change the second “LL”to “RR”, and ”Left”to ”Right”:

![](media/90b155ad66054eb2ae30cdd3abb98b9c.png)

Click“Logic”to find and drag“if true then...else”to“forever”;

Click“![](media/7498c9151101cb7e9756a8b0a5485f90.png)”twice and find and drag an“and”to “true”;

Drag a“=”to “and”:

![](media/87f0ef69566409779d48a7b72163f6e7.png)

Click“Variables”to find and drag“LL”to the left side of“=”;the 0 on the right of“=”remains unchanged;

Copy“LL”1 once and place it to the right of“and”;

Click the little triangle behind“LL”to choose“RR”and change the “0”to“1”:

![](media/092c54bd7fa288a3b50cf0568bbfedd3.png)

Click“Basic”to find and drag“show leds”to the first”then”; Click the blocks to form pattern“←”:

![](media/acfd503f9cefd92feed8f1a4b37df78e.png)

Copy“LL=0 and RR=1”once and place it behind the first“else if”, change the first 0 to 1, and the first 0 behind LL to 1; others remain unchanged:

![](media/d66a80ca5500aa98d0239742910c1237.png)

Click“Basic”to find and drag“show leds”to the second “then”;

Click the blocks to form pattern →”:

![](media/ac32c1b9de88da03d0b0eca2a9591c9c.png)

Copy“LL=1 and RR=0”once and place it to “else if” and change the first number 1 behind LL to 0:

![](media/0205c0b033aa2db6b254e486f0dfefb7.png)

Click“Basic”to find and drag“show leds”to the third else;

Click these blocks to form the pattern “×”:

![](media/51c07fc122608fb2b3785f3c91f3829f.png)

Click“Basic”to find and drag“show leds”to else;

Click these blocks to form the pattern“×”:

![](media/d1d990cb9a4f596371979df27dd3271e.png)

Complete Program:

![](media/6e6cf4461945ba8b50f0be6cd421feae.png)

![](media/2c002c25f48caf848c64adace0b5d26f.png)
① The "on start" command block runs only once to start the program.

②Set the variable LL to 0

③Set variable RR to 0

④In the "forever" instruction block, the program runs cyclically.

⑤Set the variable LL to the digital signal read on the left (1/0)

⑥Set the variable RR to the digital signal read on the right (1/0)

⑦When the variables LL=0 and RR=1 are established, execute the program under then

⑧The left side of the LED dot matrix displays the "←" pattern

⑨When the variables LL=1 and RR=0 are established, execute the program under then

⑩The "→" pattern is displayed on the left of the LED dot matrix

⑪When the variables LL=0 and RR=0 are established, execute the program under then

⑫The "×" pattern is displayed on the left side of the LED dot matrix

⑬When the above conditions are not met, execute the program under else


Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/31041df9a66787478c8b0a6f6b3a5034.png)

**(5)Test Results:**

Download code 2 to the micro:bit, when only the left TCRT5000 infrared pair tube on the line tracking sensor detects a white object, the micro bit LED dot matrix displays a "←" pattern, and the indicator light on the left side of the tracking sensor lights up;

When only the right TCRT5000 infrared pair tube on the sensor detects a white object, the micro bit LED dot matrix displays a "→" pattern, and the indicator light on the right side of the tracking sensor lights up;

([How to download?] [How to quick download?])

**17.2: Line Tracking Smart Car**

![](media/e61a7422305ab189b920b6718e4d2ef1.jpeg)

**(1)Project Description**

In this lesson we will combine line tracking sensors with a motor to make a line tracking smart car.

The micro:bit board will analyze the signals and control smart car to show line tracking function.

**(2)The Working Principle**

The smart car will make different moves according to the value received by the 3 channel line tracking sensor.

| Left/Right TCRT5000  IR Tunes（Level） | 4WD Mecanum Robot Car |             |
|----------------------------------------|-----------------------|-------------|
| LOW（0）                               | HIGH（1）             | Turn Right  |
| HIGH（1）                              | LOW（0）              | Turn Left   |
| HIGH（1）                              | HIGH（1）             | Go forward  |
| LOW（0）                               | LOW（0）              | Stop        |

**(2)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?) , or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)**

Warning: The 2-way tracking sensor should be used in environments without infrared interference such as sunlight. Sunlight contains a lot of invisible light, such as infrared and ultraviolet. In an environment with strong sunlight, the 2-way tracking sensor cannot work properly.

**(3)Flow Chart:**
![Img](./FILES/KS4031-KS4032.md/img-20230414163558.png)

**(4)Test Code:**

Code path:

| File Type | Path                                                                                          | File Name                                 |
|-----------|-----------------------------------------------------------------------------------------------|-------------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 17.2：Line Tracking Smart Car.hex | Project 17.2：Line Tracking Smart Car.hex |

Or you could edit code step by step in the editing area.

No need to create variable LL and RR but use ![](media/759604b84fbe3b80608edec46290854d.png)and ![](media/1334fa6eaf6eec8e15670db47f6832af.png)to decide:![](media/db0f65e9e8f2c9d41b36ae4e00e71446.png)

Click Functions” of ”Advance”and then tap“Make a Function”:![](media/7bff09ac7145d2ee7d4e32e08fdb4f10.png);change“doSomething”to
“car_forward”，“car_back”，“car_left”，“car_right”respectively:![](media/ef2f1b39f401e3331e7b5e616af4402c.png)

![](media/09bf0b11083a14fff48108251d3157d8.png)

Click “Functions”of ”Advance”to find and drag ![](media/460d5b4f97487f6163fbdc629bc8c849.png) to the first

if and drag![](media/ae70f5e341da2beb5bccb6f3188a6c9c.png) to the first else if;

Find and drag![](media/6f8a414e870e55bf08884a70d8368ed5.png)to the last else;

Click“MecanumRobot”to find and drag![](media/b33aa5fba3096eabc60bff5f62e36d65.png)to the second else if:

![](media/a9adc30039f4342fa86039ae9d064509.png)

Complete Program:

![](media/9e32d998d0019ee69114a68eb90c0269.png)

![](media/3f8c9ca155ee96f39b06d853502d4840.png)

![](media/2ee5c31fa0e945182b66a40c72f820aa.png)

①forward function

②The front left motor rotates forward at a speed of 40

③The motor at the rear left rotates forward at a speed of 40

④The front right motor rotates forward at a speed of 40

⑤The rear right motor rotates forward at a speed of 40

⑥Backward function

⑦The front left motor reverses, the speed is 40

⑧The rear left motor reverses, the speed is 40

⑨The front right motor reverses, the speed is 40

⑩The rear right motor reverses, the speed is 40

⑪Left turn function

⑫The front left motor reverses, the speed is 60

⑬The rear left motor reverses at a speed of 60

⑭The front right motor rotates forward, the speed is 85

⑮The right rear motor rotates forward, the speed is 85

⑯Right turn function

⑰The front left motor rotates forward, the speed is 85

⑱The rear left motor rotates forward, the speed is 85

⑲The front right motor reverses, the speed is 60

⑳The rear right motor reverses, the speed is 60


Click“JavaScript"to view the corresponding JavaScript code:

![](media/fb585c28a5a44ae8bf97f5c78afa4b1a.png)

**(5)Test Results:**

Download code to micro:bit and dial POWER to ON end, line tacking car goes forward along black line .

Note: turn on the switch at the back of micro:bit car, the width of black line should be larger than the width of line tracking sensor. Avoid to test smart car under the strong light.

### Project 18: Ultrasonic Follow Smart Car

**18.1: Ultrasonic Ranging**

**(1)Project Description**

The ultrasonic sensor uses sonar to determine distance to an object like bats do. It offers excellent non-contact range detection with high accuracy and stable readings in an easy-to-use package. It comes complete with ultrasonic transmitter and receiver modules.

The ultrasonic sensor is being used in a wide range of electronics projects for creating obstacle detection and distance measuring application as well as various other applications.

As the above picture shown, it is like two eyes. One is transmitting end, the other is receiving end.

The ultrasonic module will emit the ultrasonic waves after trigger signal. When the ultrasonic waves encounter the object and are reflected back, the module outputs an echo signal, so it can determine the distance of object from the time difference between trigger signal (TRIG)and echo signal(ECHO).

![](media/51a73598d6bb68d3d529e40336593278.png)

According to the above wiring diagram, the integrated port of the ultrasonic sensor module is connected to the 5V G P15 P16 port on the micro:bit motor drive backplane. The Trig (T) pin is controlled by P15 of the micro:bit and the pin of Echo (E) the P16.

**(2)Working Principle:**

![](media/8ff02741199a0f03d8d814a4b72f27d7.png)

Pull down TRIG then trigger high level signals with least 10us

After triggering, the module will automatically send eight 40KHz ultrasonic pulses and detect whether there is a signal return.

The propagation speed of sound in the air is about 340m/s, therefore, distance = speed \* time, because the ultrasonic wave emits and comes back, which is 2 times of distance, so it needs to be divided by 2, the distance measured by ultrasonic wave = (speed \* time)/2

**(3)Parameters:**

-   Working voltage: 3-5.5V (DC)

-   Working current: 15mA

-   Working frequency: 40khz

-   Maximum detection distance: about 3m

-   Minimum detection distance: 2-3cm

-   Precision: up to 0.2cm

-   Sensing angle: less than 15 degrees

-   Input trigger pulse: 10us TTL level

-   Output echo signal: output TTL level signal (high), proportional to range

**(4)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?) , or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)**

**(5)Test Code:**

| File Type | Path                                                                                      | File Name                             |
|-----------|-------------------------------------------------------------------------------------------|---------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 18.1： Ultrasonic Ranging.hex | Project 18.1： Ultrasonic Ranging.hex |

Or you could edit code step by step in the editing area.

(1)Tap“Advanced”→“Serial” →“serial redirect to USB”

Combine it with“on start”block

![](media/73b63660eb8f378dea4930f354d04de6.png)

(2)Click“Advanced”→“Serial” to find and drag“serial write value x=0”into“forever”; Click“MecanumRobot”to find and drag“Ultrasonic”to the 0 on the right side of“serial write value x=0”and change the x on the left side of “=”to distance:

![](media/390b1b8e952e923bbeb561c0fc9a0520.png)

(2) find and drag![](media/0788feefa06aeed58a3f7ff4a85f3848.png)of “Basic”,and change 100 to 200and place it behind![](media/039569dc23c7ff4a5577eea1a890eca4.png)

Complete Program:

![](media/497760b1d2daeec2134c8ed8fa89d130.png)
① The "on start" command block runs only once to start the program.

②Serial redirection USB

③In the "forever" instruction block, the program runs cyclically.

④Serial write value distance=Ultrasonic

⑤ Delay time 200 milliseconds


Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/f40acd137b44344724bc0e50e51eb5c3.png)

**(6)Test Results:**

Download code to micro:bit, keep USB cable connected, dial POWER switch to ON end. The distance value will be displayed on monitor.

(How to quick download?)

![](media/2cd74c16ab3623f6752d3f5e59deea2e.png)

The monitor shows the distance between the obstacle and ultrasonic sensor(as shown below). When the distance is less than 10cm, the passive buzzer of smart car emits sound.

![](media/422adea3e04563f038f7f28cd40efb2d.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud rate(the baud rate of USB serial communication of Micro:bit is 115200 through the test). Click “OK” and “Connect”.

CoolTerm serial monitor displays the distance value as follows:

![](media/69b0699826728a3ac629f8869b2c644b.png)

**18.2: Ultrasonic Avoidance Car**

![](media/7c90796f65454c4de4df4586d3c86ed5.jpeg)

**(1)Project Description**

We’ve learned the knowledge of obstacle avoidance sensor. In this project, we will integrate ultrasonic sensor, and car expansion board to make an ultrasonic avoidance car.

Its principle is to detect the distance between the car and obstacle by ultrasonic sensor and control the motion of smart car.

**(2)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?) , or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)**

**(3)Flow Chart:**
![Img](./FILES/KS4031-KS4032.md/img-20230414164323.png)

**(4)Test Code:**

Code path:

| File Type | Path                                                                                            | File Name                                   |
|-----------|-------------------------------------------------------------------------------------------------|---------------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 18.2： Ultrasonic Avoidance Car.hex | Project 18.2： Ultrasonic Avoidance Car.hex |

Or you could edit code step by step in the editing area.

(1)Enter“Basic” →“show icon ♥”

Place it into“on start”and click the triangle button to select“![](media/b9b97ec13c745120243516b57a2f2fbc.png)” pattern

![](media/4e8ed8afa7457e273982b6f884567de7.png)

Click“Variables” and then click“Make a Variable..., dialog box“New variable name：”pops up;

Fill it with “distance”;

Click“OK”to establish variable“distance;

Set the functions of servo:

![](media/9664ca8d72cc8ed831fe9b5d8713b395.png)

Click“Variables”to find and drag“set distance to 0”to“forever”;

Click“MecanumRobot”to find and drag“Ultrasonic”to the 0 behind the”to”:

![](media/b45bf0e3b9f2f27746d8aa30403ff0ab.png)

Click“Logic”to find and drag“if true then...else”to“forever”;

Find and drag“=”to “true”;

Click“Variables”to find and drag“distance”on the left of“=”;

Click the little triangle behind“=”to choose“\<”;

Change the 2 behind “\>”to 20:

![](media/609b775c588c55bcb0cfe44d208909d6.png)

Click Funtionsto of “Advance”to find and drag![](media/dd9060aa29c60f92e8ce8f1abc7b5f91.png);

Click“MecanumRobot”to find and drag![](media/0ea445fb8307fca1a1454e1e12a59307.png) to then;

Click“Basic”to find ![](media/659ed579016deb377b781697b2552aee.png) and change the 100 to 500:

![](media/6a5855db5a6855b177b8c615c717bd46.png)

Click“MecanumRobot”to find and drag![](media/c9154a5acacec35bf9bb2d0538e3dc07.png) and change the 0 to 180;

Copy ![](media/44d25af0ef67de4c735f87d5ceb245d6.png) once;

Click“Variables”to find and drag“set distance_l to 0”;

Click“MecanumRobot”to find and drag“Ultrasonic”to 0 behind “to”![](media/41552f84a7e07ba0dafd9d316c318c24.png);

Copy ![](media/44d25af0ef67de4c735f87d5ceb245d6.png)once;

![](media/62db53e547c6e8fc436677e055082ddf.png)

Copy ![](media/47ac979910f0378c537471eb0e205861.png) once;

Change the 180 to 0, distance_l to distance_r and others remain unchanged:

![](media/526ffe9431e408d67128243fcbc5819f.png)

Click“Logic”to find and drag“if true then...else”;

Find and drag“=”to true;

Click“Variables”to find and drag“distance_l to the left of “=”; Click the little triangle behind“=”to choose“\>”;

Change the 0 behind “\>”to “distance_r”:

![](media/101b300f4b7db0e23ee3a7b7ca29dd6f.png)

Click Funtionsto of “Advance”to find and drag![](media/7e3dd5d92e3b83921b164b4f72908184.png);

Click“MecanumRobot”to find and drag![](media/752a8d81f9c62d904159b1405b703f53.png);

Change the 0 to 90;

Click“Basic”to find and drag ![](media/659ed579016deb377b781697b2552aee.png) and change the 100 to 300:

![](media/5412afb79dec7e6e47c85f14151de4df.png)

Change ![](media/6ee297904b560c8c8370fc650d8ee532.png) to ![](media/7fa87915a652f69f25c4fb6325c05124.png) and place it in the first “else”：

![](media/a860cf40263fb2c685996ce8a0e44a21.png)

Click “Funtionsto” of “Advance”to find and drag![](media/f87ab638cdb2e89fcef5dea3ed2c2355.png)，and place it to the second “else”：

![](media/78793a8b16332f40f3ba0188f98d9170.png)

Complete Program:

![](media/5ffdf5cd6be9ded973e8fab3f0afb2e7.png)

![](media/817a8f155167ddf73ee286c3c4cc38bf.png)

Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/31f89e83555fb40cb016f2982c7c0264.png)

**(5)Test Results:**

Download code to micro:bit, dial to ON end, and dial POWER to ON end. When the obstacle distance is greater than 20cm, the car goes forward ; on the contrary, smart car turns left.

([How to download?] How to quick download?)

**18.3: Ultrasonic Follow Smart Car**

![](media/453cfb62710023db62eb80370eeb6f78.jpeg)

**(1)Project Description**

In previous lesson, we’ve learned the basic principle of line tracking sensor. Next, we will combine ultrasonic sensor with car shield to make an ultrasonic follow car.

The ultrasonic sensor detects the obstacle distance and control the motion status of car.

**(2)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?), or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)**

**(3)Flow Chat:**
![Img](./FILES/KS4031-KS4032.md/img-20230414164435.png)

**(4)Test Code:**

Code path:

| File Type | Path                                                                                              | File Name                                     |
|-----------|---------------------------------------------------------------------------------------------------|-----------------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 18.3：Ultrasonic Follow Smart Car.hex | Project 18.3：Ultrasonic Follow Smart Car.hex |

Or you could edit code step by step in the editing area.

(1)Enter“Basic” →“show icon ♥”

Place it into“on start”and click the triangle button to select“![](media/b9b97ec13c745120243516b57a2f2fbc.png)” pattern。

![](media/4e8ed8afa7457e273982b6f884567de7.png)

(2)Click“ MecanumRobot”to find and drag![](media/1eff07a69c5638b58b55d10dae4471d9.png)to“on start”and change the angle 0 to 90:

![](media/295d9af41bb520c0df8ed0d6bb17a01f.png)

Click“Variables” and then click“Make a Variable...”, the dialog box“New variable name：”pops up; fill it with “distance”;

Click“OK”to establish variable“distance”;

Drag“set distance to 0” to “forever”;

Click“ MecanumRobot”to find and drag![](media/510609eb2d083a5893b81c83ec790d0d.png)to the “0” of“set distance to 0”:

![](media/1adf6ff794c9cb8304cd1669bc57edf7.png)

Click“Logic”to find and drag“if true then...else”to“forever”;

Find and drag“=”to true;

Click“Variables”to find and drag“distance”to the left side of “=”;

Click the little triangle behind“=”to choose“\<”;

Change the 0 behind “” to 10:

![](media/2dd8554239ca3eafc07e2093de962311.png)

Click “Funcions” of“ Advance”to find and drag![](media/27404bb7a7aa9733a5d9a9b390ee5958.png)to“then”:

![](media/e8a12e1e353502ceb550a204a0b1f121.png)

Change the 10 to 20, car_back to car stop:

![](media/9f7cfcaee4fad430c97dbea06434a302.png)

Change the 20 to 40，car stop to car forward;

Place car stop to the last”else”:

![](media/e8629032a5e8fc91d159c79d9c76a8bb.png)

Complete Program:

![Img](./FILES/KS4031-KS4032.md/img-20230414164604.png)


Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/0e5b1c473b2de851b628164d9daa8449.png)

**(5)Test Results:**

Download code to micro:bit, dial POWER switch to ON end on shield, smart car could follow the obstacle to move.

(How to download?] [How to quick download?)

### Project 19：IR Remote Control

 19.1：Decode IR Remote Control

![](media/3a3e9860725c893c34613ee1eafb91fc.png)

**(1)Project Description**

There is no doubt that infrared remote control is ubiquitous in daily life. It is used to control various household appliances, such as TVs, stereos, video recorders and satellite signal receivers. Infrared remote control is composed of infrared transmitting and infrared receiving systems, that is, an infrared remote control and infrared receiving module and a single-chip microcomputer
capable of decoding.

![](media/9980b41f57feddc2e8a9c0346afaaea9.png)

The 38K infrared carrier signal emitted by remote controller is encoded by the encoding chip in the remote controller. It is composed of a section of pilot code, user code, user inverse code, data code, and data inverse code. The time interval of the pulse is used to distinguish whether it is a 0 or 1 signal and the encoding is made up of these 0, 1 signals.

The user code of the same remote control is unchanged. The data code can distinguish the key.

When the remote control button is pressed, the remote control sends out an infrared carrier signal. When the IR receiver receives the signal, the program will decode the carrier signal and determines which key is pressed. The MCU decodes the received 01 signal, thereby judging what key is pressed by the remote control.

Infrared receiver we use is an infrared receiver module. Mainly composed of an infrared receiver head, it is a device that integrates reception, amplification, and demodulation. Its internal IC has completed demodulation, and can achieve
from infrared reception to output and be compatible with TTL signals. Additionally, it is suitable for infrared remote control and infrared data transmission. The infrared receiving module made by the receiver has only three pins, signal line, VCC and GND.

According to the picture above, the integrated port of the infrared receiver is connected to the G port on the motor driver board and controlled by the the P9 of the micro:bit.

**(2)Parameters:**

-   Operating Voltage: 3.3-5V（DC）

-   Interface: 3PIN

-   Output Signal: Digital signal

-   Receiving Angle: 90 degrees

-   Frequency: 38khz

-   Receiving Distance: about 5m

**(3)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?) , or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)**

**(4)Test Code:**

| File Type | Path                                                                                           | File Name                                  |
|-----------|------------------------------------------------------------------------------------------------|--------------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 19.1：Decode IR Remote Control.hex | Project 19.1：Decode IR Remote Control.hex |

Click“Advanced”→“Serial”→“serial redirect to USB”

Place it into“on start”block.

![](media/73b63660eb8f378dea4930f354d04de6.png)

Enter“IrRemote”→“connect IR receiver at P0”

Put it into“on start”block

IR receiving module is controlled by P9 of micro:bit board, so click P0 to select P9.

![](media/00f33b8618173e4164f93eea90ca9e66.png)

Go to“Variables”→“Make a Variable...”→ “New variable name：” dialog box，

Enter“val”and click“OK”to create variable“val”

Then drag out“set val to 0”block into“forever”block.

![](media/ca51f70bf8729f83310f70471bf1b64a.png)

Go to“Ir Remote”→“IR button”

Place it into 0 box

![](media/85bff59d45d6defe248bd5c82c4b7078.png)

Click“Advanced”→“Serial”→“serial write value“x”=0”

Put it into“forever”block

Change“x”into“IR”

Enter“Variables”to move block“val”into 0 box behind“=”

![](media/736e85fd87be88896e185cc61373f69e.png)

Drag out block“pause (ms) 100”from“Basic”and delay in 1000ms

Leave it into“forever”block

![](media/407dccc26a2a9e0e07d0436591cd99bd.png)

Complete Program：

![](media/2e20f731f34b79115eedecb2d1eefd78.png)
“on start”: command block runs once to start program.

Serial redirect to USB

Connect IR receiver to P9

The program under the block “forever” runs cyclically.

Set val to IR button

Serial port prints IR=val

Delay in 1000ms


Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/a563b7f1f8bc0d95d012021cbed308c7.png)

Code explanation: when the buttons are not pressed, the serial monitor constantly shows 0; when pressed, the corresponding key values are displayed.

Notes：

The remote control in this kit is not inclusive of batteries. We recommend you to purchase them online.(battery type:CR2025).

Make sure IR remote is good before test. There is a tip for you to check it.

Open the cellphone camera , make IR remote control point at camera and press button. The remote control is good if you see the purple flashing light in the camera.

Download code to micro: bit board and don’t plug off USB cable Click![](media/1f02508d0c79cd976c673a6a5daba648.png)

([How to quick download?](##_7.3.快速下载))

![](media/e7bf712e0c8bedc4b0423427848fa395.png)

Make IR remote control point at IR receiver and press the button, the serial monitor will display the corresponding key values, as shown below：

![](media/c7a33a4cc9d6decbf9b653d91bcb5318.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud rate. Click“OK”and“Connect”.

CoolTerm serial monitor shows the key value as follows:

![](media/a2c59f8119f9b1659c2bb40833836430.jpeg)

The key value is displayed as for your reference:

![](media/73468f2defcf61d08bda15176f1ee072.jpeg)

**19.2：IR Remote Control**

![](media/39d39651f95564fcdb364b80362e0bbf.jpeg)

**(1)Project Description**

In this project, we combine IR remote control with car shield to make an IR remote smart car. Its principle is to control the motion of car by sending key signals from IR remote control to IR receiving module of car shield.

**(2)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?) , or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)** ** Note: The infrared sensor and infrared remote control should not be used in
environments with infrared interference such as sunlight. Because sunlight contains a lot of invisible lights, such as infrared and ultraviolet. In an environment with strong sunlight, they cannot work normally.

**(3)Flow Chart:**
![Img](./FILES/KS4031-KS4032.md/img-20230414164819.png)

**(4)Test Code**

Code path:

| File Type | Path                                                                                     | File Name                            |
|-----------|------------------------------------------------------------------------------------------|--------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 19.2：IR Remote Control .hex | Project 19.2：IR Remote Control .hex |

Or you could edit code step by step in the editing area.

(1)Create four functions controlling the car to move forward and back and turn left and right:

![](media/d46216511146b3eefc907faf354c3b28.png)

(2)Click“Ir Remote”to find and drag“connect IR receiver at P0”into“on start”;
Click the little triangle behind P0 to choose P9;

![](media/bfb26fae4a93881f1019687edf2f36dd.png)

(3)Click“Variables”then click“Make a Variable...”, the dialog box“New variable name：”pops up; fill it with“val” and click“OK”to create variable“val”;

Create variable“val2”with the same method; find and drag“set val2 to 0”to“on start”and copy it once to put into“on start”too;

Click the little triangle behind the first val2 to choose “val”;

![](media/30a8b3296f8b1036a077815143af7a20.png)

(4)Click“Variables”to find and drag“set val2 to 0”to“forever”; Click the little triangle behind val2 to choose val; Click“IrRemote”to find and drag“IR button”to the “0” behind “to”;

![](media/cb2d715c478a5e5a45c5bd290d934bb0.png)

(5)Click“Logic”to find and drag“if true then”into“forever”; find and drag “=”into“true”;

Click“Variables”to find and drag“val”to the left side of “=; the 0 on the right side of “=”remain unchanged; click the little triangle behind “=”to choose“≠”;

![](media/bd0c5a825a3ec489771cd94f66bf4eeb.png)

(6)Click“Variables”to find and drag“set val2 to 0”into “then”;find and drag “val”into the o behind “to” of“set val2 to 0”;

![](media/c7113c934b0ab15ada6402db27fd2a12.png)

(7)Click“Logic”to find and drag“if...then...else”to then;

Click“![](media/a7c5c78217692a965e679b2439ab2f3a.png)”of” if...then...else”four times;

Click“![](media/0fcc5d6332012fed7361a075bd60751f.png)”behind “else”once to delete else;

Find and drag “=” to “true”; ![](media/472e74c957d8646cf1d8d0f691f00f24.png)

(8)Click“Variables”to find and drag“val2”to the left side of“=”and change the 0 on the right of“=”to 70:

![](media/b56abcb30b725bdd5d9d638d6af51dad.png)

(9)Click“Functions” of“Advance”to find and drag![](media/d3cf8340044d82c5d2d50246d9e6965e.png)to the second “then”:

![](media/482a152434aeb6f4c85f3fdac0ae84cd.png)

(10)Copy “val2=70”once and place it behind the first “if”;change the 70 behind “=” to 68; ![](media/d5f6fef293f69b8f8d882c7649102e7f.png)

(11)Click“Functions” of“Advance”to find and drag![](media/4deed9368819d1dbfea4610d4f67a9d1.png) to the second “then” :
![](media/e6fb5164cb395fdfda9633cdd0e26cc3.png)

(12)Copy“val2=68”once and place it behind the second “else if “; change the 68 behind “=”to 67； place it in the forth “then”;Click“Functions”of“Advance”to find and drag![](media/47d91ca3ea8d1dc80a1ecb2bfb72627a.png)to the forth “then”:

![](media/40f5ed1de0d11c11e8fe8e9b6b1dd9b9.png)

(13)Copy“val2=67”once and put it behind “=” of the third “else if ; change the number 67 to 21;click “Functions” of “Advance”to find and drag![](media/cad0b2d52818bfc2bdd2c65a2663ebac.png) to the fifth “then”:

![](media/923c2766615153dcebba2524d127fc12.png)

(14)Copy “val2=21”once and place it behind the fourth “else if “;change the the number 21 behind“=”to 64；Click“MecanumRobot”to find and drag ![](media/94cc49c46a54dfc4e06e604e359fa1c9.png) to the sixth “then”:

![](media/383a620fd554d765d71d628e2a37a3dc.png)

Complete Program:

![](media/22d06d7487b51c0dfdd0ca30c7f4945e.png)

① The "on start" command block runs only once to start the program.

②Connect the IR receiver to P9

③Set the variable val to 0

④Set the variable val2 to 0

⑤In the "forever" instruction box, the program runs cyclically

⑥Set val to IR button

⑦When the variable val≠0 is established, execute the program under then

⑧Set variable val2 to val

⑨When val2=70 is established, execute the program under then

⑩The car goes forward

⑪When val2=68 is established, execute the program under then

⑫Turn left

⑬When val2=67 is established, execute the program under then

⑭Car turn right

⑮When val2=21 is established, execute the program under then

⑯The car goes back

⑰When val2=64 is established, execute the program under then

⑱The car stops


Click“JavaScript" to switch into the corresponding JavaScript code:

![](media/7964a2597251bbe9c847429f80abbe2e.png)

**(5)Test Results:**

Download code to micro:bit board, and dial POWER to ON end. Make IR remote control point at micro:bit and press the button to control smart car to move.

![](media/d55474f3fdf94e5d35de424c0135f554.png)button makes smart car move forward，![](media/5c8a65498c17f35878adf79ba446a7c8.png)stands for turning left，![](media/41116032870ebaa49d6e78fe2445da36.png)implies rightward turning,
![](media/369433f6b13252c1df8c30b3f71028d2.png)indicates moving backward，![](media/a8ef4b174911d528e2dc232c2f862b7d.png) stops car，and 4pcs WS2812RGB light up the corresponding color.

(How to download?[How to quick download?)

Note: the distance between IR remote control and IR receiving head of smart car are supposed less than 5m, during the test.

### Project 20: Bluetooth Multi-purpose Smart Car

**20.1: Read Bluetooth Data**

![](media/55b2424d88ba1ba8a711c49418ca8dc6.png)

**(1)Project Description**

Micro:bit main board comes with a built in Bluetooth which can be used to communicate with it. And the Micro:bit can also be controlled by Bluetooth or transmit signals back to smartphone or computer via it. This Bluetooth can communicate with the Bluetooth equipped in other devices or with Bluetooth App to control other equipment. It is compatible with both Android system ans IOS system. And we have designed two Bluetooth App for both systems.

The connection of the Bluetooth on the board with these two Apps is similar. In this lesson, we will introduce the functions of all keys and patterns on the Apps and control the smart car via Bluetooth App.

**(2)Experimental Preparation：**

-   Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

-   Place batteries into battery holder

-   Dial power switch to ON end

-   Connect micro:bit to computer by USB cable

-   Open online Makecode editor

Import Hex profile (How to import?), or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)**

As the Bluetooth and extension radio can’t work together, therefore, their extension libraries are not compatible.

Therefore, remove extension(s) and add Bluetooth please if you see the following prompt box pop up.

![](media/aee56e76bad3421a20cea6018ccd5e2c.png)

**(3)Test Code:**

Code Path:

| File Type | Path                                                                                      | File Name                             |
|-----------|-------------------------------------------------------------------------------------------|---------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 20.1：Read Bluetooth Data.hex | Project 20.1：Read Bluetooth Data.hex |

Or you could edit code step by step in the editing area.

Enter“Advanced” →“Serial” → “serial redirect to USB”

Place it into“on start”

![](media/73b63660eb8f378dea4930f354d04de6.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Click“Bluetooth”→“on bluetooth connected”

Go to“Basic”to move“show icon”block into“on bluetooth connected” block.

![](media/501b8068bafd00adcf138a2b828835d9.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Click“Variables”→“Make a Variable...”→“New variable name：”dialog box.

Input“connected”and click“OK”to create variable“connected”.

Drag“set connected to 0”under block “show icon” and change 0 into 1.

![](media/bc9514b04f4aae40dc295eeac3fb21ce.png)

Go to“Loops”to move block“while true do...”into“on bluetooth connected”block.

Enter“Logic”to drag out “=”block.

Click“Variables” to drag “connected” into left box of “=” block and change 0 into 1.

![](media/665a62b4895ca45f82d3ebc88e885bce.png)

\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

Then we generate variable“rec_data”in same way.

Then drag out“set rec_data to 0”and place it into block“while connected=1 do...”block.

Click“Bluetooth”→“more”→“bluetooth uart read until new line( )”

Keep it into 0 box and click triangle button to select \##.

![](media/e993122756294214c561f660c3df07ea.png)

Go to“Advanced”→“Serial”→“serial write string”

Move it below“set rec_data...until\##”block

And combine variable“rec_data”with“serial write string”block.

![](media/6effc725f7d85e4a72afbcee102cc478.png)

Click“Advanced” →“Serial” →“serial write line” and edit code string as follows:

![](media/5d66f2053f858d7a3f2e0af55bcc0f0f.png)

Click“Bluetooth”to drag out“on bluetooth disconnected”.

Go to“Bluetooth”→“on bluetooth disconnected”

Copy“show icon”block and keep it into block“on bluetooth disconnected”

Click triangle button to select“![](media/25e0341e063286ff7828c15f09ae0ade.png)”pattern.

![](media/689000dc16e8fb32f0d9918445aae4c1.png)

Complete Program

![Img](./FILES/KS4031-KS4032.md/img-20230414165146.png)
“on start”: command block runs once to start program.

Serial redirect to USB

Connect Bluetooth 

LED dot matrix shows“❤”pattern

Set variable connected to 1

When connected=1, the code under do block will be executed.

Set rec_data to bluetooth uart read until ##

Serial port prints rec_data

Print a blank space

Disconnect Bluetooth

LED dot matrix displays“”pattern.

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |

Click“JavaScript" to view the corresponding JavaScript code:

![](media/24191138f7bb709f2c6de046df16edef.png)

**(4)Test Results:**

If you drag blocks step by step, you need to set as follows after finishing test code.

Click ![](media/09767d5efdc8f05fdb331b5ae6d352b5.png)

However, you could skip this step if you directly import test code.

After setting, download code to micro:bit board, don’t plug off USB cable(How to download? How to quick download?)

Next to download App.

**For IOS System:**

a.open App Store;

![](media/27924fdb3d67692df7c63d8d0fb72287.png)

b.search mecanum_robot and click“![](media/962a57f92b78eea1f0e3e81463497a9c.png)”to download the Bluetooth App of mecanum_robot;

c. After downloading the APP, click "OPEN" or click the application mecanum_robot on the phone/iPad desktop to open the APP. A dialog box appears on the APP interface, and click "OK" in the dialog box.

d. First turn on the Bluetooth of the mobile phone/iPad, and then click the connect button (control) in the upper left corner of the APP interface to perform a Bluetooth search. In the search results, click "BCC micro:bit". After a few seconds, the Bluetooth is connected.

**For Android System:**

a. Use the scanning function in the browser to scan and identify the QR code or enter the <http://8.210.52.206/mecanum_robot.apk> to download. After the identification is successful, click "go to website" to enter the download mecanum_robot.apk page , Click "Download" to download the mecanum_robot application.

![](media/d9acbfab8eccc3da40cde7788a3e1854.png)

B.Click“Allow allow”to enter Installation Diagram; click“install”to install the App![](media/638d0a4ae5f55ca39bff4f20a3bd14a6.png);

C.Click "Open" or click the application mecanum_robot on the mobile phone desktop to open the APP, and a dialog box appears. In the dialog box, click "Allow" to turn on the Bluetooth of the mobile phone. You can also turn on the phone's Bluetooth before opening the APP.

![](media/c818fd71d6872374fbe177f082207fac.png)
![](media/b922bd4774503866b47eaf4021cb94cf.png)

Click ![](media/d3f566b98da750bf4d5799b624211516.png) on the upper right corner to search for Bluetooth and click“connect”; a few seconds later, the Bluetooth is paired.

![](media/7f8d1d05045f24aa9c252532dcd120c0.png)
![](media/b3f547c17f0bee67cd74411303d570d1.png)

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud rate. Click“OK”and“Connect”.

Point at micro:bit board and press the icons on APP, the corresponding characters are shown on CoolTerm monitor.

![](media/0ed4a53ef14fbfe047929d07d5433fcb.png)

Through the test, we get the function of every icon, as shown below:

![](media/05c3d32b07c8e1393eacd805b4de77c7.jpeg)

**20.2: Multi-purpose Smart Car**

![](media/ce8895d3efbea309fd88b8cd7d05c989.jpeg)

**(1)Project Description**

In this lesson, we will control the smart car to perform multipurpose function.

**(2)Experimental Preparation：**

Insert micro:bit board into slot of keyestudio 4WD Mecanum Robot Car

Place batteries into battery holder

Dial power switch to ON end

Connect micro:bit to computer by USB cable

Open online Makecode editor

Import Hex profile (How to import?) , or click“New Project”and drag blocks step by step(add MecanumRobot extension library first)

**(How to add MecanumRobot extension?)**

As the Bluetooth and extension radio can’t work together, therefore, their extension libraries are not compatible.

Therefore, remove extension(s) and add Bluetooth please if you see the following prompt box pop up.

![](media/aee56e76bad3421a20cea6018ccd5e2c.png)

**(3)Test Code:**

**Code path:**

| File Type | Path                                                                                          | File Name                                 |
|-----------|-----------------------------------------------------------------------------------------------|-------------------------------------------|
| Hex file  | KS4031(4032) folder/Makecode Tutorial/Makecode Code/Project 20.2：Multi-purpose Smart Car.hex | Project 20.2：Multi-purpose Smart Car.hex |

Complete Code:

![Img](./FILES/KS4031-KS4032.md/img-20230414165452.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414165458.png)
![Img](./FILES/KS4031-KS4032.md/img-20230414165504.png)


Click“JavaScript" to view the corresponding JavaScript code: ：

![](media/5f45c01f6f069d6b3f93a29b62055de0.png)

**(4)Test Results:**

This experiment combines the previous projects to make the car to perform actions by Bluetooth.

Enter Makecode online editor→Project Settings→![](media/bef5b73422672f316f211a959bcdfa60.png), enable “No Pairing....”(you could skip this step if you import test code directly)

Download code to micro:bit board, dial POWER to ON end, and connect the Bluetooth, then you can control the car via the Bluetooth App of mecanum_robot.

How to download? How to quick download?

## Resources:

Download PDF files: https://fs.keyestudio.com/KS4031-4032

BBC microbit MicroPython:

<https://microbit-micropython.readthedocs.io/en/latest/tutorials/introduction.html>

MicroPython:

<https://docs.openmv.io/reference/index.html>

ustruct library:

<https://docs.openmv.io/library/ustruct.html>

math library:

<https://docs.openmv.io/library/math.html>

utime(sleep_us,tick_us) library:

[https://docs.openmv.io/library/utime.html\##](https://docs.openmv.io/library/utime.html)

 
