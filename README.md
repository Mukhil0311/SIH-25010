# Smart India Hackathon Workshop
# Date: 25/09/2025
## Register Number: 25017690
## Name: MUKHIL S
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
<h3>SOLUTION</h3>
<ul><li>The Smart Crop Advisory App is a complete digital solution created to support small and marginal farmers by giving them useful advice for better farming. Many farmers face challenges such as not knowing which crop will grow best in their soil, how much fertilizer they should use, how to detect pests or diseases, or how to deal with sudden weather changes. This app combines all these solutions into one easy-to-use platform. One of its important features is crop suggestion, where the app recommends the best crops to grow depending on the soil type, season, and location. This helps farmers increase yield and reduce cost. Another key feature is pest and disease detection. Farmers can take a photo of their crop, and the app uses Artificial Intelligence (AI) to find whether the plant is affected. If a problem is detected, the app gives instant remedies and control measures. The app also provides weather forecasts and alerts, helping farmers plan their farming activities and protect crops from damage due to heavy rain, storms, or heatwaves. Along with this, the app guides farmers on the right type and quantity of fertilizers needed for each crop, saving money and preventing soil damage. To make it farmer-friendly, the app supports many Indian languages and offers voice guidance, so even farmers who cannot read well can use it easily. Another big advantage is that the app works in offline mode, which is helpful for farmers in villages where internet connectivity is weak. This solution is special because it does not give general advice like many other apps; instead, it provides personalized suggestions by using AI, government data, and weather updates. The app is simple in design but powerful in features, making it easy to use even for farmers with little technical knowledge. By using this app, farmers can grow healthier crops, reduce losses, improve productivity, and earn more income. It also helps them make smart farming decisions, save resources, and practice farming in a more sustainable way. In short, this app works like a digital farming assistant that gives the right advice at the right time, improving both the livelihood of farmers and the future of agriculture.</li>
<li>This solution helps farmers by giving them the right advice at the right time. Many small farmers face problems like not knowing which crop to grow, how much fertilizer to use, how to control pests, or how to deal with sudden weather changes. Our app solves these problems by suggesting suitable crops, detecting plant diseases from photos, giving weather updates, and guiding fertilizer use. It also works in many Indian languages and supports voice, so even farmers who cannot read easily can use it. Since it works on normal smartphones and can run offline, farmers in villages with less internet can also benefit. By using this app, farmers can grow better crops, reduce losses, and earn more income.</li>
<li>My solution is special because it uses AI, weather updates, and voice support all in one app. Unlike other apps that give general advice, this one gives personal advice based on the farmer’s soil, crop, and location. Farmers can take a photo of their crop, and the app will tell if there is a pest or disease and how to fix it. It also works offline in villages with less internet and supports many Indian languages with voice, so even farmers who cannot read well can use it. This makes the solution new, different, and very useful for small farmers.</li></ul>

## Technical Approach
<h3>TECHNICAL APPROACH</h3>
<ul><li>The Smart Crop Advisory App will be developed using a combination of modern technologies to make it efficient, reliable, and farmer-friendly. The mobile app frontend can be built using Java/Kotlin for Android native development or Flutter (Dart) for a cross-platform solution, while the backend will use Python with frameworks like Flask/FastAPI or Node.js (Express.js) to handle requests and connect with the AI models. For pest and disease detection, machine learning libraries such as TensorFlow or PyTorch along with OpenCV will be used to process and analyze crop images. The app will store data locally in SQLite for offline use and connect to PostgreSQL/MySQL databases on the server for central storage when the internet is available. Real-time weather updates and alerts will be integrated through APIs like OpenWeatherMap or IMD services, and multi-language voice support will be enabled using Google Cloud Text-to-Speech/Speech-to-Text or open-source tools like Mozilla DeepSpeech. The backend and AI models will be deployed on cloud platforms such as AWS, Google Cloud, or Microsoft Azure, with GPU support for training and running AI efficiently. For end-users, the app will work smoothly on basic Android smartphones with a camera, while developers will use tools like Git/GitHub for version control and Figma/Canva for UI/UX design. Together, these technologies ensure that the app is lightweight, accessible, scalable, and capable of working even in rural areas with limited internet.</li>
<li><img width="768" height="316" alt="smart_crop_flowchart" src="https://github.com/user-attachments/assets/8ba7f2b9-333b-460e-a346-4e59fd1db623" />
  <img width="1024" height="1536" alt="ChatGPT Image Sep 24, 2025, 01_35_45 PM" src="https://github.com/user-attachments/assets/7f6f4807-e57f-43b5-a0b5-cc7db1cf89c0" />

</b></li></ul>

