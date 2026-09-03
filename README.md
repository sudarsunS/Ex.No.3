# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques for the the following Prompt Engineering types with examples - Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting - Preceding Question Prompting.









### Aim: 



To write prompts for the following prompt engineering types and evaluate them:

Straightforward Prompts

Tabular Format Prompting

Preceding Question Prompting

Missing Word Prompting



# SCENARIO:


A customer buys a smartwatch from an online store and later contacts the chatbot because the watch is not syncing with their phone and the battery is draining very fast. They also want to check the status of another order they placed the same day and ask whether they can return or replace the smartwatch if the issue is not fixed. The chatbot should guide them step by step in a friendly and clear way. It may first suggest basic troubleshooting like checking Bluetooth, restarting the devices, and updating the app. Then it can help the customer track the order using the order number. Finally, if the problem continues, it should explain the return or replacement process. This makes the chatbot useful for technical support, order tracking, and customer service all in one conversation.





# PROCEDURE:







# 1. Straightforward Prompt:



**Prompt**




   You are a customer support chatbot for an online electronics store. Help customers with smartwatch troubleshooting, order tracking, and return policy questions in a polite, clear, and friendly tone.



   
**Generated response**
  



Sure, I can help you with that. Please share your order number so I can check the delivery status. If your smartwatch is not syncing, make sure Bluetooth is turned on and restart both your phone and the watch. You should also check whether the smartwatch app is updated to the latest version. If the battery is draining fast, try reducing screen brightness and closing unused apps. If the issue is still not fixed, I can guide you through the return or replacement process. Let me know if you need help with anything else.   


   
**Evaluation**



The straightforward prompt is clear and effective because it tells the chatbot exactly what role to play and what topics to handle. The generated response is polite, relevant, and easy to understand, which makes it suitable for customer support. It gives useful guidance on order tracking, smartwatch troubleshooting, and return help in a simple way. The response also follows a logical flow, so the customer can quickly understand what to do next. However, it could be improved by asking for specific details such as the order number or device model. Overall, this prompt and response work well for a friendly and practical chatbot interaction.






# 2.Tabular Format Prompting:



**Prompt**






Explain how to fix a smartwatch that is not syncing with a phone in a table with columns: Step, Action, and Purpose.






**Generated Response**  



















| Step | Action | Purpose |
|---|---|---|
| 1 | Turn on Bluetooth | Allow the devices to connect |
| 2 | Restart both the phone and smartwatch | Clear temporary connection errors |
| 3 | Check the app permissions | Make sure the app can access Bluetooth |
| 4 | Update the smartwatch app | Improve compatibility and performance |
| 5 | Re-pair the devices | Create a fresh connection |
| 6 | Contact support if the issue continues | Get further assistance |



























**Evaluation**




The tabular format prompt is effective because it organizes the troubleshooting steps in a clear and easy-to-read structure. The generated response is relevant, complete, and practical, as it provides step-by-step actions with their purposes. This format is especially useful for technical support because customers can quickly scan the table and understand what to do next. It also improves readability compared to a long paragraph. However, the response could be even better if it included more specific details, such as device model or app name. Overall, this prompting technique works well for presenting information in a structured and user-friendly way.





# 3. Preceding Question Prompting:





**Prompt**  




Earlier, the customer asked about a delayed smartwatch order. Now answer this follow-up question: ‘What should I do if my package still does not arrive tomorrow?







**Generated Response**  





If your package still does not arrive tomorrow, first check the tracking status again for any new updates. If there is still no movement, contact the delivery partner or customer support. Share your order number and tracking ID so they can investigate the issue. You may also ask for a replacement or refund if the delay continues.



**Evaluation**






The preceding question prompting technique is effective because it uses the earlier context to generate a relevant follow-up response. The generated answer directly addresses the delayed order and gives clear next steps such as checking tracking updates, contacting support, and requesting a replacement or refund if needed. This makes the chatbot feel more natural and conversational, like a real support agent. It also helps maintain continuity in multi-turn interactions. However, the response could be improved by asking the customer for their order number before giving support instructions. Overall, this technique works well for handling follow-up questions in a smooth and context-aware way.




# 4. Missing Word Prompting:




**Prompt** 





If the smartwatch battery drains too fast, the customer should lower screen brightness and close unused ______.





**Generated Response** 





If the smartwatch battery drains too fast, the customer should lower screen brightness and close unused apps.






**Evaluation**  





The missing word prompting technique is useful because it guides the model to complete a specific part of the sentence. The generated response is correct and contextually appropriate, as “apps” fits naturally in the blank. This technique works well when the goal is to get a focused and controlled answer from the chatbot. It also helps reduce unnecessary extra information and keeps the response concise. However, it is best used for simple completions rather than complex explanations. Overall, this technique is effective for targeted and precise prompt design.





  

# COMPARISON














| Prompting Technique          | How it Works                                               | Best Use                                          | Advantage                              | Limitation                                         |
| ---------------------------- | ---------------------------------------------------------- | ------------------------------------------------- | -------------------------------------- | -------------------------------------------------- |
| Straightforward Prompting    | Gives a direct instruction to the AI.                      | General chatbot tasks and simple responses.       | Easy to write and understand.          | May give less structured answers.                  |
| Tabular Format Prompting     | Asks the AI to present information in a table.             | Troubleshooting, steps, and comparisons.          | Clear and organized output.            | Not ideal for long explanations.                   |
| Preceding Question Prompting | Uses the previous question or context for the next answer. | Multi-turn conversations and follow-up questions. | Makes the chatbot context-aware.       | Depends on earlier conversation context.           |
| Missing Word Prompting       | Leaves a blank for the AI to complete.                     | Focused completions and controlled outputs.       | Produces specific and concise answers. | Limited for complex reasoning or detailed replies. |












# CONCLUSION





 
Advanced prompt engineering techniques make chatbot responses more accurate, structured, and user-friendly. In this customer support scenario, straightforward prompting helped define the chatbot’s role clearly, tabular prompting improved organization, preceding question prompting supported context-aware replies, and missing word prompting produced focused completions. Together, these techniques show how prompt design can improve the quality of AI interactions.








# RESULT






The chatbot was able to handle customer queries about troubleshooting, order tracking, and returns in a clear and conversational manner. Each prompting technique produced a different style of response, demonstrating its usefulness for specific tasks. Overall, the experiment showed that choosing the right prompting technique can significantly improve chatbot performance and user experience.



Thus, the various types of Prompts are executed successfully with generated the report.
