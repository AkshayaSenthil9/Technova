# CUSTOMER SUPPORT AUTOMATION – PROJECT REPORT

## 1. Student and Project Details
**Name:** Akshaya  
**College:** Sir Isaac Newton College of Engineering and Technology  
**Location:** Pappakovil – Nagapattinam  
**Activity:** Build Customer Support Automations  
**Selected scenario:** E-commerce order tracking and order-related support  
**Project name:** QuickCart Customer Support

## 2. Objective
To create a simple, simulated customer-support website that recognizes common e-commerce order questions, displays polite automated guidance, and directs unresolved issues to human support.

## 3. Customer Problem and Requirement
Customers may be unsure where an order is, why delivery is late, how to return an item, or how to check a refund. They need quick, simple instructions and a clear route to a human support representative when the automated answer is insufficient.

## 4. Common Customer Queries
1. Where is my order?
2. My delivery is delayed. What should I do?
3. How can I return a product?
4. When will I receive my refund?
5. I received the wrong product. How can I report it?
6. How can I contact human customer support?

## 5. Customer Support Workflow
Customer opens support interface  
↓  
Selects a category or enters a question  
↓  
System checks keywords and identifies the query category  
↓  
For order tracking, system requests a demo order ID  
↓  
System displays a matching response and next action  
↓  
If the query is unknown, order ID is invalid, or the issue needs review, system directs the customer to human support  
↓  
Customer receives a polite closing message

## 6. Automated Responses
**1. Order status – shipped**  
Hello! Thanks for checking in. Demo order QC123 has been shipped and is in transit. Please use the tracking link in your order confirmation for live carrier updates. If tracking has not updated for 48 hours, contact our support team. Thank you for contacting QuickCart Support!

**2. Order status – delayed**  
Hello! Sorry your delivery is taking longer than expected. Demo order QC456 is marked delayed. Please check the latest estimate in your order confirmation. If it passes the revised date, contact human support with your order ID. Thank you for contacting QuickCart Support!

**3. Delivery delay**  
Sorry your delivery is delayed. Check the revised delivery estimate in your order confirmation. If the date has passed, contact human support and share only your order ID. Thank you for contacting QuickCart Support!

**4. Return request**  
You can request a return from Orders → select the item → Return item, then follow the instructions. Keep the product and packaging ready if required. If the return option is missing, contact human support. Thank you for contacting QuickCart Support!

**5. Refund status**  
Refund timing depends on the payment method and bank. Check Orders → Refund details for the current status. If the expected period has passed, contact human support with your order ID. Never share your OTP, PIN, or full card details. Thank you for contacting QuickCart Support!

**6. Wrong item**  
Sorry you received an incorrect item. Please open Orders → select the order → Report an issue, and choose “Wrong item.” Keep the item and packaging until support responds. Thank you for contacting QuickCart Support!

**7. Human support / unrecognized query**  
I’m sorry, I couldn’t match that question to a support topic. Please choose one of the categories or contact human support at support@example.com. A support person can review your issue. Do not send passwords, OTPs, or full payment details. Thank you for contacting QuickCart Support!

## 7. Automation Implementation
The project uses HTML to create the interface, CSS for layout and responsive design, and JavaScript to identify query keywords and display a relevant response. The system supports category buttons, a query box, demo order-ID handling, shipped/delayed sample statuses, invalid-ID handling, and human-support escalation. It is a simulation and does not access real orders.

## 8. Communication and UX Practices
1. Simple and familiar language.
2. Polite greeting and closing.
3. Short, readable responses.
4. Clear next steps and menu paths.
5. Consistent response style.
6. Human-support option for unresolved issues.
7. Privacy warning against sharing OTPs, passwords, PINs, or card details.
8. Responsive layout for mobile and desktop.
9. Error handling for blank queries and invalid demo IDs.

## 9. AI-Assisted Improvements
AI tool used: ChatGPT. AI assistance was used to brainstorm customer queries, draft and simplify support responses, suggest workflow branches, and review possible edge cases. The responses were reviewed and customized for this simulated project. Order statuses and IDs are fictional and are clearly identified as demo data; the project does not claim to verify real orders.

## 10. Testing Results
| Test | Input / Action | Expected result | Result |
|---|---|---|---|
| 1 | Click Order status and enter QC123 | Shipped response appears | Pass |
| 2 | Ask “My delivery is delayed” | Delay guidance appears | Pass |
| 3 | Ask “How can I return a product?” | Return steps appear | Pass |
| 4 | Ask “When will I receive my refund?” | Refund guidance and privacy warning appear | Pass |
| 5 | Enter unknown ID QC999 for order tracking | Invalid ID message and support option appear | Pass |
| 6 | Submit blank query | Prompt to enter a question appears | Pass |
| 7 | Enter an unrelated query | Unrecognized-query response and human support appear | Pass |

## 11. Real-World Scenario Analysis
**Scenario:** An online customer wants to track an order.  
**Customer problem:** The customer does not know whether the parcel has shipped or is delayed.  
**Customer requirement:** A quick status explanation and next action.  
**Automation features:** Order ID input, sample status lookup, tracking guidance, delayed-order response, invalid-ID handling, and human escalation.  
**Expected output:** A clear response based on the demo ID and a next step. In a real implementation, the status lookup would need a secure, authorized connection to the store's order-management system.

## 12. Final Review and Corrections
The interface, spelling, response tone, workflow branches, empty-input handling, invalid order-ID response, and human-support fallback were reviewed. Demo information is labeled as fictional. Sensitive information is not requested. Before public use, replace the placeholder support email with an authorized address and connect to a secure order system if real order tracking is required.

## 13. Reflection
I learned how customer-support automation can answer common questions quickly and consistently. I practiced identifying customer queries and designing a workflow with clear next steps. I learned to write polite, simple responses and include human support for problems the automation cannot solve. ChatGPT helped me generate ideas and improve the wording, which I reviewed and customized. I can use these HTML, CSS, JavaScript, and workflow skills in future web development projects.

## 14. Screenshots and Submission
The ZIP includes illustrative interface preview images in the `screenshots` folder. For submission, open `index.html` in a browser and replace/add your own screenshots showing the running website (home screen, QC123 response, QC456 response, and an invalid or unrecognized query). Submit this project ZIP or host the folder using a platform approved by your instructor. Verify the final link before submitting the Google Form.
