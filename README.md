# Microsoft-Sentinal-SIEM

<h2> In this Lab, I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. We will observe live attacks (RDP Brute Force) from all around the world. We will use a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map! </h2> 


 <h2>Setting Up the Vm environment and Log connections. A rule as been put in place that allows RDP traffic through, the firewall disabled as well. </h2> 


![image](https://github.com/Applepancakes/Microsoft-Sentinal-SIEM/assets/158091426/fe92a5bf-5c91-485e-be0d-5ca5220dcc90)

 
 

 <h2>This is my RDP successful connection to the VM. We will see the powershell script in the following image which we will track the failed attempts(the attacking bots)</h2> 


![image(1)](https://github.com/Applepancakes/Microsoft-Sentinal-SIEM/assets/158091426/b3b040bd-4d57-4b72-8244-10949c7909c6)



<h2>The public IP of the VM as been discovered and we can see the attacks pouring in </h2> 
 

![image4](https://github.com/Applepancakes/Microsoft-Sentinal-SIEM/assets/158091426/6599d2f1-c4f2-4d8c-9815-ea399de690da)

 


<h2> World map of incoming attacks after 48 hours pulled with Azure Custom log (built custom logs including geodata)</h2>
 
 
![image6](https://github.com/Applepancakes/Microsoft-Sentinal-SIEM/assets/158091426/9d684f53-facb-40bc-ac39-6eb91d4e02a1)


 

-