## Feasibility and Viability
<h3>FEASIBILITY & VIABILITY</h3>
<ul><li>The Smart Crop Advisory App is possible to make and use because all the needed technologies like mobile apps, AI for crop image checking, weather updates, and offline storage already exist and can run on normal smartphones that most farmers have. The cost to build the app may be a little high at the start, but farmers will save money in the long run by using the right crops, less fertilizer, and by avoiding big losses from pests or weather, so it is worth it. The app is simple to use with pictures, local languages, and voice help, so even farmers who cannot read much can use it easily. It also solves real problems farmers face, like which crop to grow, how to control pests, and how to plan for the weather, so farmers will accept it and benefit from it. Overall, this app is practical, affordable, farmer-friendly, and can make farming easier, more profitable, and more sustainable.</li>
<li>The Smart Crop Advisory App, while very useful, may face some challenges and risks. Farmers in rural areas may not have good internet access, and although the app can work offline, some features like weather updates will need connectivity. Many farmers may also find it difficult to trust new technology in the beginning, so training and awareness will be important. The AI system may not always detect pests and diseases correctly, especially if the photo quality is poor, which could cause farmers to lose trust if wrong advice is given. Another risk is the cost of maintaining and updating the app, including keeping the database of crops, fertilizers, and diseases accurate and up to date. Language and dialect differences across regions can also be a challenge. Finally, if farmers depend only on the app and ignore local expert advice, it may create problems in certain cases.</li>
<li>To overcome these challenges, the app can include an offline mode where key features like crop suggestions, fertilizer guidance, and disease detection still work without the internet, while weather updates can be stored and refreshed whenever connectivity is available. To build trust, farmers can be given training through workshops, Krishi Vigyan Kendras (KVKs), and farmer groups, showing real success stories of how the app helps. The AI system can be improved by collecting more crop images from local farms to make detection more accurate. Regular updates can be managed by partnering with government agencies and agricultural universities to keep data reliable and low-cost. For language challenges, the app should support multiple Indian languages and add voice features for ease of use. Finally, the app should be promoted as a digital assistant to support farmers, not replace local experts, so that farmers continue to combine both sources of knowledge for the best results.</li></ul>

## Impact and Benefits
<h3>IMPACTS & BENEFITS</h3>
<ul><li>The Smart Crop Advisory App can have a very positive impact on small and marginal farmers by giving them the right advice at the right time, which can improve their crop yield, reduce losses, and lower farming costs. By helping farmers choose the best crops for their soil and season, use the correct amount of fertilizer, and quickly detect pests and diseases, the app can make farming more efficient and profitable. Weather alerts will protect farmers from sudden climate risks, and the use of local languages and voice support will make it accessible even for those who cannot read well. Since it also works offline, farmers in villages with poor internet will not be left out. Overall, the app can improve farmers’ confidence, increase their income, make farming more sustainable, and contribute to better livelihoods in rural areas.</li>
<li> SOCIAL BENIFITS: 
The app supports farmers in their local languages and with voice features, making it easy even for those who cannot read. It reduces farmers’ stress by giving quick solutions to problems and helps build confidence in modern farming methods. It also promotes equality by reaching small and marginal farmers who often have less access to expert advice.

ECONOMIC BENEFITS: 
By suggesting the best crops, guiding the correct amount of fertilizer, and detecting pests and diseases early, the app helps farmers reduce losses and increase crop yield. This directly increases their income and reduces unnecessary spending on inputs. Access to weather alerts also saves farmers from sudden losses due to climate events.

ENVIRONMENTAL BENEFITS: 
The app promotes sustainable farming by guiding farmers to use only the required amount of fertilizer, which prevents soil damage and reduces water pollution. Early detection of pests reduces the need for excess pesticide use, protecting the environment and human health. Choosing the right crops for the soil and season also supports long-term soil fertility and reduces wastage of natural resources.</li></ul>

## Research and References
<h3>RESEARCH AND REFERENCES</h3>
<ul><li>New Plant Diseases Dataset (Kaggle):
This is a public dataset hosted on Kaggle which contains images of plant leaves exhibiting various diseases, intended for use in training, validating, and benchmarking machine learning models for plant disease detection. The dataset includes multiple classes corresponding to different disease types (and healthy leaves), and is accompanied by labels and metadata to facilitate supervised learning in agricultural computer vision applications.
  https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
  
Paddy Doctor:
A Visual Image Dataset for Automated Paddy Disease Classification and Benchmarking (arXiv, 2205.11108). This paper introduces Paddy Doctor, a curated visual dataset consisting of 16,225 annotated images of paddy (rice) leaves across 13 classes (12 disease types plus healthy), to address the scarcity of high-quality public datasets for paddy disease detection. The authors benchmark performance using a convolutional neural network and several transfer learning models (VGG16, MobileNet, Xception, ResNet34), reporting strong results (e.g. ResNet34 achieving 97.50% F1-score), and they publicly release the data and code to foster further research.
  https://arxiv.org/abs/2205.11108
  
Vosk-API (GitHub repository by alphacep):
Vosk is an open-source, offline-capable speech recognition toolkit that supports multiple platforms (Android, iOS, Raspberry Pi, servers) and languages (Python, Java, C#, Node.js, etc.). Its models are compact (≈50 MB), with streaming, low-latency transcription, dynamic vocabulary reconfiguration, and speaker identification capabilities, making it suitable for embedding in resource-constrained environments and real-time applications like virtual assistants, transcription tools, and smart devices.
  https://github.com/alphacep/vosk-api</li></ul>
