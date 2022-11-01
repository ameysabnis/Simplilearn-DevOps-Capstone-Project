<ol>
  <li type ="1"> Create a new EC2 cluster with Elastic IP enabled.</li>
  Login into your <b>AWS console</b>, go to <b>EC2</b> section, under <b>'Instances(running)'</b>, click on <b>'Launch Instances'</b> to create a new instance.
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199164486-5c363526-3c35-49fe-b0e7-acf1ac530621.png">
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199164731-940feb2c-1f7c-447f-81a7-3538c5080fe2.png">
  <br>
  Set name as <b>'SL_DO_Capstone_Project'</b>, select the OS as <b>Ubuntu Server 22.04 LTS</b>, Instance type as <b>t2.micro</b>.
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199165534-4821f6fb-f721-4f44-950b-3ccfca4bfefe.png">
  <br>
  Create a new or link an existing <b>key pair</b>, under Network Settings <b> Create a new security group and select all 3 options.</b>
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199165618-6bdb0c0f-7626-4e71-bfc8-580204c3dd17.png">
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199165698-371d367f-e02b-4ba7-a6b4-51928d4c16aa.png">
  <br>
  Click on <b>Launch Instance</b> at the bottom of the page.
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199165774-19f2be07-c106-420e-9d0e-55aa3f5d9491.png">
  <br>
  The new instance shall be up and running as below:
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199166229-f5a60b2a-5673-423d-8813-cee5a9b29750.png">
  <li>Create a <b>new Elastic IP for the new instance</b> so that the public IP of the instance <b>doesn't change every time the instance is restarted.</b>
  Under <b>'Network & Security' -> Elastic IPs'</b>, click on <b>'Allocate IP address'</b>.
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199167655-456fe33f-0200-4499-9503-ce0f2e3860e2.png">
  Rename the IP address as <b>'SL_DO_CP_IP_Address'</b> as below:
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199168118-c069e6b0-a373-4d9e-bdf8-284f939ad0b8.png">
  Click on <b>'Actions'</b> and select 'Associate IP address'</b> and <b>link the newly created instance</b> and, finally click on >b>'Associate'</b> as below.
  <img width="912" alt="aws manageent console" src="https://user-images.githubusercontent.com/84242168/199168922-6604803a-3d22-467f-991e-114ace235830.png">
  The <b>public IP of the instance won't change</b>, even after the instance is rebooted.

  



  
  
  
'
  
