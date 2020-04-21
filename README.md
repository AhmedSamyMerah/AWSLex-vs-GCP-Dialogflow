# Xavier Remacle & Ahmed Merah Seminar
## For access to our video tutorials, please contact us
## AWS and GCP 

# Motivation 
The cognitive computing area that we chose for this seminar is the area of Language. Specifically, the sub-area of language understanding for conversational purposes we researched on two platforms, Amazon and Google. The motivation for this research is to investigate the other platforms that offer conversational services, specifically language understanding. The knowledge we have accumulated from using the IBM platform’s Watson assistant services formed the basis of this research.

# What are we attempting to Answer
There are many conversational services for conversational virtual assistants (Bots). The question we are attempting to answer is what conversational virtual assistants are best suited to any specific use-case. Many cloud platforms offer a variety of bots, and we wanted to see what the differences were in those bot services, and how they hold up against IBM Watson as this is the foundation of our current knowledge. The two platforms we are comparing are Amazon Web Services (AWS) and Google Cloud Platform (GCP). They each have a variety of cognitive services, but the specific services we're focusing on are AWS Lex, and GCP DialogFlow. 

# Overview of the platforms and services 

## AWS
 Amazon Web Services (AWS) offers a wide variety of services. They range from Analytics all the way to Storage. They offer 25 products and 175 fully featured services. AWS is the world’s leading cloud platform and has the most functionality compared with any other cloud provider. The functionality of all of its services are ever evolving, and are constantly being updated, and expanded to fit the needs of its customer base. They offer many cognitive services like Amazon SageMaker which is used in Formula 1, and Amazon Personalize that can add a layer of recommendations into your bot. 

	Their customer base is 70% of web-traffic travels through AWS. This proves how fundamental it is to understand what AWS is and what they offer, as this is a necessary platform to understand and use. Their security is as well one of the most secure platforms out there. Their security has 230 ‘security, compliance, and governance services and features’. They also have a pipeline for experimentation as they offer free trials for all their services, and they have a contract Linux Academy for sandboxing. 

## GCP

Google Cloud Platform (GCP) is a cloud platform that offers a large plethora of services and was launched in 2008. It is a cloud computing that is part of the “Big 3” of cloud computing/providers that includes AWS and Microsoft Azure. GCP offers IaaS (Infrastructure as a Service), PaaS (Platform as a Service) and supports serverless architecture. GCP offers hundreds of various services and API’s on their platform that ranges from cloud computing, storage, networking services, data analytics, Big Data and AI and Machine learning. At the moment GCP is ranked as the third leader in cloud services after AWS and Microsoft. 


    In this seminar we will focus on the AI and Machine learning services that GCP offers. These services are related to cognitive computing as many of them emulate human behavior. Some of these services are included in the following paragraphs. One of the biggest advantages of the Google platform is that almost all services are modular and can be used together towards a common goal.


# Capabilities

## AWS Lex
The AWS Lex service has custom and prebuilt intents, and matching entities for such things like hello messages, and Language preferences. Some of the problems we were attempting to run into were for ambiguity and uncertainty. multiple interpretations of a simple meaning. The bot was able to understand but required a lot more training utterances for the specific intent to be fulfilled. The second is that natural language is ambiguous at its core and its interpretations are always uncertain, so we ‘attacked’ the bot with different ways of saying the same statement, e.g. ‘I want a pizza’ and ‘Can I have a cheese pie’. Without a clear synonym definition, the bot would be lost. AWS was able to overcome these problems.

## GCP Dialog Flow
Dialogflow by Google was a wonderful platform to work with. It covered the main cognitive concepts that we covered in our learning during the course through the IBM platform with much more features and ease of use. There is options to define intents with various training phrases that can be used in different languages to derive better utterances depending on the language which integrates really well with the translate service. From these intents various multiple responses can be derived and created. Entities are also available to use but not necessary as specified by Google as they use state of the art machine learning for training the model on the intent itself.

The service also offers the possibility of integrating context variable directly into intents by using training phrases and selecting what would be considered a context variable. The training on the platform is very fast and accurate as you can test instantly without having to wait for the assistant to train.

# Comparison
Working with AWS Lex and GCP Dialogflow was a wonderful and eye-opening experience. Comparing the platforms, AWS and GCP offer a large suite of varied services that r## Comange from storage to machine learning, and other services for various domains and purposes. We found that AWS is cheaper and offers more integrated services. GCP has a better user experience and is more centralized to integrate services.

