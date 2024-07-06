---
title:		"How to create a serverless Google Drive indexer using Cloudflare."
date:		2022-05-05 22:45:00
updated:	2022-05-05 22:45:13
tags: 
  - Cloudflare Workers
  - Create
  - Google Drive Indexer
  - How
  - technology	
permalink:	https://www.techtracker.in/2022/05/how-to-create-serverless-google-drive.html
---

<div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-1jM97uweY4M/YnQGHbr7VNI/AAAAAAAAKuE/yfGTFfEn5sIk7gCW22QTuvG9byZdQr3YACNcBGAsYHQ/s1600/1651770904696097-0.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-1jM97uweY4M/YnQGHbr7VNI/AAAAAAAAKuE/yfGTFfEn5sIk7gCW22QTuvG9byZdQr3YACNcBGAsYHQ/s1600/1651770904696097-0.png" width="400">
  </a>
</div><div><br></div><div><br></div><div>Drive is undoubtedly one of the most popular free cloud storage platform from search engine giant Google where you can&nbsp;</div><div>store all your files but like any other cloud storage platform you account is linked to your Email thus if by any chance you lose your account then you can't access Drive and it's files if they are private.</div><div><br></div><div>Usually, Google Drive users who never want to loose files create public links of files and save them somewhere safe so that they can access and download them anytime but Google Drive public links not only lengthy in characters but also don't look professional if you want to send on chat or include in articles etc.</div><div><br></div><div>If you're someone who frequently share Google Drive folders and files on blogs or websites then for sure it's very important brand Google Drive lengthy links with your custom domain isn't to get credits and let people know your'e the real owner of files right? but unfortunately as of now Google Drive has no option to customize links.</div><div><br></div><div>Eventhough, you can use url shortener platforms like Rebrand.ly to shorten Google Drive lengthy links with your custom domain yet once you load short link on browser it will redirect to original Google Drive lengthy links, so people will just share Google Drive lengthy links on internet without giving credits to you.</div><div><br></div><div>Recently, we found an github project named aicrou goindex-theme-acrou to create a serverless Google Drive indexer using Cloudflare Workers which supports custom domain so from now people will know you're the real owner of files, isn't cool? are you ready to create free custom domain Google Drive indexer? If yes let's&nbsp; &nbsp; get started.</div><div><br></div><div><b>• How to create a serverless free Google Drive indexer using Cloudflare Workers •</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-BlMhRszXmQ8/YnQGGPKRLcI/AAAAAAAAKuA/mUbtg4ZmYQ0WOHkKjbR3sf1BlZzdwhSKACNcBGAsYHQ/s1600/1651770899578066-1.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-BlMhRszXmQ8/YnQGGPKRLcI/AAAAAAAAKuA/mUbtg4ZmYQ0WOHkKjbR3sf1BlZzdwhSKACNcBGAsYHQ/s1600/1651770899578066-1.png" width="400">
  </a>
</div><br></b></div><div>- Go to <a href="https://goindex-builder-acrou.glitch.me/">goindex-builder-acrou.glitch.me</a></div><div>then tap on <b>Click me</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-n8l4BXyRedY/YnQGEoKGYEI/AAAAAAAAKt8/3uzR_aMDaRgTfOfyg-OOeTInTWHU8BTMwCNcBGAsYHQ/s1600/1651770893526178-2.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-n8l4BXyRedY/YnQGEoKGYEI/AAAAAAAAKt8/3uzR_aMDaRgTfOfyg-OOeTInTWHU8BTMwCNcBGAsYHQ/s1600/1651770893526178-2.png" width="400">
  </a>
</div></b><br></div><div>- Select your Google Account then tap on <b>Allow</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-7Qk-9RB8x1s/YnQGDfMAN6I/AAAAAAAAKt4/RuoqZfJKYAIF_svaPmvflEkiigvkRY69QCNcBGAsYHQ/s1600/1651770887883885-3.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-7Qk-9RB8x1s/YnQGDfMAN6I/AAAAAAAAKt4/RuoqZfJKYAIF_svaPmvflEkiigvkRY69QCNcBGAsYHQ/s1600/1651770887883885-3.png" width="400">
  </a>
