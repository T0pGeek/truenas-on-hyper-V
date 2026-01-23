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
<p>Turn off Secure Boot. TrueNAS will not boot if it's on. </p>

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

<p>Next, use the Arrow Keys and press enter on "Reboot System".</p>

<p>
 <img width="474" height="412" alt="Editing truenas-on-hyper-V_README md at main · T0pGeek_truenas-on-hyper-V - Brave 1_14_2026 9_31_22 AM" src="https://github.com/user-attachments/assets/6970a59f-360b-4ef9-818e-806715efad92" />
</p>
<p>Now TrueNAS Scale is up and running, but we need to configure it.</p>


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


<p>
 <img width="3440" height="1247" alt="Captures - File Explorer 1_15_2026 9_08_26 AM" src="https://github.com/user-attachments/assets/0dc71dc9-77e5-4f68-84b0-232e353a2c44" />
</p>
<p>This is how you will configure/update your TrueNAS server.
</p>


<p>
 <img width="3440" height="1247" alt="Captures - File Explorer 1_15_2026 9_08_26 AM" src="https://github.com/user-attachments/assets/0301a725-d66b-4df0-aa4f-8577adbe1ca4" />
</p>
<p>Now we will set up a Storage Pool. Click on Storage.</p>


<p>
 <img width="631" height="243" alt="Media Player 1_18_2026 2_09_26 PM" src="https://github.com/user-attachments/assets/db579fdb-2e40-490e-b9c2-98c0718044ec" />
</p>
<p>Click "Create Pool".</p>

<p>
 <img width="1714" height="735" alt="Media Player 1_18_2026 2_13_52 PM" src="https://github.com/user-attachments/assets/2cc8c265-f006-4aa7-8448-b75d72c1adb6" />
</p>
<p>Create a Name and click next.</p>


<p>
 <img width="1550" height="987" alt="Media Player 1_18_2026 2_40_34 PM" src="https://github.com/user-attachments/assets/5b2b14e4-79f9-4d55-b68b-afb50e84f48f" />
</p>
<p>For the Layout click stripe, and click next.</p>



<p>
 <img width="1216" height="617" alt="Media Player 1_18_2026 2_45_25 PM" src="https://github.com/user-attachments/assets/5992fa1a-f71d-480e-95f1-305d8383a116" />
</p>
<p>Under Disk Size, select the disk you want to use, and click next.</p>


<p>
 <img width="1931" height="698" alt="Media Player 1_18_2026 2_49_43 PM" src="https://github.com/user-attachments/assets/c334d845-a440-4707-a343-947f2a28b36e" />
</p>
<p>Click Next until you're at Review, and click Create Pool.</p>


<p>
 <img width="328" height="185" alt="Media Player 1_18_2026 2_54_35 PM" src="https://github.com/user-attachments/assets/10b19dff-7047-4f48-ba45-2de40d0dbdaf" />
</p>
<p>Click confirm and Continue.</p>


<p>
 <img width="526" height="538" alt="Media Player 1_18_2026 2_57_30 PM" src="https://github.com/user-attachments/assets/290e7355-2ce0-4a54-9fa1-39052a5bf447" />
</p>
<p>Click Shaires.</p>

<p><img width="1596" height="526" alt="Media Player 1_18_2026 2_59_36 PM" src="https://github.com/user-attachments/assets/c8620d32-bd6a-4163-aef8-e428b433d28f" /></p>

<p>Click Add.</p>


<p>
 <img width="469" height="618" alt="Media Player 1_18_2026 7_57_12 PM" src="https://github.com/user-attachments/assets/c061dd95-b59d-4d39-b07f-1eabc63ffd91" />
</p>
<p>Select the Disk that you named.</p>


<p>
 <img width="473" height="618" alt="Media Player 1_18_2026 8_01_18 PM" src="https://github.com/user-attachments/assets/ce76c9c4-f3fb-4085-a538-9b1c224cb8a9" />
</p>
<p>Click on Create Dataset.</p>


<p>
 <img width="370" height="232" alt="Media Player 1_18_2026 8_04_42 PM" src="https://github.com/user-attachments/assets/69bc4c2f-dc08-4ae9-aceb-239fcdbe1fbf" />
</p>
<p>Name it, then click create.</p>


<p>
 <img width="462" height="793" alt="Media Player 1_18_2026 8_25_03 PM" src="https://github.com/user-attachments/assets/5fe96af4-e5bf-4ec8-99c1-be1f2e1f6667" />
</p>
<p>Click Save.</p>


<p>
 <img width="372" height="218" alt="Media Player 1_18_2026 8_26_52 PM" src="https://github.com/user-attachments/assets/44b3fdec-7d2b-4950-ab6c-282266403abb" />
</p>
<p> Then click Start.</p>


<p>
 <img width="433" height="525" alt="Media Player 1_18_2026 8_30_28 PM" src="https://github.com/user-attachments/assets/26cbd420-efec-4cb1-b388-cbe31d64fc4f" />
</p>
<p>Click on Credentials.</p>


<P>
 <img width="603" height="556" alt="Media Player 1_18_2026 8_32_52 PM" src="https://github.com/user-attachments/assets/f0ef5394-902b-4b7a-87c5-de142e2cfb3e" />
</P>
<p>Click Users.</p>

<p>
 <img width="2001" height="905" alt="Media Player 1_18_2026 8_36_20 PM" src="https://github.com/user-attachments/assets/1c9d0226-7e67-4a2b-a1d3-57110834c729" />
</p>
<p>In the top right corner, click the "Add".</p>



<p>
 <img width="478" height="990" alt="Editing truenas-on-hyper-V_README md at main · T0pGeek_truenas-on-hyper-V - Brave 1_19_2026 7_19_33 PM" src="https://github.com/user-attachments/assets/de2dd293-4f94-468b-8e9a-3b7b87ebda84" />
</p>
<p>Type in a Username. You will use this same Username/Password to connect the NAS from your computer.</p>


<p>
 <img width="475" height="997" alt="Editing truenas-on-hyper-V_README md at main · T0pGeek_truenas-on-hyper-V - Brave 1_19_2026 7_24_49 PM" src="https://github.com/user-attachments/assets/57aea10c-4874-4088-9544-3e856fd6053f" />
</p>
<p>Type in a Password.</p>


<p>
 <img width="775" height="784" alt="Media Player 1_19_2026 7_34_03 PM" src="https://github.com/user-attachments/assets/e68be397-cc33-419b-97b2-98b07e43cf01" />
</p>
<p>Now we will connect to the NAS, first press the Windows key and type "\\" before your IP address, and press enter. </p>


<p>
 <img width="453" height="422" alt="Media Player 1_19_2026 7_35_38 PM" src="https://github.com/user-attachments/assets/e26ab6a0-c7c1-4d5f-9f1d-325c2884a9cf" />
</p>
<p>Now type in the Username/Password you created earlier and you connected to your NAS.</p>


<p>
 <img width="842" height="650" alt="Media Player 10_11_2025 11_58_29 AM png 1_19_2026 7_38_23 PM" src="https://github.com/user-attachments/assets/7db63ca3-82cf-4d9b-a645-9c21b8ebe67e" />
</p>
<P> double click the name of the folder you have.</P>


<p>
 <img width="985" height="841" alt="Media Player 1_19_2026 7_35_38 PM png 1_19_2026 7_42_04 PM" src="https://github.com/user-attachments/assets/4c9109da-78e4-49b0-9272-bb4eba27bdad" />
</p>
<p> Finally, you can add whatever files you want onto it, and you can connect to it with any other device on your local network.</p>


