---
title: "Understanding the Safety: Top 6 Cyber Threats Linked to AI Chatbots Like ChatGPT"
date: 2024-08-17T11:28:57.331Z
updated: 2024-08-18T11:28:57.331Z
tags:
  - chatgpt
  - open-ai
categories:
  - openAI
  - chatgpt
description: "This Article Describes Understanding the Safety: Top 6 Cyber Threats Linked to AI Chatbots Like ChatGPT"
excerpt: "This Article Describes Understanding the Safety: Top 6 Cyber Threats Linked to AI Chatbots Like ChatGPT"
thumbnail: https://thmb.techidaily.com/c45afa71b37443a1f59fe90234d68b3b0e50e4c51b39e47e7a2ccf645d397043.PNG
---

## Understanding Word and Character Quotas in AI-Powered Chatbots Like GPT-3

### Key Takeaways

* ChatGPT responses are not limitless in length, despite the initial claim. There are hidden limits determined by the token system, past conversations, and system demands.
* The token system used by ChatGPT considers both the length of queries and answers. The available token lengths vary depending on the GPT model used.
* To get longer responses from ChatGPT, you can ask it to continue, break your question into smaller sections, use the regenerate option, specify a word count limit, or start a new conversation. These techniques can help you work around the unofficial limits and receive more complete answers.

 ChatGPT is big news. But how big are the responses you get from this all-purpose chatbot?

 Establishing this is not as simple as you may think. For starters, ask ChatGPT this question, and you will be assured that there are no set limits to the length of its responses.

 However, as we uncover here, it isn't that straightforward. There are hidden limits to the length of a ChatGPT response, but there are also some nifty and simple workarounds to help you get longer answers.

## How Does ChatGPT Determine the Length of a Response?

