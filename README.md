# WhatsApp Chatbot with llama-2-7b on Google Colab

This project demonstrates the setup of a WhatsApp chatbot powered by the llama-2-7b model, running on a Google Colab instance. The chatbot is integrated with Twilio for messaging capabilities.

## Steps to run

### Step 1: Run llama-2-7b API in Google Colab
Run the llama-2-7b API file in Google Colab to set up the llama-2-7b model. This will generate a ngrok endpoint.

### Step 2: Use ngrok Endpoint in Twilio Chatbot File
In the Twilio chatbot file, use the ngrok endpoint generated in Step 1 in the call_llama_api function. This function will be responsible for connecting to the llama-2-7b model.

### Step 3: Configure Twilio Sandbox Settings
Run the twilio chatbot file and get its ngrok endpoint. Use this endpoint in the twilio sandbox settings to make the connection

![image](https://github.com/tejaspthorat/Whatsapp-chatbot/assets/97504422/98aff988-b682-4bf5-87af-c9fb4d55e493)



### Example output:

![Screenshot - 1](https://github.com/tejaspthorat/Whatsapp-chatbot/assets/97504422/97899d91-5314-4ba6-bf52-50e7985e5d5f)


![screenshot - 2](https://github.com/tejaspthorat/Whatsapp-chatbot/assets/97504422/96e516a4-5d28-4646-b1bc-a2d601be49ed)
