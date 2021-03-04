# limitless-blueprint-email
This Genesys Blueprint provides instructions for integrating Limitless into Genesys Cloud. The integration connects a Genesys Cloud email flow through the Limitless APIs to Experts who are using the SmartCrowd platform. Questions submitted to the webform are sent to Genesys Cloud through email and then routed to Limitless experts who can answer the questions and classify the questions for further processing by the Email flow.

GigCX is available on multiple digital channels. This blueprint it starts from a webform on a website. Customers ask a question (along with their email to receive the reply) and Genesys Cloud routes the question to a Gig Expert on the Limitless SmartCrowd platform to answer the question.

This question is presented to a collection of Gig Experts. Experts are notified that questions are available via alerts and login to the Limitless SmartCrowd desktop or mobile app. There they see all the available questions and will select a question with which they have personal experience. The Expert receives a reward (e.g. $2) for successfully resolving the case. The Expert also classifies the answer for reporting in the Genesys Cloud performance view.

The customer will receive an email with the answer and can reply to continue the conversation. This can happen as many times as needed to satisfy the customer’s question.

![](blueprint/images/Architecture.png)

