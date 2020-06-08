# Intelligent-Customer-Help-Desk-with-Smart-Document-Understanding


Intelligent Customer Help Desk with Smart Document Understanding. 
This is repository built with the help of Watson Assistant, Discovery, Cloud Function and Node Red app of IBM Cloud. It was made for my one month AI internship at Smartbridge.

#Project Description : The typical customer care chatbot can answer simple questions, such as store location and open-hours, directions etc. When a question falls outside of the scope of the pre-determined question set, the assistant usually tells the customer that the question is not valid or offers to speak to a real person.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers problems. To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries. Scope of Work Create a customer care dialog skill in Watson Assistant Use Smart Document Understanding to build an enhanced Watson Discovery collection Create an IBM Cloud Functions web action that allows Watson Assistant to post queries to Watson Discovery Build a web application with integration to all these services & deploy the same on IBM Cloud Platform

I have used the ecobee3_userguide.

Node-Red Dashboard link after deploying : https://node-red-fsndr.mybluemix.net/ui/#!/0?socketid=YdMwiqFGLTTV3gCSAAAA

Youtube video link is : https://www.youtube.com/watch?v=dPBtjVAFEaE
