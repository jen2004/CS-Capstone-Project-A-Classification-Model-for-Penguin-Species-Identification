# CS Capstone Project: A Classification Model for Penguin Species Identification

<img src="https://github.com/user-attachments/assets/3d5a3e2c-7bc6-40b2-bc72-ca535d60edbe" width="400" />

Photo Source: Kristen Gorman

I completed this project during my 5th semester at WGU as a part of the class Computer Science Capstone C964.

For this project, I developed a machine-learning-based tool for the fictional World Penguin Conservation Organization (WPCO) to improve penguin species identification in the field. By utilizing the Palmer Penguins Dataset, the tool predicts species based on two simple features: bill length and bill depth. It replaces traditional methods that are time-intensive, invasive, and potentially stressful for penguins, while also reducing risks to researchers working in harsh Antarctic environments. The user-friendly tool, implemented in a Jupyter Notebook hosted on Google Colab, allows researchers to input bill measurements and obtain predictions within seconds, enhancing both efficiency and accuracy.

The project followed the CRISP-DM methodology, involving data preprocessing, exploratory data analysis (EDA), and logistic regression modeling. Data cleaning and feature selection ensured high-quality input, while the model achieved 97% accuracy on the test set, validated through accuracy scores and confusion matrix analysis.

For the complete project requirements, please refer to the “Task Overview.pdf” file.  

For my complete project report, refer to “Capstone Report.pdf”.

Quick Start User Guide

To open and use the Penguin Species Classification Tool and the Descriptive Methods and Visualizations Tool, you will need the following:
1.	Windows 10 or higher.
2.	A Google account - Since the tool is hosted on Google Drive, a Google account is required. If you don’t have one, you can create a free Google account here: [Create a Google Account](https://accounts.google.com/lifecycle/steps/signup/name?ddm=1&dsh=S-2026582058:1736179676853473&flowEntry=SignUp&flowName=GlifWebSignIn&TL=AE--Llxb3Mblayj1KetpvK5y9YL-meV8XxDieu9SUnZQZe13piY2j95vxeUr1htC&continue=https://accounts.google.com/ManageAccount?nc%3D1)

3.	A stable internet connection.

Follow these instructions to use the Penguin Species Classification Tool:

1.	Download the file “penguin_dataset.csv” to your local machine. And make sure that you name it “penguin_dataset.csv” (<<Use this name exactly!)
2.	Sign in to your Google Drive account.
3.	Open the Jupyter Notebook in Google Colab by Ctrl + clicking this link: [Penguin Species Classifier Tool](https://colab.research.google.com/drive/1RB8iSRPPP8LA0K7Bhd2xRc21KiQwls2z?usp=drive_link)
4.	Create your own copy of the Notebook by going to File > Save a Copy in Drive.
5.	 In the copied notebook file, from the Menu Bar at the top of the page, click on “Runtime” > “Run All”.
6.	 After a few seconds, scroll to the bottom of the output cell. A button labeled “Choose Files” will appear. Click this button, select the “penguin_dataset.csv” file from the location where you saved it, and click “Open”. This will upload the file to Colab’s temporary storage.
7.	Once the code finishes running, scroll down to the bottom of the output cell. You will see a green button labeled “Predict Species”. Above this button, there are text boxes where you can input values for bill length and bill depth to get a prediction for the penguin species.
8.	Input the bill length and bill depth (in millimeters) into the respective boxes. Enter a bill length between 32.0 mm and 60.0 mm, and a bill depth between 13.0 mm and 22.0 mm. Round your inputs to the nearest 0.1 mm. Then, Click the “Predict Species” button.

<img src="https://github.com/user-attachments/assets/774a2b58-e75e-44c4-9929-8ad0acfa5491" alt="2" width="400">


9.	Your prediction result will appear under the “Predict Species” button, labeled as “Predicted Penguin Species:”.<br><br>
    

<img src="https://github.com/user-attachments/assets/bb0d37ba-ffce-4a03-a2ed-748e77267751" alt="1" width="500">

<br><br>

10.	Below the species prediction tool, you can view the accuracy analysis for the model, including the accuracy percentage and the confusion matrix.