</div><br></b></div><div>- Copy Authorization code then go back to&nbsp;</div><div><a href="https://www.goindex-builder-acrou.glitch.me">goindex-builder-acrou.glitch.me</a></div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-cjbcsYBO6Tw/YnQGBzbacUI/AAAAAAAAKt0/q3BAhBryAgk_cQ3ZA7EWUZEx227IU8YRQCNcBGAsYHQ/s1600/1651770883151539-4.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-cjbcsYBO6Tw/YnQGBzbacUI/AAAAAAAAKt0/q3BAhBryAgk_cQ3ZA7EWUZEx227IU8YRQCNcBGAsYHQ/s1600/1651770883151539-4.png" width="400">
  </a>
</div><br></div><div>- In fill the form, Paste your Authorization code then scroll down.</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-v0AqyTJibRU/YnQGAk03-CI/AAAAAAAAKtw/U2yAu5BU-kQLlYcEyojDOfcRUGT985nWgCNcBGAsYHQ/s1600/1651770878564981-5.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-v0AqyTJibRU/YnQGAk03-CI/AAAAAAAAKtw/U2yAu5BU-kQLlYcEyojDOfcRUGT985nWgCNcBGAsYHQ/s1600/1651770878564981-5.png" width="400">
  </a>
</div><br></div><div>- Select language then tap on <b>Get Code</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-K6XH2UkElLo/YnQF_m6OOeI/AAAAAAAAKts/3yxEU7D0MC4242RKYZu7Fj6C2o5pMjwcACNcBGAsYHQ/s1600/1651770872795149-6.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-K6XH2UkElLo/YnQF_m6OOeI/AAAAAAAAKts/3yxEU7D0MC4242RKYZu7Fj6C2o5pMjwcACNcBGAsYHQ/s1600/1651770872795149-6.png" width="400">
  </a>
</div><br></b></div><div><br></div><div>- In Finished, tap on <b>Copy the code to clipboard</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-juO7AzvD5BE/YnQF-HE7-hI/AAAAAAAAKto/qQGee0WirGkkU1hY1gQO3Gk1-fn6qfL7QCNcBGAsYHQ/s1600/1651770867790044-7.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-juO7AzvD5BE/YnQF-HE7-hI/AAAAAAAAKto/qQGee0WirGkkU1hY1gQO3Gk1-fn6qfL7QCNcBGAsYHQ/s1600/1651770867790044-7.png" width="400">
  </a>
</div><br></b></div><div>- Go to <a href="http://Cloudflare.com">Cloudflare</a> and sign up or login the add Website into your dashboard.</div><div><br></div><div><b><a href="https://www.techtracker.in/2021/12/how-to-add-cloudflare-on-blogger-to.html">+ How to add cloudflare on blogger to optimize and stop bot traffic.</a></b></div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-Ua5R18AJuoo/YnQF8_b4D_I/AAAAAAAAKtk/v3rzKwmqJj4PqQ1TYceojK5YExT0VIsTQCNcBGAsYHQ/s1600/1651770862829449-8.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-Ua5R18AJuoo/YnQF8_b4D_I/AAAAAAAAKtk/v3rzKwmqJj4PqQ1TYceojK5YExT0VIsTQCNcBGAsYHQ/s1600/1651770862829449-8.png" width="400">
  </a>
</div><br></div><div>- Tap on&nbsp;<b>≡</b>&nbsp;then tap on <b>Workers</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-CNwYzXIaxPM/YnQF7h5s40I/AAAAAAAAKtg/qOOj9V4WtYkrG7_49UfRymltcCbxz3N3gCNcBGAsYHQ/s1600/1651770857781930-9.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-CNwYzXIaxPM/YnQF7h5s40I/AAAAAAAAKtg/qOOj9V4WtYkrG7_49UfRymltcCbxz3N3gCNcBGAsYHQ/s1600/1651770857781930-9.png" width="400">
  </a>
