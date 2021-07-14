# Entity-Recognization-azure
 Recognize entities in text with the text analytics API in Azure

# Intro to Entity-Recognization and Features :
 ### Introduction to entity recognition :
Entity recognition is a part of the Text Analytics service under Azure Cognitive Services. You can provide the service with unstructured text and it will return a list of entities, or items in the text that it recognizes. The service can also provide links to more information about that entity on the web. An entity is essentially a type or a category that certain text elements can fall under. The service supports two types of recognition.

* Named entity recognition
* Entity linking

📌 1. Named entity recognition :
                             Named entity recognition provides the ability to recognize and identify items in text that are categorized according to some pre-defined classes. Version 3, which is in preview, will add the ability to identify more items such as personal and/or sensitive information like phone numbers, social security numbers, email addresses, and bank account numbers.

📌 2. Entity linking :
                     The entity linking feature helps to remove ambiguity that may exist around an identified entity. A document may contain an entity such as ARES, which could mean the Greek god of war or it could be an acronym for Amateur Radio Emergency Services. Text Analytics is not able to make this linking on its own. It requires a knowledge base, in the required language, to provide the necessary recognition. This is a way to customize linked entities to your own organizations list of entity elements.
                     
 ## Entity types Example :                    
 ![Screenshot 2021-07-14 at 1 05 26 PM](https://user-images.githubusercontent.com/53942720/125582092-83d7c99f-ab2a-4b2c-ad62-cace5c297e22.png)
 
 
# To Run this project follow the following instructions :
 ## NOTE : to run this project require python 3.8 version 
 
 1) Activate Text Analytics resource in azure .
 2) It take some time to activate services, after that copy subscription_key and paste it in our python file at **_subscription_key_** variable.
 3) After that copy endpoint key and paste it in our python file at **_endpoint_** variable.
 4) Select the Run Python File in Terminal or right-click anywhere in the code editor and select Run Python File in Terminal.
 5) If your code contains no errors, the resulting JSON output should be sent to the output window and is displayed here.
 
 ![Screenshot 2021-07-14 at 1 25 25 PM](https://user-images.githubusercontent.com/53942720/125585062-e200f553-1d98-47d9-9872-b8d959366e39.png)





                    
                     
