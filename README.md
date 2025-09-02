# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: 01.09.25                                                                           
### REGISTER NUMBER : 212223230045
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm and Prompting Techniques for AI Chatbot Development
## Direct Instruction Prompts
Objective: Guide the chatbot to respond concisely to customer inquiries.
Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"

The objective is to guide the chatbot to respond concisely and clearly to customer inquiries. For instance, when a customer asks about order status, the chatbot is prompted to reply:
"Your order is currently being processed and will be delivered by [date]."

This method helps provide consistent and straightforward answers for routine questions, ensuring efficient handling of common queries.

## Contextual Prompting
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.
Prompt Pattern:
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"

This technique incorporates specific context from the user's previous interactions to provide more detailed, personalized responses. For example:
"If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"

Contextual prompting enhances the chatbot's responsiveness by recognizing prior user concerns.

## Persona-Based Prompting
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.
Prompt Pattern:
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"

In this approach, the chatbot is designed to adopt a particular persona to make interactions more engaging and approachable. For example:
"Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"

This makes communication warmer, builds user trust, and creates a natural conversational flow.

## Few-Shot Prompting
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
Prompt Pattern:
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"

Few-shot prompting teaches the AI how to respond by providing a few examples to learn from, enabling it to generalize for similar situations. For instance:
"Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"

This pattern helps the chatbot infer how to address new but related queries effectively.

## Chain of Thought Prompting
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.
Prompt Pattern:
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"

This method uses step-by-step reasoning to solve more complex or technical issues. The prompt guides the chatbot through a logical sequence, for example:
*"When a customer reports their laptop overheating, guide them through these steps:

Ask if they are using the laptop on a soft surface.

Suggest moving the laptop to a flat, hard surface for better airflow.

Ask if they’ve cleaned the vents recently.

Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"*

This approach improves problem-solving clarity and thoroughness.

## Instruction with Constraints
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
Prompt Pattern:
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"

This type of prompting instructs the chatbot to adhere to specific constraints such as response length or tone. For example:
"Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"

Constraints ensure the chatbot's replies are concise and user-friendly, avoiding confusion.

## Reflective Prompting
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
Prompt Pattern:
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"

Reflective prompting ensures the chatbot repeats or reflects the user's question before answering to reduce misunderstandings. For example:
"When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"

This technique clarifies user intent and improves communication accuracy.

## Table result:
| **Prompting Technique**          | **Objective**                                                         | **Prompt Pattern Example**                                                                                                                                       | **Key Benefit**                                                      |
| -------------------------------- | --------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| **Direct Instruction**           | Guide chatbot to respond concisely to routine queries.                | *"When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by \[date].'"*                  | Provides consistent, straightforward answers quickly.                |
| **Contextual Prompting**         | Use previous interactions to personalize responses.                   | *"If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check...'"*  | Enhances personalization and responsiveness.                         |
| **Persona-Based Prompting**      | Make chatbot adopt a specific persona to improve engagement.          | *"Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions...'"*  | Builds trust and creates a warmer, engaging experience.              |
| **Few-Shot Prompting**           | Teach chatbot how to generalize answers using a few examples.         | *"'My phone isn't charging.' → 'Try a different cable.' 'Screen flickering.' → 'Restart device.' Now, respond to: 'My app keeps crashing.'"*                     | Helps chatbot handle similar but new questions effectively.          |
| **Chain of Thought Prompting**   | Use step-by-step reasoning for complex issues.                        | *"Laptop overheating: 1. Ask if used on soft surface. 2. Suggest hard surface. 3. Ask about vents. 4. Recommend restart. Now, solve: 'My laptop fan is noisy.'"* | Improves logical clarity and structured troubleshooting.             |
| **Instruction with Constraints** | Ensure replies follow length, tone, or style constraints.             | *"Respond to order inquiries in no more than 50 words. For example: 'Your order is on the way and should arrive by \[date]. Feel free to reach out if needed.'"* | Keeps responses concise, user-friendly, and on-brand.                |
| **Reflective Prompting**         | Reflect the user’s query before answering to avoid misunderstandings. | *"If asked 'How can I reset my password?' reply: 'You're asking how to reset your password, correct? Here’s how you can do it.'"*                                | Reduces misunderstandings and confirms user intent before answering. |



# Result: 
Thus the Prompts were exected succcessfully .

