### Identifying depression markers via social media and building an early-stage recommendation engine

- Depression is one among the many causes of disability throughout the planet. If untreated, depression can cause suicide, which may be a leading explanation for death among youngsters. 
- Treatment for depression isn't accessible due to various factors like social stigma, unawareness, and lack of medical professionals. With the event of technology, studies are done to identify patterns for mental illnesses. 
- The widespread use of smartphones and social media apps provides a chance for continuous monitoring of a person through their usage patterns, alongside social media data, provide insights about the psychological state of the person, and that can be used to predict depression and recommend activities that help in treating the condition early, as unchecked emotions at an early stage snowball to depression and anxiety at later stages.
About our proof of concept:

### POC details 
Through our POC, we built a recommendation system, combining the social media sentiments (text/media) to arrive at the mental state of a person. The weights/probabilities from each text/media model are utilized to arrive at a recommendation. The recommendations are generic and are rule based.

<img width="692" alt="Screenshot 2022-04-12 at 3 17 55 PM" src="https://user-images.githubusercontent.com/17350312/162932717-79b18a9e-718c-44c9-aadc-cffa2bac6e1f.png">


### Modelling tools and packages

- Text2emotion 
    - Python package which yields the emotional context behind a given text input. It has the capability to incorporate emojis or shortcodes. The outcome is     based on 05 categories - Happy, angry, sad, surprise, fear
- Facial expression Recognition 
    - We have used Pytorch to achieve our  computer vision task. We created a Convolutional Neural Network Model with Residual Networks which will increase the number of channels of the face image data and decrease the dimension. 

### Conclusion and future scope

- We were able to build an early stage recommendation engine based on social media inputs. Combining the power of deep learning models with research we carried out to understand the depression markers. Currently we are using thresholds of weights to arrive at static recommendations. In future we hope to make the system more robust and able to come up with personalized recommendations based on user activities on social media and other platforms. 
- Expand the paradigm to personal/demographic info, screen time spent, availability of calendar, work schedules, health and eating patterns we can further personalise and accurately identify the markers and suggest tailor made recommendations catering to his/her interests.
- People tend to post happy images more often on social media making it unreliable to detect the true and current emotion of that person ,so for further development of our project we would like to make use of Haar-Cascade Classifier,OpenCV to detect persons face through the camera and identify emotions real time especially when taking zoom calls,office meetings for an accurate model.


### References
- https://www.helpguide.org/articles/depression/depression-treatment.html 
- https://www.researchgate.net/publication/349451635_Engaging_Smartphones_and_Social_Data_for_Curing_Depressive_Disorders_An_Overview_and_Survey
- https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1184/reports/6879557.pdf 
- https://www.researchgate.net/publication/350488667_EmoCure_Utilising_Social_Media_Data_and_Smartphones_to_Predict_and_Cure_Depression
- https://www.researchgate.net/publication/349451635_Engaging_Smartphones_and_Social_Data_for_Curing_Depressive_Disorders_An_Overview_and_Survey 
- https://pypi.org/project/text2emotion/
- https://jovian.ai/learn/deep-learning-with-pytorch-zero-to-gans 