</div><br></b></div><div>- Tap on <b>Create a Service</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-BuJDLE-Sdpo/YnQF6S7mJ9I/AAAAAAAAKtc/uAps6j_1EVET1yj_xxH4cUbFo8d2LUb-QCNcBGAsYHQ/s1600/1651770852755298-10.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-BuJDLE-Sdpo/YnQF6S7mJ9I/AAAAAAAAKtc/uAps6j_1EVET1yj_xxH4cUbFo8d2LUb-QCNcBGAsYHQ/s1600/1651770852755298-10.png" width="400">
  </a>
</div><br></b></div><div>- Enter <b>Service name</b> then scroll down</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-JiVRab0juOI/YnQF5Jc7ZMI/AAAAAAAAKtY/niGgOp15xikobf2Di1hQMsWK4u4nbqfcwCNcBGAsYHQ/s1600/1651770848451879-11.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-JiVRab0juOI/YnQF5Jc7ZMI/AAAAAAAAKtY/niGgOp15xikobf2Di1hQMsWK4u4nbqfcwCNcBGAsYHQ/s1600/1651770848451879-11.png" width="400">
  </a>
</div><br></div><div>- Tap on <b>Create service</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-kNeVQXRy3N4/YnQF31TZtFI/AAAAAAAAKtU/8qxV-jg422ASaVnKvQC6-I8hEq24yi9RgCNcBGAsYHQ/s1600/1651770843002533-12.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-kNeVQXRy3N4/YnQF31TZtFI/AAAAAAAAKtU/8qxV-jg422ASaVnKvQC6-I8hEq24yi9RgCNcBGAsYHQ/s1600/1651770843002533-12.png" width="400">
  </a>
</div><br></b></div><div>- Tap on <b>Quick edit</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-sUg9WSIcqe4/YnQF2pTwaZI/AAAAAAAAKtQ/BWZCenzvHsQp3nF5x89yt_S_5w3fq82YQCNcBGAsYHQ/s1600/1651770837168519-13.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-sUg9WSIcqe4/YnQF2pTwaZI/AAAAAAAAKtQ/BWZCenzvHsQp3nF5x89yt_S_5w3fq82YQCNcBGAsYHQ/s1600/1651770837168519-13.png" width="400">
  </a>
</div><br></b></div><div>- Remove existing code and paste the code which you copied earlier then tap on <b>Save and Deploy</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-EdjaOrQKYYA/YnQF1IJoIwI/AAAAAAAAKtM/kAYh8HDGbjEA1Q3IQ28sXRu6lqE2K6oqwCNcBGAsYHQ/s1600/1651770832022174-14.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-EdjaOrQKYYA/YnQF1IJoIwI/AAAAAAAAKtM/kAYh8HDGbjEA1Q3IQ28sXRu6lqE2K6oqwCNcBGAsYHQ/s1600/1651770832022174-14.png" width="400">
  </a>
</div><br></b></div><div>- Tap on <b>Save and Deploy</b> again</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-ACQV6u_Ygdw/YnQFz0akGxI/AAAAAAAAKtI/a2nFjATHJFQWjDSdIJpD98YSNUOnvSfewCNcBGAsYHQ/s1600/1651770826945418-15.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-ACQV6u_Ygdw/YnQFz0akGxI/AAAAAAAAKtI/a2nFjATHJFQWjDSdIJpD98YSNUOnvSfewCNcBGAsYHQ/s1600/1651770826945418-15.png" width="400">
  </a>
</div><br></div><div>- Tap on&nbsp;<b>≡</b>&nbsp;then tap on <b>Websites</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-JM_apPE2Htw/YnQFyQNQ0AI/AAAAAAAAKtE/1o1fX0xjeVUPJ6shMB4m1NCKfR78vhFkQCNcBGAsYHQ/s1600/1651770822046820-16.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-JM_apPE2Htw/YnQFyQNQ0AI/AAAAAAAAKtE/1o1fX0xjeVUPJ6shMB4m1NCKfR78vhFkQCNcBGAsYHQ/s1600/1651770822046820-16.png" width="400">
  </a>
