# hackathon_gmu
gmu_website_students
Introduction
At George Mason University (GMU), every student's academic journey should be fulfilling and smooth. However, many international students find the course selection and academic planning process to be challenging.

The Inspiration
Our team's inspiration stemmed from personal experience. When we first applied to GMU, we encountered various hurdles, particularly in understanding course structures, timely scheduling, and navigating the extensive catalog. As international students, these challenges were amplified due to our unfamiliarity with the American educational system and GMU's specific processes.

The Problem
Navigating GMU's vast course offerings, understanding prerequisites, and planning an academic path is no small feat. For international students, there's an added layer of complexity: cultural nuances, language barriers, and often, a lack of a support system. This can make their transition and subsequent semesters daunting. To address this pressing need, we initiated the Patriot help services project. Our primary goal was to create a platform tailored specifically for GMU's international student body. At the heart of this platform lies our AI-powered Class Selection Predictor. This tool uses machine learning to analyze historical class data, popularity trends, and offers personalized course recommendations.

What it does
AI-Powered Recommendations: Our tool doesn't just list popular courses. It understands an individual's academic trajectory and offers suggestions aligned with their goals.
Cultural Nuances: Recognizing the diverse backgrounds of international students, our platform includes resources that explain cultural and academic nuances, bridging the knowledge gap.
Language Support: We understand that English might not be the first language for many international students. Hence, our platform offers multi-language support in the future, ensuring comprehensibility for all.
How we built it
Our development journey for Patriot Help Services was multi-faceted, harnessing various technologies to deliver a robust and user-friendly platform:

Machine Learning with SageMaker Canvas:

We leveraged the power of AWS SageMaker Canvas to develop our prediction models. After importing our data via Amazon S3, we meticulously crafted datasets, honing in on specific targets. This allowed our platform to predict and recommend the best classes and clubs tailored for each student's needs.
Frontend Development:

The website's user interface was designed using HTML, CSS, and JavaScript, ensuring a seamless and intuitive user experience. We prioritized responsiveness, ensuring that our platform is accessible across a range of devices.
Backend & Database:

Our backend was developed using Express and Node.js, facilitating a stable and efficient connection to our local database. This allowed us to store and retrieve essential data dynamically.
To manage and organize data sheets effectively, we incorporated Python scripts, ensuring efficient data processing and integration.
AI Assistance with Amazon Lex:

Recognizing the need for instant support, we integrated an AI chatbot using Amazon Lex. This bot serves as a virtual assistant, addressing common queries and guiding students through the platform, enhancing their overall experience.
Potential Challenges in the "Patriot Help Services" Project
1. Data Quality & Quantity
Challenge: Insufficient or poor-quality data can hinder the effectiveness of machine learning predictions.
Implication: Inaccurate course or club recommendations may be provided to students.
2. Machine Learning Complexity
Challenge: Fine-tuning the AWS SageMaker Canvas model for optimal predictions.
Implication: The model might overfit or underfit without proper tuning, affecting prediction quality.
3. Integration Issues
Challenge: Seamless integration of diverse technologies (Python, Node.js, Amazon Lex) into a cohesive platform.
Implication: Integration issues can result in system lags, crashes, or inefficient operations.
4. Chatbot Limitations
Challenge: Ensuring Amazon Lex understands and processes a wide variety of user queries accurately.
Implication: Inaccurate chatbot responses can lead to user frustration.
5. Frontend Compatibility
Challenge: Ensuring the website displays and functions properly across various devices and browsers.
Implication: A section of users might experience a suboptimal interface.
Accomplishments that we're proud of and what we learned on our why there
1. Machine Learning & Data Analytics
Mastering AWS SageMaker Canvas for predictive modeling.
Proficiency in data preprocessing and analysis using Amazon S3.
Crafting and interpreting datasets for precise prediction outcomes.
2. Cloud Computing and Storage
Leveraging Amazon S3 for cloud data solutions.
Understanding and utilizing AWS services for scalable applications.
3. AI & Chatbot Integration
Implementing Amazon Lex for chatbot functionalities.
Basics of natural language processing (NLP) for improved user-AI interactions.
4. Problem-solving & Critical Thinking
Identifying real-world challenges and devising actionable solutions.
Testing and refining based on feedback and emerging challenges.
5. Continuous Learning & Adaptation
Staying updated with tech advancements and integrating new tools.
Adapting platform features based on evolving user and tech trends.
6. AI Efficiency:
Our Class Selection Predictor has shown an accuracy rate of about 50% in trials,which is not accurate but for our first try while using this AWS service validating our tech choices, it was a good run

7. great teamwork
This is the fist time we have ever been to this kind of an event. We are proud to say that we have done a great job in working like a team and contributed by spliting our work and hosting a service in less than 36hrs.

What's next for Patriot Help Services
-However, with additional time and direct access to GMU's class database, our model's predictive capabilities could be further enhanced. -We also plan to add multiple languages to our AI bot and enhance it with personalized natural language training -With additional time, we plan to make the website look cosmetically better. We also plan to make the website available to the people with special abilities. -There are many more things that we plan to do. This improvement would undoubtedly lead to an even more refined and superior user experience -Given that SM canvas is a no-code platform, we could not call the backend API and host it on our website. If given enough time frame, we could have implemented a real-time data presentation.

Why PHS Matters
We believe in the potential of every international student at GMU. Our platform aims to level the playing field, ensuring that everyone, irrespective of their background, has access to the resources they need for a successful academic journey.

Conclusion & Call to Action
Our personal experiences at GMU fueled the creation of patriot help services. We envision a future where every international student can navigate their academic life at GMU with confidence and clarity. Join us in this mission. Explore patriot help tech and redefine your GMU experience!
