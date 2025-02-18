# VPN-Setup-and-Usage-With-Proton-VPN
<p align="center">
<img src="https://github.com/user-attachments/assets/bf65c576-b237-4f67-913a-7680fa791f73"

</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/5cb750b0-e0db-4ea6-a811-ac49da3dd997"

</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/83354073-7c92-4aed-90b2-79cdf5f36bb0"

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
<img src="https://github.com/user-attachments/assets/693b705a-4ea4-4c45-8d4c-57e81b57f1ed"

</p>
<p>
Go to whatismyipaddress.com to grab your current IP address. Open notepad or grab a piece of paper to write it down  
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/a29a2d27-b014-4ed2-8e09-192d03a2faae"

</p>
<p>
Go to Microsoft Azure and type Virtual Machine 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/cc60f62b-0ecb-4add-a75d-d11af81d2397"

</p>
<p>
Next click create and go to Azure Virtual Machine 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/37ec93e0-b8ca-461a-9fd8-7f9daca56102"

</p>
<p>
Go to the Resource Group tab and click create new, the name will be Vm-practice. then click the blue ok button
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5dbfe70d-0079-4521-8eb4-9d948c8bdeb2"

</p>
<p>
Now go to the Virtual Machine name and type VMP, the region I will put Europe North Europe so we can get a out of America IP address. The Image click Windows 10 Pro version
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/40970054-a039-44bf-9888-17f28880fe27"

</p>
<p>
<img src="https://github.com/user-attachments/assets/9752e990-c659-45a6-9ccf-5237be40deeb"

</p>
<p>
Next the size can be under Standard E2, the username will be named labuser, and the password can be your unique password. Then once your done click the Licensing box in the bottom left. {NOTE} write down yur username, password, and region to rememeber when you log in
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5a9b1666-bb0e-41e9-8119-614f1f78ea28"

</p>
<p>
Next go to the Review and Create tab and click Create on the bottom left side
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/96a5790c-dbf6-444e-a3bd-3d428a5972e2"

</p>
<p>
<img src="https://github.com/user-attachments/assets/0383f74a-937e-44e3-8b28-2c83fae70d26"

</p>
<p>
Now the deployment progess will start, then once its finish you will see a green check to the left
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/eec08d45-2a3b-463b-b23d-1f31fe427950"

</p>
<p>
Now go back to the search bar and type Virtual Machine and you will see VMP was created, click the VM
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/727390d9-1c91-4d5d-8675-3264c7833fde"

</p>
<p>
Now go copy the public IP address
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/366231c0-9d68-45ef-b537-37b396eb99cf"

</p>
<p>
Type Remote Desktop Conenction on your pc
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/c0f28974-53c0-48d4-8ced-6170fbcdc8c0"

</p>
<p>
Now copy the IP of VMP in the Computer section, then click connect
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/50f59496-4336-465f-a3a6-674bb84d2d11"

</p>
<p>
<img src="https://github.com/user-attachments/assets/08d8ebf6-bd43-4db4-970d-ec224479ac27"


</p>
<p>
Now for your username type labuser, and the password section type in your password then click the blue ok button
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/15bace91-ae72-43e8-8485-0edd890633b6"

</p>
<p>
Now click yes to log into the VM
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f06a4dcb-3c83-447c-bbf3-da4fa62fae92"

</p>
<p>
Now you should see the VM loading with the name labuser
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/1780bce9-02b1-46be-9445-4e82b6ef281f"

</p>
<p>
Now click no for the following in the image above
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/e87c0b2f-6fc8-4a2a-b4d6-990b7ca1dc38"

</p>
<p>
Now click yes for the networks tab when it pops up
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/b1cd48b6-8c80-42a8-b2b4-c596417c63ab"

</p>
<p>
Now open microsoft excel and click start without your data
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/8d9c229d-e7ab-4f06-98e9-d2f1a3862aa7"

