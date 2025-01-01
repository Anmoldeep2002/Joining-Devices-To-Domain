<h1>Joining Devices To The Domain (Helpdesk and Client Device)</h1>


<h2>Description</h2>
<p>In this section, I will allow the helpdesk and client device to join the domain that I've created for this project.</p>


<br />

<h2>Step-by-Step Walk-Through:</h2>


<p align="center"> 
STEP 1 (Adding Helpdesk Device To The Domain): <br/>
<img src="https://i.imgur.com/GNLA84e.png" height="70%" width="70%"/> </p>


<p align="center">The first step in connecting the Windows 10 device to the domain is to open "FILE EXPLORER".</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 2: <br/>
<img src="https://i.imgur.com/jXDIJRf.png" height="70%" width="70%"/> </p>


<p align="center">I then right-click "THIS PC" and select "Properties" to access further settings for the Windows 10 device.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 3: <br/>
<img src="https://i.imgur.com/ISiCjUq.png" height="70%" width="70%"/> </p>


<p align="center">Now I'm in the "PROPERTIES" section of the Windows 10 device. As you can see, there are many options available, but in this case, I chose "ADVANCED SYSTEM SETTINGS" to access further domain settings.</p>

<hr width="100%" size="2">

<br />

<p align="center"> 
STEP 4: <br/>
<img src="https://i.imgur.com/3VmXGrq.png" height="40%" width="40%"/> </p>


<p align="center">This is the "ADVANCED SYSTEMS SETTINGS" section, and from here, I select the last option, "change the domain or workgroup".</p>

<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/6mR4IsO.png" height="70%" width="70%"/> </p>


<p align="center">From here, I can finally add the Windows 10 device to a domain. I enter the domain name into the domain section. I enter "office123.com" as the domain and click "OK" to move on to the next step.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/qYkwycL.png" height="70%" width="70%"/> </p>


<p align="center">I'm asked to enter a username and password so that the Windows 10 device can join the domain "office123.com". The login and password should be associated with a domain-accessible account. In this example, only the Server 2016 device has access to the domain, therefore I enter its login credentials to allow this Windows 10 device to join the domain. I then select "OK" to successfully allow this device to join the domain.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/s8OTjA6.png" height="70%" width="70%"/> </p>


<p align="center">The "Welcome" message on the photo above indicates that the Windows 10 device has successfully joined the domain. I then restart the device to see whether I can log in with a domain account that I had previously created.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/o0YfVDf.png" height="70%" width="70%"/> </p>


<p align="center">As you can see, the Windows 10 device now offers me the choice to sign in to the domain "office123.com". This indicates that the device successfully joined the domain.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/ctNL8Z1.png" height="50%" width="50%"/> </p>


<p align="center">I'm back in the "PROPERTIES" section of the Windows 10 device. As you can see, the device has successfully joined the domain under the computer name "Desktop1.office123.com". This device can now be identified as "Desktop1" in Active Directory's "COMPUTERS" section.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/6QJR2LJ.png" height="70%" width="70%"/> </p>


<p align="center">Finally, I can access "ACTIVE DIRECTORY USERS AND COMPUTERS" from the Windows 10 device using RSAT tools. As you can see, the domain "office123.com" has finally appeared, and the Windows 10 device with the name "DESKTOP1" has appeared in the "COMPUTERS" folder of Active Directory.</p>

<hr width="100%" size="2">

<p align="center"> 
STEP 5 (Adding Client Device To The Domain): <br/>
<img src="https://i.imgur.com/E01D1ZY.png" height="40%" width="40%"/> </p>


<p align="center">Now, I'd like to add the client "DESKTOP2" device to the domain "office123.com". I went to the device's "PROPERTIES" section and selected the domains section. I entered the domain "office.123.com" and then selected "OK" to move on to the next step.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/m8Re7CM.png" height="70%" width="70%"/> </p>


<p align="center">I'm requested to enter a username and password so that the "DESKTOP2" device can join the domain "office123.com". The login and password should be associated with a domain-accessible account. In this situation, only the newly formed "HELPDESK" account has access to the domain, therefore I provide its login credentials to allow this "DESKTOP2" device to join the domain. I then select "OK" to successfully allow this device to join the domain.
The second image shows that the "DESKTOP2" device has successfully joined the domain, as evidenced by the "Welcome" message above.</p>


<br />
<br />

<p align="center"> 
<img src="https://i.imgur.com/Y8SXJfY.png" height="70%" width="70%"/> </p>


<p align="center">I'm on "ACTIVE DIRECTORY" from the Helpdesk account to see if the "DESKTOP2" device has been added to the domain. As you can see from the "COMPUTERS" folder, the device "DESKTOP2" was successfully added and is now part of the domain.</p>












<a href="https://www.example.com">
  <button>NEXT</button>
</a>
