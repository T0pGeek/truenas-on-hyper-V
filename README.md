<p align="center"> 
 <img width="473" height="239" alt="image" src="https://github.com/user-attachments/assets/4db19bfb-6d83-402f-8d5a-bc2e540104eb" />
 
 
 <p align="center"> 
 <h1>Instaling Truenas on Hyper-V</h1>
 </p>
  This tutorial will show you how to set up and configure TrueNAS Scale on Hyper-V.
 <h2>Video Demonstration</h2>
 https://youtu.be/vkGs64GSq6Q
 

 

 <h2>Prerequisites and Installation of Truenas Scale on Hyper-V</h1>

- Windows 11/10 pro edition
- Truenas Scale iso
- Extra storage space
-  <h2>Oparating System Used</h2>
- Windows 11 Pro
  
 <h2>Environments and Technologies Used</h2>

- Hyper-V
- Virtual Disk Drive

<h2>Installation Steps</h2>

<p>
<img width="661" height="432" alt="Media Player 1_5_2026 12_20_17 PM" src="https://github.com/user-attachments/assets/bd523bfe-9b30-48a9-82e9-5d9e98407e82" /> </p>
<p>
Launch Hyper-V and click on Quick Create.
</p>
<p>
<img width="816" height="482" alt="Media Player 1_5_2026 12_22_09 PM" src="https://github.com/user-attachments/assets/70aef570-c35e-4fbf-bd2d-24b750ce645f" />
</p>
<p>Click Change Installation Source.</p>

<p>
 <img width="1179" height="709" alt="Media Player 1_10_2026 6_55_56 PM" src="https://github.com/user-attachments/assets/ea0702f8-c632-4b96-b33c-60fcf3d2fc50" />
</p>
<p>Click on the TrueNAS Scale Iso.
</p>

<p>
 <img width="818" height="481" alt="Media Player 1_10_2026 6_59_24 PM" src="https://github.com/user-attachments/assets/d508d336-a57f-4fef-b321-d19a3abc9ab6" />
</p>
<p>Turn off Secure Boot TrueNAS will not boot if it's on. </p>

<p>
 <img width="817" height="479" alt="Media Player 1_10_2026 7_02_48 PM" src="https://github.com/user-attachments/assets/4611b17a-5b65-45f5-90eb-1a13928fec17" />
</p>
<p>Click Create Virtual Machine.</p>

<p>
 <img width="816" height="475" alt="Media Player 1_10_2026 7_21_43 PM" src="https://github.com/user-attachments/assets/0221e537-ea5f-490a-ba08-4e4ca05cff8b" />
</p>
<p>Click Edit settings.</p>

<p>
 <img width="711" height="671" alt="Media Player 1_12_2026 11_00_09 AM" src="https://github.com/user-attachments/assets/23d3eb22-9133-4c5a-8cac-2d5188ef2d7f" />
</p>
<p>Click Hard Drive.</p>




<p>
 <img width="715" height="688" alt="Media Player 1_12_2026 10_57_13 AM" src="https://github.com/user-attachments/assets/460415d4-37ac-439a-b3f0-ac08b68855e9" />
</p>
<p>Click New.</p>

<p>
 <img width="1169" height="699" alt="Media Player 1_12_2026 11_09_15 AM" src="https://github.com/user-attachments/assets/afbdb387-1d59-4f8e-a0ad-f06fb6af554d" />
</p>
<p>Make a New folder on the desired drive.</p>

<p>
 <img width="1165" height="701" alt="Media Player 1_12_2026 11_17_14 AM" src="https://github.com/user-attachments/assets/6d3417bc-c406-4c58-b468-e4ed7083aea7" />
</p>
<p>Then click open.</p>

<p>
 <img width="710" height="685" alt="Media Player 1_12_2026 11_28_58 AM" src="https://github.com/user-attachments/assets/aae4e084-775a-4e3e-9632-73a7425414eb" />
</p>
<p>Click apply.</p>

<p>
 <img width="712" height="681" alt="Media Player 1_12_2026 11_29_56 AM" src="https://github.com/user-attachments/assets/8cbfe09e-6063-4037-9eaa-984d586a00e7" />
</p>
<p>Then click OK.</p>

<p>
 <img width="1310" height="655" alt="Media Player 1_12_2026 11_26_21 AM" src="https://github.com/user-attachments/assets/a1d220bd-965b-417b-b518-54e7e0f6778c" />
</p>
<p> Right-click on your Virtual Machine.</p>


<p>
 <img width="1293" height="665" alt="Media Player 1_12_2026 11_25_07 AM" src="https://github.com/user-attachments/assets/1be412bc-8689-451d-b430-e42f009d2b8d" />
</p>
<p>Click Start.</p>