AWS was a difficult process to initialize as this was probably built for advanced domain experts and advanced super users. It took a bit of googling to just create an account. Stopping the billing and setting alerts/stoppages was cumbersome. I felt as if I was back in first year attempting to just install UWP packages. Moving to the AWS Lex service, it was simple enough to use the pre-built solutions. The prebuilt solution was straight-forward and easy to play with, as the playground was quite verbosely defined in the tutorial. 

Building the pizza ordering Virtual Assistant (Bot) was straight-forward as it followed the same process as IBM Watson Virtual Conversational Assistant. It was an intent focused service, as all intents have entities and slots integrated into its bot building. I found that you could integrate slots/entities into intent examples, so that the machine learning services (AWS SageMaker) could then dynamically build more examples. I had to define a multitude of examples just to come up with a usable intent. You could also integrate with an intent multiple type of responses, and as well you can hook up AWS Lex to AWS Lambda functions (Cloud Functions). Lastly integrating into outside services like Slack or Facebook Messenger was as simple a copy-pasting the auth values from slack/FBMessenger into a set of forms and pressing authorize. 

GCP was a very easy process to initialize as the Google suite is very integrated and most of us have a Google account through Gmail. From there all that was left to do was pick a service and start a project. There were prebuilt solutions that were very easy to integrate with any other services. One example of a prebuilt service were “agents” which were prebuilt templates with content such as currency conversion or booking systems. 

Building a Shawarma shop virtual assistant was very straightforward and simple. There were the same concepts we covered of intents and entities. The platform just like AWS Lex was intent focused but with more training and direct integration that allowed a hands-off approach to bot development. GCP offered pre-built features that allowed the bot to be more comprehensive such as a currency converter plugin that would build dynamic responses and examples directly due to the machine learning techniques that GCP offers with Dialogflow. Dialogflow was easy to hook up to translation services, other Google services such as translation and other services such as Slack, Facebook messenger and Google Home just by copying authentication keys.

Comparing the Services, based critiquing on the difference, we found overall that GCP Dialogflow more straight-forward and was able to create a bot faster. AWS was a rigorous process, but it was rewarding in knowing that integrating into every service AWS offered was allowed. 

Dialogflow was a simple UI that was easy to use and intuitive. By taking a hands-off approach where the training and machine learning methods do the heavy lifting and derive responses on their own without the necessary use of entities as the training takes care of synonym mapping. Whereas with AWS the UI was complex but advanced in the features it offered such as web-hook and cloud function integration with every intent. The entities were derived values based on slots, meaning you could have slots that were tightly coupled with entities in the same field.

In conclusion our results were very satisfactory as we both learned a lot about the different platforms and what goes on into building language understanding systems in different platforms and their service integrations. Overall, we would recommend GCP Dialogflow for building conversational virtual assistants as they suite that can be integrated with it is larger in the grand scheme of things with services like translation prebuilt agents that allow for richer interactions.

# Tutorials

## AWS Lex

To create a bot, you must navigate to console.aws.amazon.com/Lex.

> Select ‘Create’ from the top menu

> Next, select ‘Custom Bot’  
> Enter you bots name  
> Select a voice  
> Set timeout value  
> And if your app will be used by those under 14 years old, select yes in COPPA, > else select NO
> Steps are also given in the figure below  
> Next select ‘Create Intent’  
> Enter the intents name  
> Then add the intent    
 
> Next select ‘+’ create slot  
> Enter the slot name  
> Enter the slot description  
> Enter slot resolution  
> And enter the values and synonyms of your slot  

> If you have a lambda function   

> Lastly let’s do the error handling  
> Select error handling  
> Enter any clarification prompts  
> Select the number of repeats  
> Then enter your hang-up phrases  

## GCP Dialog Flow

> Go to  https://cloud.google.com/  
> Click products and click “See all products”  
> Scroll to the “AI and Machine Learning” section and click “Dialogflow”  
> Click “Go to console”  
> Click “Sign-in with Google”  
> Create a an intent  
> Add training phrases  
> Highlight a part of the intent to create a context variable  
> Create responses with the context variable by using $ if wanted  
> Test on the right panel  
> Click small talk to create a prebuilt agent  
> Cover basic responses with your choosing  
> Click integrations and enable slack  
> Click test in slack 
> Allow the app to be integrated  
> Open slack and test it in slack  
