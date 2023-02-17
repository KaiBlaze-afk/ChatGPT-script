# Linux Terminal to ChatGPT

This script allows users to connect their Linux terminal to the ChatGPT chatbot. ChatGPT is a natural language processing chatbot that can understand and respond to user input.

This script is written in bash (maybe) and requires the following packages to be installed:

- jq
- lolcat

To use this script, First download required packages by the command

```sudo apt install jq lolcat -y```

Then Download this chatgpt file, Go to the ChatGPT-script folder and chmod the chatgpt file using

```chmod +x ./chatgpt```

Now edit the file using any text editing tool and replace YOUR_API_KEY with the api key you generated from openai website

Then move the file to /bin/

```mv chatgpt /bin/```

## Possible issues

Your API is invalid or The ChatGPT servers are busy so you will get jq error 

## Now you are all set to use it

Try Chatgpt with this command 

```chatgpt "Write a code to add two numbers in C" ```

If you have any questions or feedback about this script, please feel free to contact me.