<p>
 <img width="1310" height="655" alt="Media Player 1_12_2026 11_26_21 AM" src="https://github.com/user-attachments/assets/d9327140-ff67-45ea-a1ef-5206903bf1c6" />
</p>
<p>Right Click again.</p>

<p>
 <img width="1338" height="674" alt="Media Player 1_12_2026 11_43_57 AM" src="https://github.com/user-attachments/assets/4da55b0d-1648-4793-bffb-b2438ddd7a73" />
</p>
<p>Click Connect.</p>


<p>
 <img width="1093" height="725" alt="Media Player 1_12_2026 11_48_09 AM" src="https://github.com/user-attachments/assets/7ac28959-158c-42c7-9979-e250e76aa671" />
</p>
<p>Then this screen will pop up, and you want to press enter on"Start TrueNAS SCALE Installation".</p>

<p>
 <img width="1023" height="764" alt="New Virtual Machine on DESKTOP-SNHPQG7 - Virtual Machine Connection 12_28_2025 4_36_08 PM" src="https://github.com/user-attachments/assets/563a1f7b-d48e-4235-b626-22fd71684917" />
</p>
<p>Press Enter on"Install/Upgrade".</p>


<p>>
 <img width="1023" height="764" alt="Media Player 1_14_2026 8_37_57 AM" src="https://github.com/user-attachments/assets/2b5d631b-9498-4e65-aa14-c49b80f2b9ec" />
</p>
<p>Select the Virtual Disk you want to boot from.
Make sure to choose the correct Virtual Disk to install to.</p>


<p>
 <img width="1025" height="767" alt="Media Player 1_14_2026 8_45_54 AM" src="https://github.com/user-attachments/assets/1eff2ab0-b08a-438d-8386-10b9f29f9785" />
</p>
<p>Once you choose the Virtual Disk, press the Space Bar and click Enter.</p>


<p>
 <img width="1020" height="760" alt="Media Player 1_14_2026 8_54_25 AM" src="https://github.com/user-attachments/assets/47384b04-3f0a-4291-ae11-34f2e16c667f" />
</p>
<p>Press Enter on Yes.</p>



<p>
 <img width="1018" height="764" alt="Media Player 1_14_2026 8_57_05 AM" src="https://github.com/user-attachments/assets/06fc614c-78d5-414e-a617-6d2c33229ec6" />
</p>
<p>Press Enter on "Administrative user (Truenas_admin)".</p>



<p>
 <img width="1018" height="765" alt="Media Player 1_14_2026 9_00_43 AM" src="https://github.com/user-attachments/assets/be5d6abe-0dad-44cd-9b9f-d9e836cb12e5" />
</p>
<p>Create a good Password, and make sure to remember it.
You will use this Password to log in.
It will start installing TrueNAS.</p>


<p>
 <img width="1020" height="762" alt="Media Player 1_14_2026 9_13_21 AM" src="https://github.com/user-attachments/assets/55629455-c336-4846-91ec-7de3b982a562" />
</p>
<p>The Intallation is complete; Press Enter. </p>


<p>
 <img width="1023" height="761" alt="Media Player 1_14_2026 9_00_43 AM png 1_14_2026 9_20_28 AM" src="https://github.com/user-attachments/assets/a43cbdad-24e3-4a5b-8d4a-ef06b5725211" />
</p>

<p>Next use the Arrow Keys and press enter on "Reboot System".</p>

<p>
 <img width="474" height="412" alt="Editing truenas-on-hyper-V_README md at main · T0pGeek_truenas-on-hyper-V - Brave 1_14_2026 9_31_22 AM" src="https://github.com/user-attachments/assets/6970a59f-360b-4ef9-818e-806715efad92" />
</p>
<p>Now TrueNAS Scale is up and running, But we need to configure it.</p>


<p>
 <img width="594" height="541" alt="Media Player 10_11_2025 11_58_29 AM png 1_14_2026 9_28_46 AM" src="https://github.com/user-attachments/assets/90ba56b9-3b71-4b6d-8339-17a9b324c864" />
</p>
<p>Now type in the IP Address into your web browser. The IP Address will not be the same as shown in the image. </p>


<p>
 <img width="1309" height="720" alt="Media Player 1_15_2026 8_46_51 AM" src="https://github.com/user-attachments/assets/c158fedf-779b-4708-8e19-843a516cbe5e" />
</p>
<p>Press Enter.</p>


<p>
 <img width="488" height="652" alt="Media Player 1_15_2026 8_46_51 AM png 1_15_2026 8_51_50 AM" src="https://github.com/user-attachments/assets/7b00d032-7802-4e34-aa31-be73a916df4f" />
</p>
<p>Type in "truenas_admin" for the Username, and the password you created earlier, and click Log In.</p>








