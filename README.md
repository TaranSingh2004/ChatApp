# ChatApp


websockets- enable real time connections
stomp- organize and route message within that connection and it makes it easier for creating any msg destinations chat groups
sock- when the client doesnt have thing to use this app





Summary of Flow:
Page loads → connect is called → WebSocket connection is established.
User enters their name and a message → clicks Send.
sendMessage creates a message object → sends it to /app/sendMessage.
Server broadcasts the message to /topic/messages.
showMessage displays the message in the chat window.
