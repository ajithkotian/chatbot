# Table of Content


## Preparation 
- You will be provided with an azure account id and credentials to login.
  
## Create your own chatbot

- Open the Azure Language cognitive services page https://language.cognitive.azure.com/home 

- Select "Custom Question Answering"

![](/assets/1_Custom_qna_service.png)

- Click on "Create new project"

![](/assets/2_create_new_project.png)

- Click on "Add Source" --> "URL's"

![](/assets/3_add_source.png)

- Add a URL (Ex: https://www.ubs.com/global/en/investor-relations/contact/faq.html) and give it an "URL Name" (Ex: UBS FAQ). Click on "Add All"

![](assets/4_add_faq_url.png)

- The questions and answer from the url will be ingested and a knowledge base will be created as shown below. Once the Knowledge base is created, you can click on "Edit Knowledge base" see the questions and answers.

![](assets/5_edit_KB.png)

- Click on "Deploy Knoweldge base" in the left menu pane and then click on "Deploy" button.
 
![](assets/6_deploy_n_create_bot.png)

Once the deploy completes, you can can then click on "Create a bot" option presetend. 

- This will take you to the portal.azure.com as shown below.
![](assets/7_create_bot.png)

 Append your username to the "Bot handle". Ex: user3 in screenshot above. Refer 1 in image above

 Change the "Pricing Tier" to "Free". Refer 2 in image above.

 "App name" usualy matches the "Bot Handle". If not, update it to make it unique. Refer 3 in image above.

 "App service plan/location" should be populated by default. If not, raise it to the presenter. Refer 4 in image above.

 Click on "Create". Wait for the resource to be created.

- Click on "Goto Resource"
![](assets/8_bot_resource.png)

- Click on "Test in web chat". Wait for hte welcome message to appear. ex: "Hello and Welcome". You can now ask questions and interact with this bot.

![](assets/9_test_bot_resource.png)

- Enable "Microsoft Teams" under "Channels" . Read and Agree the terms and conditions. Select "Commercial" and click on "Apply".

![](assets/10_add_teams.png)

Click on "Close"

- Click on "Get bot Embed codes" or clikc on "Open in Teams"

![](assets/11_get_embed_codes.png)

![](assets/12_get_embed_codes_link.png)

- You need to enter the credentials passed on to you when prompted. Open in web and not the desktop Teams app. You may get error's as shown below for the first time login. Be patient and wait for about 5-10 mins. 

![](assets/12a_error.png)

![](assets/12b_user_web_app_instead.png)

- You should now see the Chatbot avaialble for you to interact. 

![](assets/13_teams_chatbot.png)
