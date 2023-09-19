# XSS in Subrion 4.2.1 (/panel/languages/)

**Software link**: Subrion CMS 4.2.1 [https://subrion.org/download/]

**@author**: Alejandro Amorín

**Description**: Cross-site scripting (XSS) vulnerability in /panel/languages/ of Subrion v4.2.1 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into 'Title' parameter.

## POC

1. Create or edit a new language
   
![xss1](https://github.com/al3zx/xss_languages_subrion_4.2.1/assets/20266218/5acfe422-a9d6-4cab-993f-31f649e20c68)

2. Insert the payload in 'Title' field
   
![xss2](https://github.com/al3zx/xss_languages_subrion_4.2.1/assets/20266218/f4155395-bc5e-4180-b75b-83ff16b4812a)

3. Add
   
![xss3](https://github.com/al3zx/xss_languages_subrion_4.2.1/assets/20266218/eba8a8e2-c9f3-4ed6-9ba3-ee2448b96723)




