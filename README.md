# Krushi Sheni

# AUTOMATION AND OPTIMIZATION OF MODERN FARMING
This website is created as a farmers’ friendly interface. By providing the option to choose a language that the user is most comfortable with, you are ensuring that language barriers do not come in the way of the farmer's ability to access and use the webpage. The navigation bar on the webpage is well-organized and easy to understand, with the Disease Detection option being prominently displayed. This ensures that farmers can find what they need quickly and efficiently, without having to navigate through unnecessary information. The step-by-step instructions provided on the web page make it easy for farmers to use your service. By breaking down the process into simple and easy-to-follow steps, you are ensuring that farmers who may not be tech-savvy can still use the webpage without difficulty. The webpage's ability to predict the disease affecting the leaf and provide customized solutions to mitigate the disease is particularly useful for farmers. This saves them time and money by providing a targeted solution to their specific problem. By displaying the product details of fertilizers on the Amazon website, farmers can easily purchase the recommended fertilizers. Additionally, by providing access to User Manuals for these fertilizers, farmers can make informed decisions about the products they choose to use. Finally, by displaying various government schemes related to the purchase of fertilizers, your webpage helps farmers access subsidies and other benefits offered by the government. This ensures that farmers are able to access the resources they need at a lower cost, making it more affordable for them to maintain their crops.

A.	Website flow
Step 1: Open the webpage.
Step 2: Choose the appropriate language according to the user’s preference.
Step 3: Click on the Disease Detection option in the webpage's navigation bar.
Step 4: Upload a JPEG file of the leaf that you want to test for disease detection.
Step 5: A pre-trained machine learning model will process the input image and predict the disease affecting the leaf.
Step 6: Display appropriate solutions to mitigate the predicted disease.
Step 7: Suggest the required fertilizers to be used on the plants and display the product details from the Amazon website:
Step 8: The user can also consult the User Manual of the fertilizers and make informed decisions.
Step 9: Display various government schemes related to the purchase of fertilizers for the benefit of farmers.

This methodology has the potential to improve agricultural productivity and profitability by enabling early detection and mitigation of crop diseases.

![architecturaldiagram](https://user-images.githubusercontent.com/78720027/234005000-cbbcd985-2919-4f23-9bb7-ab2d21480281.png)

Fig. 1. Architecture Diagram

We will get the input of the crop disease from the farmer then the crop disease is detected from the crop image and the symptoms, solutions, fertilizer names are generated from the chatGPT API and the fertilizer are fetched from the e-commerce website and the details like price, rating, name, and the link to the e-commerce website are added. The user manual is generated for each fertilizer from the chatGPT API. This all is with a google translator with more than 130 languages. The government schemes for the farmers are fetched from the government website with essential details.

# Result:
To analyze the website, we can evaluate its features and performance based on various criteria, such as usability, accuracy of disease detection, effectiveness of solutions provided, and overall user experience.

![image](https://user-images.githubusercontent.com/78720027/234005311-c96cbca2-e83c-4218-93ff-c9675fbe79b4.png)

Fig. 2. Base navigation

![image](https://user-images.githubusercontent.com/78720027/234005357-b0e1fe34-ccc4-44f0-abf2-8db30142f57b.png)

Fig. 3.  Government Scheme
 
![image](https://user-images.githubusercontent.com/78720027/234005460-9b061ee0-dfb7-4ba6-bc70-09972a639db3.png)

Fig. 4. Government scheme translated into Gujarati Language
 
![image](https://user-images.githubusercontent.com/78720027/234005499-40f0e665-4928-427d-b115-c2d13d0fad3c.png)

Fig. 5.  Example page for farmer to know different languages available in website
The accuracy of disease detection depends on the quality of the input image and the performance of the machine learning model. The machine learning model must be trained on a diverse dataset of crop diseases to achieve high accuracy. The website could also incorporate features that guide users on how to take appropriate images for accurate disease detection.
 
![image](https://user-images.githubusercontent.com/78720027/234005551-03755347-5dcc-4472-a345-f82e9302d22e.png)

Fig. 6.  Add the image of Infected leaf
 
![image](https://user-images.githubusercontent.com/78720027/234005594-89b71556-848d-446a-97a4-dfa2ec984ef6.png)

Fig. 7. Browsing image from folder
 
![image](https://user-images.githubusercontent.com/78720027/234005627-ee699594-4e98-4d72-8cd3-29d1b63b6232.png)

Fig. 8.  Leaf disease prediction, its symptoms, its solution (organic) and the top 3 fertilizers
 
![image](https://user-images.githubusercontent.com/78720027/234005660-6c93aab3-bd43-40fc-96ac-355a0f4c23fc.png)

Fig. 9. Linked to amazon.com website for the fertilizer
 
![image](https://user-images.githubusercontent.com/78720027/234005707-595adb63-aa6f-4e07-94dc-3b7427da2fca.png)

Fig. 10. Generated user manual for the fertilizer
 
![image](https://user-images.githubusercontent.com/78720027/234005748-1d229cde-b2dd-4224-95c0-fc38e037f51a.png)

Fig. 11. User manual in Tamil

# Run code:
Flask App

```
source venv/bin/activate or .\venv\Scripts\activate
```
Activates the virutal environment required for the project dependency isolation.

```
pip install -r requirements.txt
```

Installs libraries and dependencies listed in requirements.txt in active environment.

```
python run.py
```


React App

```
cd my-app
```

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```
npm install
```

In order to run the application Type the following command

```
npm start
```

The Application Runs on localhost:3000
=======
 
