---
title:		"How to host a static website using GitLab pages for free."
date:		2022-04-24 22:38:00
updated:	2022-04-24 22:38:02
tags: 
  - GitLab pages
  - How
  - Static Website
  - host
  - technology	
permalink:	https://www.techtracker.in/2022/04/how-to-host-static-website-using-gitlab.html
---

<div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-kCEGI2WhIlw/YmWD8HUedSI/AAAAAAAAKZA/_gtoSzxQmKY-T7gVfjf0FOVqrvH23FMVgCNcBGAsYHQ/s1600/1650820076606551-0.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-kCEGI2WhIlw/YmWD8HUedSI/AAAAAAAAKZA/_gtoSzxQmKY-T7gVfjf0FOVqrvH23FMVgCNcBGAsYHQ/s1600/1650820076606551-0.png" width="400">
  </a>
</div><div><br></div><div><br></div><div>Now a days in order to create website most people rely on hosting platforms or content management systems like Blogger and WordPress over there you will get alot of features and options to customize and publish your website as you like but most reliable hosting platforms require money to host your website.</div><div><br></div><div>Even though there are some hosting platforms like Bytehost and Infinity Free and content management platforms like Blogger and WordPress etc provide free services yet there are few necessary features missing that are required by Geeks and developers so they usually prefer Github or GitLab to host static websites or blogs for free.</div><div><b><br></b></div><div><b><a href="https://www.techtracker.in/2022/04/how-to-host-website-on-github-pages-for.html">+ How to host website on GitHub Pages for free.</a></b></div><div><br></div><div>GitLab is most popular platform for developers after Github where you'll get tools and amazing features to automate development of software easily, and by using GitLab you can also host static website even though the process is little different to GitHub.</div><div><br></div><div>On GitLab you can create public repositories for open source projects so that anyone on internet can contribute to your project including that you can also create private repositories for yourself or team just like GitHub, anyway now we are going to create public repository to host static website on GitLab, so do you like it? are you ready? If yes let's get started.</div><div><br></div><div><b>• GitLab official support •</b></div><div><b><br></b></div><div>- <a href="https://www.facebook.com/gitlab">Facebook</a></div><div>- <a href="https://twitter.com/gitlab">Twitter</a></div><div>- <a href="https://www.linkedin.com/company/gitlab-com">LinkedIn</a></div><div>- <a href="https://www.youtube.com/channel/UCnMGQ8QHMAnVIsI3xJrihhg">YouTube</a></div><div><br></div><div><b>Website : </b><a href="http://Gitlab.com">Gitlab.com</a></div><div><br></div><div><b>• How to create a static website using GitLab pages •</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-ob19myStjS4/YmWD7CRLjxI/AAAAAAAAKY8/NcEyPKkeaQwNme3iR9GiIx4I2wWlv_XXgCNcBGAsYHQ/s1600/1650820071874335-1.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-ob19myStjS4/YmWD7CRLjxI/AAAAAAAAKY8/NcEyPKkeaQwNme3iR9GiIx4I2wWlv_XXgCNcBGAsYHQ/s1600/1650820071874335-1.png" width="400">
  </a>
</div><br></b></div><div><br></div><div>- Go to GitLab Signup and create account using available options.</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-oln329dGQHE/YmWD56w7fgI/AAAAAAAAKY4/BX5NBOTRtSALKd8V1hSoAjmy0lA4V1UEwCNcBGAsYHQ/s1600/1650820066421615-2.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-oln329dGQHE/YmWD56w7fgI/AAAAAAAAKY4/BX5NBOTRtSALKd8V1hSoAjmy0lA4V1UEwCNcBGAsYHQ/s1600/1650820066421615-2.png" width="400">
  </a>
</div><br></div><div>- Tap on <b>Accept terms</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-BfgvjhO3vBg/YmWD4nr_bhI/AAAAAAAAKY0/jaBBWRXAE7QC8ijDVI51QmsEPzv9r-TXwCNcBGAsYHQ/s1600/1650820062502206-3.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-BfgvjhO3vBg/YmWD4nr_bhI/AAAAAAAAKY0/jaBBWRXAE7QC8ijDVI51QmsEPzv9r-TXwCNcBGAsYHQ/s1600/1650820062502206-3.png" width="400">
  </a>
