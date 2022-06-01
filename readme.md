# Microsoft-Engage-2022
This is my project for Microsoft Engage 2022 under **Face Recognition track to diagnose diseases**. 
<p align="center">
<a href="https://acehacker.com/microsoft/engage2022/">
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/micro-mediDetect-age/transmicromedi.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
</a>
	<h2 align="center">micro-MediDetect-age</h2>
	<h3 align="center">A non-invasive and no cost diagnosis solution to check pulse rate and genetic diseases remotely and safely...<h3>
	<br />

  [![DOCS](https://img.shields.io/badge/Documentation-see%20docs-blue?style=flat-square&logo=appveyor)](https://docs.google.com/document/d/1ywypT24DVXsVZUW7jRAg4Z631YMjOSPI4hjyhklrhx8/edit?usp=sharing) 
  [![UI  ](https://img.shields.io/badge/User%20Interface-Link%20to%20UI-yellow?style=flat-square&logo=appveyor)](https://www.figma.com/file/PLF0WhBHO1Fgt3LyIuLXZZ/micro-MediDetect-age?node-id=1%3A2)
[![VIDEO ](https://img.shields.io/badge/Video-Link%20to%20Video-blue?style=flat-square&logo=appveyor)](https://youtu.be/QJ9o6T1rgBw)
 </p>
			  

<p align="center">
    .
    <a href="https://docs.google.com/document/d/1ywypT24DVXsVZUW7jRAg4Z631YMjOSPI4hjyhklrhx8/edit?usp=sharing"><strong>Check Project Documentation »</strong></a>
    <br />
    <br />
   												      
  <p align="center">
   .
    <a href="https://youtu.be/QJ9o6T1rgBw"> Project Video Demo Link </a>
    ·
    <a href="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/issues">Report Issues</a>
    ·
    <a href="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/issues"> Suggest/Request Feature</a>
	</p>
</p>

---
## 🔗 Important Links

 👉[Video Demo](https://youtu.be/QJ9o6T1rgBw) <br>
 👉 [Documentation](https://docs.google.com/document/d/1ywypT24DVXsVZUW7jRAg4Z631YMjOSPI4hjyhklrhx8/edit#heading=h.tvto5hccx0b6) <br>
 👉 [UI Figma Design](https://www.figma.com/file/PLF0WhBHO1Fgt3LyIuLXZZ/micro-MediDetect-age?node-id=1%3A2) <br>
 
	
## 📋 Project Overview
micro-MediDetect-age is a fully functional **disease diagnosing website using face recognition
technology made using Agile development methodology** as part of the Microsoft Engage 2022
program. 


## 🔖 Introduction
	
Taking a pulse is a very important part of heart health checks. A person's resting heart rate is a major factor in determining a person's risk of a heart attack. So, what if you could determine the pulse rate with just using webcam/camera?   Early detection of Genetic Diseases  help in early intervention and treatment, which may either cure the disease or improve the outcome of the patient but still doctors struggle to recognize as they don't spend much time with them.
												    
Keeping all this in mind, introducting you my project micro-MediDetect-age...
												    
micro-MediDetect-age is a non-invasive and no cost diagnosis solution to check pulse rate and genetic diseases remotely and safely.



![GIF demo](https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Engage22Project-GIF.gif)

## 💡Features
	
👩‍💻 **User Login/ Signup**  <br>
1.1 Description: Users can securely login with their email id and password used <br>
for creating an account on micro-MediDetect-age <br>
1.1.1 Input: Name, email ID, password for account creation, and email ID <br>
and password <br>
1.1.2 Output: Redirect if successful login/ account creation and error
message displayed if wrong details entered.  <br>

 🫀 **Heart Rate Detector Model:** <br>
2.1 Face Recognition <br>
2.2 Forehead detect in face <br>
2.2 Heart Rate/ Pulse Rate Detection Model <br>
2.3 Web Electrocardiogram Generation <br>
**This feature will help to diagnose critical diseases...Some of them are as follows:** <br>
$ Coronary artery disease <br>
$ Heart Attack <br>
$ Ventricular Tachycardia <br>
$ Cardiomyopathy (Where the heart walls becomes thickened or enlarged) <br>
$ Atrial Fibrillation/Asthma --(People with asthma could be at 1.5 times higher risk of developing atrial fibrillation) <br>
$ COPD (Chronic Obstructive Pulmonary Disease)	<br>	
$ Arrhythmias <br>
$ Pneumonia --(it can push heart into abnormal fast rhythms) <br>												    
 👁️  **Wilson Syndrome Detector** <br>
3.1 Face and Eye Recognition <br>
3.2  Kayser-Fleischer rings / Brown rings detection in eyes to detect disease <br>

 ⚕️ **Genetic Disease Detector**  <br>
This feature is able to **detect the following genetic disorders at an early stage so that it can be cured to an extent /proper treatment can be done** : <br>
 $ Down’s Syndrome <br>
 $ FragileX Syndrome (FXS) <br>
 $ Marfan Syndrome <br>
 $ Angelman <br>
 $ Cornelia de Lange (CDL) <br>
 $ Turner Syndrome <br>
 $ Sotos Syndrome <br>
**Methodology Used**
> - On top of VGGFace, I used four Fully Connected layers. Then, on top of it, three fully linked layers and an SVM classifier. The Transfer Learning method used  allowed to re-use previously learnt features. <br>
> - The SGD optimizer was employed with a very low learning rate of 0.0001 and a momentum of 0.9. <br>
> - When the validation loss stopped improving, a callback was defined in keras to reduce the learning rate by 0.1. <br>
> - In each example, the batch size was set at 32. <br>
> - As a baseline for good categorization, we try to reduce cross-entropy loss. <br>
> - The deep learning classifier has been created using the keras (v2) package. <br>
> - The Tesla K80 GPU is used to train the model. <br>
> - The accuracies stabilised around 100 epochs after a total of 200 epochs were run. <br> 									

**Find all the Google Colaboratory notebooks of genetic disease detector here :**  https://drive.google.com/drive/folders/1wFTd4E8ubqkWdIrulmBdffUXk092Hk-m <br>
 🏥 **Immediate Hospital Finder** <br>
 🤖 **Voice Chat Bot**  <br>
 🧻 **Proper Documentation** <br>

<br>

## 🧰 Tools and Technologies used

 **Frontend:**
● HTML
● CSS
● Javascript
● Jquery <br>
**Backend:**
● PHP
● MySQL for database <br>
**Building models/features:**
● Python
● Machine Learning
● Tensorflow
● Opencv
● Pytorch
● Streamlit
● Numpy
● Deep Learning <br>
**Design**												    
● Figma <br>


## ⚙️ Instructions for running project locally

1. Clone the repo https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22 <br>
2. Download the following packages of python to run Pulse Rate Detector Model first and then run the app.py file . <br>

   altair==4.2.0 <br>
   av==9.2.0 <br>
   matplotlib==3.4.2 <br>
   numpy==1.22.4 <br>
   opencv_python < 4.5.2.54 <br>
   Pillow==9.1.1 <br>
   requests==2.25.1 <br>
   st_annotated_text==3.0.0 <br>
   streamlit==1.9.0 <br>
   streamlit_webrtc==0.37.0 <br>
<p align="left">
   <a href="#">
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/app.png?raw=true width="600", height="300" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pulseDetect.png?raw=true width="600", height="300" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/micro-pulse-age.drawio.png?raw=true width="600", height="300" alt="Microsoft Engage 22"/>
	
</a>
</p>

   Heart Rate Detection Model is deployed locally using streamlit and then by running app.py , it opens on link: http://localhost:8501/ <br>

3. Download the folder from github and  xampp server in that xampp->htdocs paste the folder and add the sql database file to phpmyadmin and run the website locally.
  Also launch the heart rate monitor locally following step 2 locally.	<br> <br>										    


 
## ◼️Project Methodology

**Agile Software Development Methodology** is used in making micro-MediDetect-age
by dividing the large project feature into small chunks and agile sprints. Dividing the
project into two agile sprints with each sprint further divided in 3 phases: <br>
1. **Planning and Prototyping Phase:** In this proper workflow structure was made
with techstack and functionalities to be implemented. Followed by that,
prototyping by designing the UI on Figma and then implementation of it as
website. <br>
2. **Implementation**- building the fully functional features in this phase. <br>
3. **Testing and Review** <br>
**First Sprint:** <br>
**Starting Date:** 7th May, 2022 <br>
**Ending Date:** 20th May, 2022 <br>
**Features Developed and Released:** Heart pulse rate detection model using face
recognition and deployment using streamlit, account creation system, Wilson
Detection model. <br>
**Second Sprint:** <br>
**Starting Date:** 20th May, 2022 <br>
**Ending Date:** 26th May,2022 <br>
**Features Developed and Released:** Involved ironing out bugs from the first sprint,
website creation, genetic diseases prediction feature using face recognition, voice
chatbot and immediate hospital finder. <br>
Following Agile SDLC involved releasing the features like heart rate model by
deploying it and enhancing its accuracy parallely with other features. It resulted in
completion of project in time, ready to make changes and frequent delivery of
product. <br>



<h3 align="left">Tools and Technologies Used:</h3>
<p align="left">
<a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a>
<a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a>  <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a>  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a>
 <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a>
</p>
  
 ## 💻 Project Pictures
<p align="center">
<a href="https://acehacker.com/microsoft/engage2022/">
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg1.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg2.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
   <img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg3.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg4.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg7.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/Screenshot%20(12).png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg5.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg6.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg10.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg11.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg9.png?raw=true width="450", height="130" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/pg%2013.png?raw=true width="700", height="130" alt="Microsoft Engage 22"/>
</a>
 
 ![GIF demo](https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Engage22Project-GIF.gif)

## 🚩 Future Scopes:-
Feature | Explanation
------------ | -------------
Deployment of Genetic Disease Detection Model |   Deploying genetic disease detection model and integrating it on website.
Skin Disease Detection  | Making Skin Disease Detection model using face recognition and adding it as one more service
OTP Security System | Automatic OTP Snder on mobile and email during login as one more security layer using WebOTP API. 

## 🔶UML Diagrams, Testing Results
<p align="center">
<a href="https://acehacker.com/microsoft/engage2022/">

	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/register%20sequential.png?raw=true width="700", height="300" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/login%20sequential.png?raw=true width="700", height="300" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/password%20authenication.png?raw=true width="700", height="300" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/Testing%201.png?raw=true width="700", height="300" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/Testing%202.png?raw=true width="700", height="300" alt="Microsoft Engage 22"/>
	<img src="https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/Project_Images/micro-pulse-age.drawio.png?raw=true width="700", height="300" alt="Microsoft Engage 22"/>
</a>
</p>

 ## Contributors

<table>
	<tr align="center">
		<td>
		Priyanka Kumari
		<p align="center">
			<img src = "https://github.com/PriyankaKumari-2002/micro-MediDetect-age-Microsoft-Engage-22/blob/master/micro-mediDetect-age/Priyanka.jpeg" width="150" height="150" alt="Priyanka Kumari">
		</p>
			<p align="center">
				<a href = "https://github.com/PriyankaKumari-2002">
					<img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
				</a>
				<a href = "https://www.linkedin.com/in/priyanka-kumari-4736b61ba/">
					<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>
				</a>
			</p>
		</td>
	</tr>
</table>


<p align="center">
	Made with :heart: by <a href="https://github.com/PriyankaKumari-2002">Priyanka Kumari</a> <br>
	You can also check [My Project Documentation/ Report](https://docs.google.com/document/d/1ywypT24DVXsVZUW7jRAg4Z631YMjOSPI4hjyhklrhx8/edit#heading=h.psnahpqn4tlc) <br>
	Thank you ! Microsoft Team for such a wonderful mentorship program ❤️
</p>