</div></b><br></div><div>- Select your website</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-hD7_KBnor2g/YnQFxc-59aI/AAAAAAAAKtA/f9bnvK2M3XYYiTNycGQVl3F2c8P7SiNvQCNcBGAsYHQ/s1600/1651770817700183-17.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-hD7_KBnor2g/YnQFxc-59aI/AAAAAAAAKtA/f9bnvK2M3XYYiTNycGQVl3F2c8P7SiNvQCNcBGAsYHQ/s1600/1651770817700183-17.png" width="400">
  </a>
</div><br></div><div>- Tap on <b>≡</b> then tap on <b>DNS</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-1Xpja59tL-k/YnQFwX4KMjI/AAAAAAAAKs8/_Eg5_-PMYiYZuMDQ6XKgHsdCeO8XAAkDgCNcBGAsYHQ/s1600/1651770812885947-18.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-1Xpja59tL-k/YnQFwX4KMjI/AAAAAAAAKs8/_Eg5_-PMYiYZuMDQ6XKgHsdCeO8XAAkDgCNcBGAsYHQ/s1600/1651770812885947-18.png" width="400">
  </a>
</div><br></b></div><div>- Tap on<b> + Add record</b> and add subdomain using A or Cname records.</div><div><br></div><div>- If A records failed then try Cname records it will work for sure.</div><div><br></div><div>- Tap on <b>Save</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-BZajml86_EM/YnQFuzKJSrI/AAAAAAAAKs4/xwMKLck6fHgEOP6LEGRHQKEex_RkWRk-wCNcBGAsYHQ/s1600/1651770807563964-19.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-BZajml86_EM/YnQFuzKJSrI/AAAAAAAAKs4/xwMKLck6fHgEOP6LEGRHQKEex_RkWRk-wCNcBGAsYHQ/s1600/1651770807563964-19.png" width="400">
  </a>
</div><br></b></div><div>- Now, go back to Workers then tap on <b>Add route</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-CVuM_AXKXFg/YnQFtrv1KOI/AAAAAAAAKs0/uUq3LMVtRXAIqII8NhbJtA5k6O5LBuK-gCNcBGAsYHQ/s1600/1651770802577446-20.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-CVuM_AXKXFg/YnQFtrv1KOI/AAAAAAAAKs0/uUq3LMVtRXAIqII8NhbJtA5k6O5LBuK-gCNcBGAsYHQ/s1600/1651770802577446-20.png" width="400">
  </a>
</div><br></b></div><div>- Replace my sub-domain with yours, select Service and Environment then tap on <b>Save</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-sGJnAGYx9bA/YnQFsbhINSI/AAAAAAAAKsw/IGEqoEMhHGMysPZlXWUckxp2eTR4pWpvACNcBGAsYHQ/s1600/1651770796184526-21.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-sGJnAGYx9bA/YnQFsbhINSI/AAAAAAAAKsw/IGEqoEMhHGMysPZlXWUckxp2eTR4pWpvACNcBGAsYHQ/s1600/1651770796184526-21.png" width="400">
  </a>
</div><br></b></div><div><br></div><div>- Voila, you successfully created a free serverless custom domain Google Indexer.</div><div><br></div><div>Atlast, this are just highlighted features of Cloudflare Workers and aicrou goindex-theme-acrou project there&nbsp;may be many hidden features in-built to provide external features for ultimate usage experience, anyway if you want to create best indexer then aicrou goindex-theme-acrou is best on go choice for sure.</div><div><br></div><div>Overall, it is very easy to implement aicrou goindex-theme-acrou project&nbsp;on Cloudflare Workers to get simple and clean user-friendly Google Drive indexer for free, thanks to user friendly GitHub repository but in any project there is always space available for improvement so let's wait and see will goindex-theme-acrou project&nbsp;get any major changes in future to make it even better as of now it's pretty nice.</div><div><br></div><div>Moreover, goindex-theme-acrou project&nbsp;+ Cloudflare Workers is one of the very few methods available out there on internet to create best free serverless Google drive indexer, yes indeed if you're searching for such method then goindex-theme-acrou project&nbsp;potential to become your new favourite for sure.</div><div><br></div><div>Finally, this is how you can create a free serverless Google Drive indexer using Cloudflare Workers, are you an existing user of this method? If yes do say your experience and mention if you know any better method to get Google Drive indexer in our comment section below, see ya :)</div>
<!-- no comments on this post -->