</div><br></b></div><div>- Tap on <b>Create blank project</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-XjQzYjKFEu4/YmWD3dV3q-I/AAAAAAAAKYw/RbcNFrWCBnoqjXmAEbA9OrXy_jd2XJtgQCNcBGAsYHQ/s1600/1650820057707714-4.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-XjQzYjKFEu4/YmWD3dV3q-I/AAAAAAAAKYw/RbcNFrWCBnoqjXmAEbA9OrXy_jd2XJtgQCNcBGAsYHQ/s1600/1650820057707714-4.png" width="400">
  </a>
</div><br></b></div><div>- Enter Project name, Project slug and then scroll down.</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-QW4a2qcVyx4/YmWD2DJTorI/AAAAAAAAKYs/qeMjcFFYbnQ66hMbFFUCDSbDVkxT4fr0ACNcBGAsYHQ/s1600/1650820053030390-5.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-QW4a2qcVyx4/YmWD2DJTorI/AAAAAAAAKYs/qeMjcFFYbnQ66hMbFFUCDSbDVkxT4fr0ACNcBGAsYHQ/s1600/1650820053030390-5.png" width="400">
  </a>
</div><br></div><div>- Select Public then Tap on <b>Create project</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-kl1Ky-6oEfg/YmWD1O6jr2I/AAAAAAAAKYo/1yHHwwbHh5Mz8pQyVO4zCljSNnYVlHL7QCNcBGAsYHQ/s1600/1650820046054219-6.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-kl1Ky-6oEfg/YmWD1O6jr2I/AAAAAAAAKYo/1yHHwwbHh5Mz8pQyVO4zCljSNnYVlHL7QCNcBGAsYHQ/s1600/1650820046054219-6.png" width="400">
  </a>
</div><br></b></div><div><b><br></b></div><div>- Scroll down then tap on <b>Upload File</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-1PMKbGYBqXI/YmWDzbVKSbI/AAAAAAAAKYk/AgLzZufASfwmvp7LimGDqvzJQoYhOv3YwCNcBGAsYHQ/s1600/1650820041906123-7.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-1PMKbGYBqXI/YmWDzbVKSbI/AAAAAAAAKYk/AgLzZufASfwmvp7LimGDqvzJQoYhOv3YwCNcBGAsYHQ/s1600/1650820041906123-7.png" width="400">
  </a>
</div><br></b></div><div>- Select your .html file from storage then tap on <b>Upload file.</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-XOXSfUoVaCU/YmWDyUQkImI/AAAAAAAAKYg/wZh_v3NE3dYT0BFF4oEDhx7GKLrDhni6gCNcBGAsYHQ/s1600/1650820038422934-8.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-XOXSfUoVaCU/YmWDyUQkImI/AAAAAAAAKYg/wZh_v3NE3dYT0BFF4oEDhx7GKLrDhni6gCNcBGAsYHQ/s1600/1650820038422934-8.png" width="400">
  </a>
</div><br></b></div><div>- Now open your file manager, I suggest Mixplorer and create .TXT file named <b>.gitlab-ci.yml</b> and edit it.</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/--OA8TqoG574/YmWDxfnbS_I/AAAAAAAAKYc/OanH9WueJ9ITBE2rzNbGWu8AcVFTJM9PgCNcBGAsYHQ/s1600/1650820034607698-9.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/--OA8TqoG574/YmWDxfnbS_I/AAAAAAAAKYc/OanH9WueJ9ITBE2rzNbGWu8AcVFTJM9PgCNcBGAsYHQ/s1600/1650820034607698-9.png" width="400">
  </a>