[How ChatGPT works is complex](https://www.makeuseof.com/how-does-chatgpt-work/) , and the response length varies depending on what is being asked and the level of detail requested. As the next screenshot shows, ChatGPT claims there are no strict limits.

![Screenshot of ChatGPT Declaring No Limits](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-declaring-no-limits.jpg)

 Of course, asking ChatGPT about itself isn't a good idea since it isn't typically objective about its abilities or has limited information. So, we ran some tests to determine the length limits of ChatGPT responses. We asked the chatbot to write a 5000-word article on the history of the FIFA World Cup. ChatGPT's assessment of itself differed from the results we found.

![Asking ChatGPT to write 5000 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-5000-words-article.jpg)

 ChatGPT is a powerful tool. But maybe 5,000 words was asking a bit too much, so I asked for 2,500 words instead.

![Asking ChatGPT to write 2500 words article](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/asking-chatgpt-to-write-2500-words-article.jpg)

 ChatGPT still said it wasn't able to fulfill the request. We worked down to 1,000 words before the chatbot produced the article. But there was another problem: no matter how many times we tried, ChatGPT couldn't produce 1,000 words on the subject. But why? What's limiting the chatbot's ability to produce longer replies?

 Part of the answer as to why this happens lies in something called the token system.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
### What Is the Token System ChatGPT Uses?

 When you ask ChatGPT a question, the length of the replies it can provide depends on a token system. Rather than a simple word count to determine the length of both queries and answers, ChatGPT uses this system. Notice something? The length of both "queries and answers" is taken into consideration. The token system breaks down each input and output into a series of tokens to classify the request and response size.

 While word count does play a part in this, it isn't the whole story. For instance, the example below was entered into[OpenAI's Tokenizer tool](https://platform.openai.com/tokenizer) .

![Screenshot of ChatGPT Tokenizer tool test](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-tokenizer-tool-test.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The sentence "How many words have I typed" and answer "6" were "tokenized" to a value of nine tokens. This is consistent with OpenAI's "rule of thumb" that one token is equivalent to around three-quarters of a word.

 Here's where things get a little bit tricky. OpenAI's GPT models come in varying token lengths. The standard GPT-4 model that comes with your ChatGPT Plus subscription offers anywhere between 4k and 8k token context length. OpenAI also provides an extended 32k token context length GPT-4 model. The GPT-3.5 series offers even more token variety. There are 4k, 8k, and 16k GPT-3.5 models. However, not all these models are publicly available.

 We used the base GPT-3.5 and supposed GPT-4 8k models for this test. We say "supposed" because the 8k tag didn't check out when we ran a context window test. And then there's the fact that there's no confirmation from official sources that the GPT-4 model at chat.openai.com is an 8k model.

 The base GPT 3.5 4k model is supposed to restrict user questions and replies to 4,097 tokens. Similarly, the GPT-4 8k model is supposed to deliver 8,192 tokens. By OpenAI's reckoning, this equates to about 3,000 words for the GPT-3.5 and around 5,000 to 6,000 words for the GPT-4 8k tokens. But wait a minute. With an approximate 3,000 to 6,000 words capacity on either model, why wasn't ChatGPT able to deliver a 2,500-word or even 1,500-word article when we requested? Why are ChatGPT responses much less than their advertised token count or context length?

## Why Are ChatGPT's Responses Limited?

 While token length looks straightforward and good in theory, there's more to how AI models consider these limits. There are two notable considerations.

1. **Past Conversations** : Because ChatGPT is a conversational chatbot, whenever you ask a question, the chatbot considers older conversations to stay consistent and ensure natural-sounding interactions. This means in longer conversations, older prompts and responses are invariably considered as part of the context window and end up eating your token length. So, it is not just the immediate question and replies that is considered in the context window calculation.
2. **System Demand** :[ChatGPT has quickly become one of the fastest-growing apps of all time](https://www.makeuseof.com/how-chatgpt-became-fastest-growing-app/) . This has generated a huge demand for ChatGPT. To ensure everyone gets a piece of the action, 8k tokens might not always be 8k. Remember, the more tokens to process, the more demand on the system. To lessen the average demand from each user, responses are curtailed to far below the stated limits.

 To stress, this is not a fixed rule—we generated outputs that exceeded this by almost two hundred words. However, this can be considered a safe upper limit to achieve complete answers.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## How to Get Longer Responses From ChatGPT

 Once you understand that there is a "hidden limit" to ChatGPT's responses, there are some simple ways to help you get more complete responses.

1. **Ask ChatGPT to Continue:** If ChatGPT stops partway through an answer, then one option is to simply ask it to continue. In the example below, we typed "Go on," and it added another two hundred words to the response.  
![Screenshot of ChatGPT being prompted to continue](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-being-prompted-to-continue.jpg)
2. **Break your question into smaller sections:** For instance, we asked it several times to write an essay on the impact of AI on society. One option here is to ask it to bullet-point some topics for an essay on AI, then use the supplied bullet points as individual prompts.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Screenshot of ChatGPT response to AI Bullet points](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-chatgpt-response-to-ai-bullet-points.jpg)
3. **Use the Regenerate option:** While this might throw up the same error, with nothing to lose, it is always worth a shot.
4. **Specify an upper limit to your word count in your prompt:** The image below illustrates how this can be used to manipulate the maximum word count in an answer.  
![Screenshot of using a word limit for ChatGPT response](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/screenshot-of-using-a-word-limit-for-chatgpt-response.jpg)
5. **Start a new conversation** : starting a new conversation gives you a clean slate to work with. Remember, ChatGPT considers past prompts and responses in a conversation. Starting a new chat gives you unused context to work with.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->

 These tips will help you to get more complete answers from ChatGPT and work around the unofficial limit in the length of its responses.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## ChatGPT: Quality Over Quantity

 While there is no official information on the maximum length of ChatGPT responses, in practice, there are hidden constraints. The token system, influenced by past conversations and system demand, all impact how long ChatGPT's answers can be. However, by asking ChatGPT to continue, breaking questions into parts, regenerating responses, specifying word counts, and starting new chats, you can often get more complete, longer replies. Though not perfect, being aware of these unofficial limits and using the right techniques can help you get the most out of this powerful AI chatbot.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-why-videos-speak-louder-for-brands/"><u>[New] 2024 Approved  Why Videos Speak Louder for Brands</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-cutting-edge-tools-for-youtube-content-capture-for-2024/"><u>[New] Cutting-Edge Tools for YouTube Content Capture for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-elevating-online-presence-with-obs-facebook-linking-for-2024/"><u>[New] Elevating Online Presence with OBS-Facebook Linking for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-capturing-the-moment-methods-for-online-audio-recording/"><u>[New] In 2024, Capturing the Moment  Methods for Online Audio Recording</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-the-ultimate-ppt-recording-process-explained/"><u>[New] In 2024, The Ultimate PPT Recording Process Explained</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-is-itops-feature-set-enough-to-justify-usage/"><u>[New] Is ITop's Feature Set Enough to Justify Usage?</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-quick-start-guide-dells-simple-screen-recording-methods-for-2024/"><u>[New] Quick Start Guide  Dell's Simple Screen Recording Methods for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-samsung-screen-captures-of-your-gaming-spree-for-2024/"><u>[New] Samsung Screen Captures of Your Gaming Spree for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-top-pick-screen-capture-tools-for-apple-devices/"><u>[New] Top Pick  Screen Capture Tools for Apple Devices</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-transform-your-virtual-engagements-with-these-top-10-cost-free-tools/"><u>[New] Transform Your Virtual Engagements with These Top 10 Cost-Free Tools</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-mastering-video-record-with-vlc/"><u>[Updated] 2024 Approved  Mastering Video Record with VLC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-crafting-engaging-sims-4-gameplay-videos/"><u>[Updated] In 2024, Crafting Engaging Sims 4 Gameplay Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-streamlining-your-gaming-diary-overwatch-video-documentation/"><u>[Updated] In 2024, Streamlining Your Gaming Diary  Overwatch Video Documentation</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-is-itops-performance-worth-your-investment-in-2024/"><u>[Updated] Is ITop's Performance Worth Your Investment, In 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-setting-up-your-logitech-webcam-for-recording/"><u>[Updated] Setting Up Your Logitech Webcam for Recording</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-techniques-that-elevate-your-ppt-recording-experience-for-2024/"><u>[Updated] Techniques that Elevate Your PPT Recording Experience for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-art-of-instagram-videography-capturing-attention/"><u>[Updated] The Art of Instagram Videography  Capturing Attention</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-breaking-the-freeze-reviving-your-obs-cam/"><u>2024 Approved  Breaking the Freeze  Reviving Your OBS Cam</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-google-hangout-techniques-4-ways-to-shine/"><u>2024 Approved  Google Hangout Techniques, #4 Ways to Shine</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlock-the-power-of-spotifys-advertising-potential/"><u>2024 Approved  Unlock the Power of Spotify’s Advertising Potential</u></a></li>
<li><a href="https://extra-tips.techidaily.com/crafting-chuckles-in-cyberspace-diy-memes-of-the-metaverse/"><u>Crafting Chuckles in Cyberspace  DIY Memes of the Metaverse</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-se-2020-to-the-previous-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone SE (2020) to the Previous iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-samsung-galaxy-a15-4g-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Samsung Galaxy A15 4G to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-change-screenshot-saving-location-on-mac/"><u>In 2024, Change Screenshot Saving Location on Mac</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-streamline-playlist-dissemination-on-youtube/"><u>In 2024, Streamline Playlist Dissemination on Youtube</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-oneplus-11-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to OnePlus 11 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://extra-resources.techidaily.com/laugh-o-matic-crafting-gags-on-the-house-rate/"><u>Laugh-O-Matic  Crafting Gags on the House Rate</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-the-art-of-image-editing-in-depth-analysis-of-adobe-ps-background-removal-tool/"><u>Mastering the Art of Image Editing  In-Depth Analysis of Adobe PS Background Removal Tool</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pixelperfect-image-transformations-for-2024/"><u>PixelPerfect Image Transformations for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/profit-maximizers-playlist-8-tools-and-products-to-elevate-your-business-game/"><u>Profit Maximizers Playlist  8 Tools & Products to Elevate Your Business Game</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-ultimate-list-of-free-windows-screenshot-apps/"><u>The Ultimate List of Free Windows Screenshot Apps</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/ultimate-guide-new-camera-recording-tech-overview-for-2024/"><u>Ultimate Guide  New Camera Recording Tech Overview for 2024</u></a></li>
</ul></div>
