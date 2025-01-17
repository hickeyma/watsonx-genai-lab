# Pre-work

This section is broken up into the following steps:

1. [Sign up for IBM Cloud](#1-sign-up-for-ibm-cloud)
1. [Create a watsonx Assistant instance](#2-create-a-watsonx-assistant-instance)
1. [Connect to watsonx.ai](#3-connect-to-watsonxai)
1. [Create a sandbox project in watsonx.ai](#4-create-a-sandbox-project-in-watsonxai)

## 1. Sign up for IBM Cloud

Ensure you have an IBM Cloud ID as services and [Large Language Models (LLMs)](https://en.wikipedia.org/wiki/Large_language_model) will be deployed on the cloud.

![IBM cloud sign up](../images/ibm-cloud-sign-up.png)

**Note:** You will need to be logged into IBM Cloud before [creating a watsonx Assistant instance](#2-create-a-watsonx-assistant-instance) and [connecting to watsonx.ai](#3-connect-to-watsonxai)

## 2. Create a watsonx Assistant instance

You will use the [watsonx Assistant](https://www.ibm.com/products/watsonx-assistant?cm_sp=ibmdev-_-developer-tutorials-_-product) for creating the dialog flow and integrating with LLM to generate the travel chatbot app.

If you don't have a [watsonx Assistant instance deployed](https://cloud.ibm.com/catalog/services/watson-assistant?cm_sp=ibmdev-_-developer-_-trial) or you want to use a new instance then use any of the service plans, including *lite*.

![watsonx assistant creation](../images/watsonx-assistant-creation.png)

Once deployed, launch the Assistant so you can start using it.

![watsonx assistant launch](../images/watsonx-assistant-launch.png)

## 3. Connect to watsonx.ai

You will use [watsonx.ai](https://www.ibm.com/products/watsonx-ai) for prompt tuning and [inferencing AI models](https://research.ibm.com/blog/AI-inference-explained#), so ensure that you can log into the UI. You will also connect to the project for inferencing models in the travel chatbot app.

If you haven't already signed up, click "Start your free trial" and follow the instructions. You'll be able to use your free trial for this lab and further self-study, just be mindful of token limits as they vary depending on [pricing tier](https://www.ibm.com/products/watsonx-data/pricing).

## 4. Create a sandbox project in watsonx.ai

A *project* is where you work with data and models by using tools. When you sign up for watsonx.ai, your sandbox project is created automatically, and you can start working in it immediately.

If you don't have a project, you can manually create one too.

![watsonx.ai project creation](../images/watsonxai-create-project.png)

Once you have a project, you'll be able to open the Prompt Lab, where you can experiment with prompting different foundation models, explore sample prompts, as well as save and share your best prompts.

![watsonx.ai start prompt lab](../images/watsonxai-start-prompt-lab.png)

You are now ready to move on to the first lab where we'll use prompt engineering of foundation models to better understand what model and input prompt we need to be able to use the model in our application to return the information we require. In the subsequent lab, we will then integrate the learnings from the first lab to call the model in the dialog flow of our travel chatbot application.
