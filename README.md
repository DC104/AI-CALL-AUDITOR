# GEN-AI-AUDITOR1
1. In these project we have made a call auditor which will analyse the call specifically for customer support releated .
2. It  will analyse the call based on the customer tones and alls .
   
# Installing dependencies
1. At first step clone this repo or manually downaload all files to your local computer from this repo based on your preferences
2. Then create a virtual enviorment using this command : "python -m venv your-enviorment"
3. After that activate that virtual enviorment using this command : "your-enviorment\Scripts\activate"(for windows)
4. After that install all dependencies and modules from requirement.txt by running this command : "pip install -r requirement.txt"
 
# Now Run this app
* after completing all the above mentioned steps run this app using this command : "streamlit run app.py" and you will see app will get open in this
web address - "http://localhost:8501/"

# How to start analyze and use the app
1. select any audio files(specifically customer supporting recording) from your device then upload it using upload button. 
2. After that provide your own gemini api Key .To create gemini api key follow this step:
    1. search Gemini api key in browser and then gemini ai studio will be opened.
    2. From there click on "Get your own api key" button.
    3. After that a new page will be open from there sign in with your existing google account and click on create api key.
    4. After that a small page will be shown where you have to give any name for the api key and from the dropdown select "default gemini project"
    5. Now your api key is ready to use . Now copy the key using copy button which is available right side of the api key.
   
3. After copyting the apikey paste it in the api key section . Now you are ready to start the audit file.
4. In the manager email section give your email and click "start audit" button .
5. Now app will analyze the recording file and based on the policy it will generate score .
6. If the score will be less < 30 then an alert email will go to your email address .

# Important points
1. while downloading the file please set the manager email and app password in the "reporting.py" file other wise app will show error.





   
  