</p>
<p>
Then click continue without this data 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/d88575d7-0a5d-474d-8198-44f00c7585e0"

</p>
<p>
Then click confirm and continue 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/8d054348-bb69-4ed3-8cff-8ce7c863837f"

</p>
<p>
Then click confirm and start browsing 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/cd54a3d1-eebe-42c7-9617-fd131945f1a3"

</p>
<p>
Then type whatismyipaddress in the search bar and click the site
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/8cc4ecf5-41ea-4e35-9ddb-af4b3b947da6"

</p>
<p>
Then go to the MY IP section
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/56dc5718-7daf-4a32-a5d9-84bc984e24f0"

</p>
<p>
Then you will see the IPv4 and the city, region, and the country
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/b2880d79-5e36-4a91-8cd9-ee1f3a44a9be"

</p>
<p>
<img src="https://github.com/user-attachments/assets/80e6cd34-b1d7-488f-83de-4dacd3b536c8"

</p>
<p>
Then type proton VPN download in the search bar and scroll down till you see download VPN
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/b7547b89-a9a5-46fb-a005-b7a23d13adfe"

</p>
<p>
Next click Download Proton VPN
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/63fa7e58-db24-4324-885d-82c4528cb46d"

</p>
<p>
Next go to file explorer, go to the download folder, and double click the software to open it
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/8d98d7e7-601f-4fc8-a7a8-10905db80886"

</p>
<p>
Next click the next button
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/d220cd39-85bd-4787-9790-4e0561163496"

</p>
<p>
Next click the next button
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/b0063385-4968-46e1-a1bf-f531b6a8d134"

</p>
<p>
Next click the install button
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/0af0bb70-9dd4-42c8-8d93-1d76779860d5"

</p>
<p>
Now create an account in the bottom left, if you have an account type your username and password
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/1b460d5e-dfd7-42a7-9dbc-1ac29e2e75fe"

</p>
<p>
Now once it loads click the skip button unless you want a tour
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/897ffe83-17a4-4773-bd6f-5a690619ee35"

</p>
<p>
Next connect to whatever country you want for this I will pick Japan, then click the purple button
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/57da0780-066c-4a37-8a66-033c3ee447be"

</p>
<p>
Next let the VPN load dont click anything 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/e7da93c2-2a41-4131-8633-f70fdd331d11"

</p>
<p>
Now if you see a Reconnecting tab dont click cancel, let the process finish 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/97526d51-79ea-4ede-a408-c23061154792"

</p>
<p>
Now go back to whatisyouripaddress.com and refresh the page and you will see your IP, city, region, and country changed
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/d59e8673-4d61-4707-990b-10640a370df7"

</p>
<p>
Now go back to Proton VPN and click disconnect, you can also click on any of Japan's IP that are availble on the left side once you click the arrow to expand the available IP
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/a22a44a1-a569-4f78-a1d6-842bcfe7ae99"

</p>
<p>
Now click the bar at the top left and click sign out to sign out of your account
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/5ede0145-ba14-48d8-b6d0-263fab33167d"

</p>
<p>
Next go back to Microsoft Azure and type Resource Groups click on Vm-practice and type it in the delete resource group tab then click the delete red tab
</p>
<br />


<p>
<img src="https://github.com/user-attachments/assets/ff581695-4def-4e33-b47b-29b8f1b51d1a"

</p>
<p>
Then just confirm the process by clicking delete again 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/706b4f21-0dba-4258-98b7-5329f6ef5d26"

</p>
<p>
Now go to the next resource group if you have one and click delete resource group
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/06d53b05-d4ba-425d-aa50-f737edf45558"

</p>
<p>
Then type the name in and click the red delete button
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/a9315381-8226-452d-9f63-1209e12816ae"

</p>
<p>
Then to finish the process click delete again 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/52a4ecf2-1108-46e9-9921-7d42416260d4"

</p>
<p>
Then if you want to see the process click the bell icon on the top right 
</p>
<br />
