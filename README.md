# VPN-Setup-and-Usage-With-Proton-VPN
<p align="center">
![1](https://github.com/user-attachments/assets/bf65c576-b237-4f67-913a-7680fa791f73)

</p>
<p align="center">
![2](https://github.com/user-attachments/assets/5cb750b0-e0db-4ea6-a811-ac49da3dd997)

</p>
<p align="center">
![3](https://github.com/user-attachments/assets/83354073-7c92-4aed-90b2-79cdf5f36bb0)

</p>

<h1>VPN Setup and Usage With Proton VPN</h1>
In this tutorial, we are going to make a VPN using Proton VPN and measure the different IP addresses. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Proton VPN
- Whatsmyipaddress.com


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Steps</h2>

- Use whatsmyipaddress.com to grab your current IP address
- Create a Virtual Machine in Microsoft Azure
- Log into the virtual machine using Remote Desktop Connection
- Use whatsmyipaddress.com to grab your VM IP address
- Download Proton VPN then connect to any VPN
- Use whatsmyipaddress.com to grab your new Proton VPN IP address


<h2>Actions and Observations</h2>

<p>
![4](https://github.com/user-attachments/assets/693b705a-4ea4-4c45-8d4c-57e81b57f1ed)

</p>
<p>
Go to whatismyipaddress.com to grab your current IP address. Open notepad or grab a piece of paper to write it down  
</p>
<br />

<p>
![5](https://github.com/user-attachments/assets/a29a2d27-b014-4ed2-8e09-192d03a2faae)

</p>
<p>
Go to Microsoft Azure and type Virtual Machine 
</p>
<br />

<p>
![6](https://github.com/user-attachments/assets/cc60f62b-0ecb-4add-a75d-d11af81d2397)

</p>
<p>
Next click create and go to Azure Virtual Machine 
</p>
<br />

<p>
![7](https://github.com/user-attachments/assets/37ec93e0-b8ca-461a-9fd8-7f9daca56102)

</p>
<p>
Go to the Resource Group tab and click create new, the name will be Vm-practice. then click the blue ok button
</p>
<br />

<p>
![8](https://github.com/user-attachments/assets/5dbfe70d-0079-4521-8eb4-9d948c8bdeb2)

</p>
<p>
Now go to the Virtual Machine name and type VMP, the region I will put Europe North Europe so we can get a out of America IP address. The Image click Windows 10 Pro version
</p>
<br />


<p>
![9](https://github.com/user-attachments/assets/40970054-a039-44bf-9888-17f28880fe27)

</p>
<p>
![10](https://github.com/user-attachments/assets/9752e990-c659-45a6-9ccf-5237be40deeb)

</p>
<p>
Next the size can be under Standard E2, the username will be named labuser, and the password can be your unique password. Then once your done click the Licensing box in the bottom left. {NOTE} write down yur username, password, and region to rememeber when you log in
</p>
<br />

<p>
![11](https://github.com/user-attachments/assets/5a9b1666-bb0e-41e9-8119-614f1f78ea28)

</p>
<p>
Next go to the Review and Create tab and click Create on the bottom left side
</p>
<br />

<p>
![12](https://github.com/user-attachments/assets/96a5790c-dbf6-444e-a3bd-3d428a5972e2)

</p>
<p>
![13](https://github.com/user-attachments/assets/0383f74a-937e-44e3-8b28-2c83fae70d26)

</p>
<p>
Now the deployment progess will start, then once its finish you will see a green check to the left
</p>
<br />

<p>
![14](https://github.com/user-attachments/assets/eec08d45-2a3b-463b-b23d-1f31fe427950)

</p>
<p>
Now go back to the search bar and type Virtual Machine and you will see VMP was created, click the VM
</p>
<br />

<p>
![15](https://github.com/user-attachments/assets/727390d9-1c91-4d5d-8675-3264c7833fde)

</p>
<p>
Now go copy the public IP address
</p>
<br />

<p>
![16](https://github.com/user-attachments/assets/366231c0-9d68-45ef-b537-37b396eb99cf)

</p>
<p>
Type Remote Desktop Conenction on your pc
</p>
<br />

<p>
![17](https://github.com/user-attachments/assets/c0f28974-53c0-48d4-8ced-6170fbcdc8c0)

</p>
<p>
Now copy the IP of VMP in the Computer section, then click connect
</p>
<br />

<p>
![18](https://github.com/user-attachments/assets/50f59496-4336-465f-a3a6-674bb84d2d11)

</p>
<p>
![19](https://github.com/user-attachments/assets/08d8ebf6-bd43-4db4-970d-ec224479ac27)


</p>
<p>
Now for your username type labuser, and the password section type in your password then click the blue ok button
</p>
<br />

<p>

</p>
<p>
Now click yes to log into the VM
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/67ff3b3d-ced0-48df-8274-68fae0dbd63d"/>
</p>
<p>
Now you should see the VM loading with the name labuser
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/316dbb0e-2596-4de4-afdb-19604cf12ff8"/>
</p>
<p>
Now click no for the following in the image above
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/757ba510-9f32-4db1-b079-84f39ab643c0"/>
</p>
<p>
Now click yes for the networks tab when it pops up
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/9a8530c0-a988-4b49-8600-e0a044a79faf"/>
</p>
<p>
Now open microsoft excel and click start without your data
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/26f2717b-6cae-4c2f-b577-e4f3e19e25ea"/>
</p>
<p>
Then click continue without this data 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/3b282d2e-c1df-4546-a4f7-401e811d97e0"/>
</p>
<p>
Then click confirm and continue 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/ca0f42c7-8c64-4365-950c-2de9c7f5d42b"/>
</p>
<p>
Then click confirm and start browsing 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/00835c30-edb4-4073-8808-21e723672fd4"/>
</p>
<p>
Then type whatismyipaddress in the search bar and click the site
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/e323648d-e07f-4a57-897c-1789bbb9df46"/>
</p>
<p>
Then go to the MY IP section
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/08e4e3ca-e881-44d5-9594-c9fab99b0433"/>
</p>
<p>
Then you will see the IPv4 and the city, region, and the country
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/909f7e1d-2e10-47e5-9fcb-e55a122b993d"/>
</p>
<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/8ba6de5f-7b7d-4fd9-a372-b0d117983bd1"/>
</p>
<p>
Then type proton VPN download in the search bar and scroll down till you see download VPN
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/98d54564-6d6d-47f2-a879-f3697e32b9e4"/>
</p>
<p>
Next click Download Proton VPN
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/41507a62-9102-4018-80ea-89e231b27410"/>
</p>
<p>
Next go to file explorer, go to the download folder, and double click the software to open it
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/724f74e2-f370-4f36-ada0-41d1e1c21396"/>
</p>
<p>
Next click the next button
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/25df9158-e76b-41f8-87ad-3028a5cc16ac"/>
</p>
<p>
Next click the next button
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/9cc3514b-58f5-4e77-9f80-0cf194b75936"/>
</p>
<p>
Next click the install button
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/485d14f7-b5c0-4694-8b93-7f025a2dc725"/>
</p>
<p>
Now create an account in the bottom left, if you have an account type your username and password
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/e017fdda-1160-4e38-8ddb-2d05e6f5bda0"/>
</p>
<p>
Now once it loads click the skip button unless you want a tour
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/b425fc99-aab2-49dd-93f4-874468f3431d"/>
</p>
<p>
Next connect to whatever country you want for this I will pick Japan, then click the purple button
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/f659d68f-725e-440b-8b02-d8c6b5916e97"/>
</p>
<p>
Next let the VPN load dont click anything 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/2ead675f-c5ba-4097-884e-00e109d1541b"/>
</p>
<p>
Now if you see a Reconnecting tab dont click cancel, let the process finish 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/d21bf5cf-6718-4f3e-b4b2-6b8686359d11"/>
</p>
<p>
Now go back to whatisyouripaddress.com and refresh the page and you will see your IP, city, region, and country changed
</p>
<br />


<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/894afd2e-ad5b-4b01-95d2-73f8c60537a1"/>
</p>
<p>
Now go back to Proton VPN and click disconnect, you can also click on any of Japan's IP that are availble on the left side once you click the arrow to expand the available IP
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/acf372d3-4d49-4314-a8ba-531269573bf9"/>
</p>
<p>
Now click the bar at the top left and click sign out to sign out of your account
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/8e7cbc6b-ab7e-4060-871f-c8474ab11f2a"/>
</p>
<p>
Next go back to Microsoft Azure and type Resource Groups click on Vm-practice and type it in the delete resource group tab then click the delete red tab
</p>
<br />


<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/1513d1ca-84d6-4383-bf0a-19f95a499ce5"/>
</p>
<p>
Then just confirm the process by clicking delete again 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/40bf458c-a985-4847-b684-2237055fff6a"/>
</p>
<p>
Now go to the next resource group if you have one and click delete resource group
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/1c682958-82be-4d8b-86b0-2891045ddac2"/>
</p>
<p>
Then type the name in and click the red delete button
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/4deb6184-898a-4457-b51f-7b3f1e410b7f"/>
</p>
<p>
Then to finish the process click delete again 
</p>
<br />

<p>
<img src="https://github.com/Jacobvillagomez1/VPN-Setup-and-Usage-With-Proton-VPN/assets/143027686/b62da111-91fb-46d7-85d7-8dbed0c65e04"/>
</p>
<p>
Then if you want to see the process click the bell icon on the top right 
</p>
<br />
