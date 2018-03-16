# Get Messages:
curl https://api.telegram.org/bot$TOKEN/getUpdates | jq

# Send Messages
curl -s -X POST https://api.telegram.org/bot$TOKEN/sendMessage -d chat_id=$CHATID -d text="Hello World"