</div><br></div><div>- Copy CI code from <a href="https://about.gitlab.com/blog/2016/04/07/gitlab-pages-setup/">github-pages-setup</a> and paste it in -gitlab-ci.yml TXT file then save it.</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-KT_9y2gUWrg/YmWDwUreu_I/AAAAAAAAKYY/foCPv4XTEJEvlQ1-O9rkh-py1RhKc89EACNcBGAsYHQ/s1600/1650820029486804-10.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-KT_9y2gUWrg/YmWDwUreu_I/AAAAAAAAKYY/foCPv4XTEJEvlQ1-O9rkh-py1RhKc89EACNcBGAsYHQ/s1600/1650820029486804-10.png" width="400">
  </a>
</div><br></div><div>- Once done Go back to GitLab then tap on <b>Upload File</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-GWiqEh--mIE/YmWDvVL4QJI/AAAAAAAAKYU/2jl_y_0FoVMnDrrfHoX4Gfjy6Q1uRWMkQCNcBGAsYHQ/s1600/1650820025557144-11.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-GWiqEh--mIE/YmWDvVL4QJI/AAAAAAAAKYU/2jl_y_0FoVMnDrrfHoX4Gfjy6Q1uRWMkQCNcBGAsYHQ/s1600/1650820025557144-11.png" width="400">
  </a>
</div><br></b></div><div>- Select your .gitlab-ci.yml file from storage then tap on <b>Upload file</b></div><div><b><br></b></div><div><b><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-SevS911t_T4/YmWDuEsH3aI/AAAAAAAAKYQ/hh9uzpw2RiwQAIjV0lsnc_Y0aWStIrydACNcBGAsYHQ/s1600/1650820016721126-12.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-SevS911t_T4/YmWDuEsH3aI/AAAAAAAAKYQ/hh9uzpw2RiwQAIjV0lsnc_Y0aWStIrydACNcBGAsYHQ/s1600/1650820016721126-12.png" width="400">
  </a>
</div><br></b></div><div>- That's it, you successfully created and deployed static website on GitLab but you should validate your account using credit or debit card to run pipelines.</div><div><br></div><div><div class="separator" style="clear: both; text-align: center;">
  <a href="https://lh3.googleusercontent.com/-A08dTFOD1oU/YmWDrwdTlwI/AAAAAAAAKYM/QuBC6rWaiSstOlmnkBVUw2fvFRz3Z_-zgCNcBGAsYHQ/s1600/1650820012257192-13.png" imageanchor="1" style="margin-left: 1em; margin-right: 1em;">
    <img border="0" src="https://lh3.googleusercontent.com/-A08dTFOD1oU/YmWDrwdTlwI/AAAAAAAAKYM/QuBC6rWaiSstOlmnkBVUw2fvFRz3Z_-zgCNcBGAsYHQ/s1600/1650820012257192-13.png" width="400">
  </a>
</div><br></div><div>- YAY, once you validate your account go to yourgitlabusername.github.com/your.html to check your static website.</div><div><br></div><div>Atlast, this are just highlighted features of GitLab there may be many hidden features in-build that provides you external benefits to give the ultimate usage experience, if you want one of the best free and reliable platform to host your static websites or blog then GitLab pages is worthy choice..</div><div><br></div><div><br></div><div>Overall, it is very easy to create website on Github through GitHub pages due to simple and clean interface that ensures user friendly experience, but in any project there is always space for improvement so let's wait and see will GitLab get any major changes in future to make it even better as now it's cool.</div><div><br></div><div>Moreover, it is definitely worth to mention you can also create Jekyll and hexo websites etc with custom domain support and free SSL and TLS certification on GitLab pages using this <a href="https://about.gitlab.com/blog/2016/04/07/gitlab-pages-setup/">guide</a>, yes indeed if you're searching for such platform then GitLab has potential to become your new favourite choice for sure.</div><div><br></div><div>Finally, this is GitHub pages a Integration of GitLab to create websites or blogs for free, are you an existing user of GitLab pages? If yes do say your experience and mention which feature of GitLab pages you like the most in our comment section below, see ya :)</div>
<!-- no comments on this post -->