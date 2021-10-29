# autoTranslateInbox

Auto translate all incoming customer messages to the desired language of your agents within Inbox.

Sample screenshots below :

* Inbox
https://storage.googleapis.com/mbse_samples/Screen%20Shot%202021-10-22%20at%205.32.57%20pm.png

* Flow Builder
https://storage.googleapis.com/mbse_samples/Screen%20Shot%202021-10-29%20at%2010.24.40%20pm.png


Steps :

1 : Sign up with MessageBird : https://dashboard.messagebird.com/en/sign-up

2 : Setup a channel - https://dashboard.messagebird.com/en/channels

3 : Get started on Inbox : https://inbox.messagebird.com/

4 : Open Flow Builder - https://dashboard.messagebird.com/en/flow-builder

5 : Import, add API key, choose language in Translate step and publish the predefined webhook flow into FlowBuilder - https://github.com/superbird2019/autoTranslateInbox/blob/main/Conversation%20call%20back%20and%20translation%20flow.json

6 : Setup channel callback URL - https://github.com/superbird2019/autoTranslateInbox/blob/main/Channel%20callback%20URLs.postman_collection.json

Test by sending in a message on the newly setup channel which will appear as a ticket in Inbox. If done correctly, all incoming messages will be automatically translated and displayed as a note within the conversation.
