# PRoJEct-NeGYa

Hacker style personal homepage template.

Version： v1.01

## Characteristics

1. Crazy and cool
2. Rouge support code highlighting
3. MathJax formula
4. Article index
5. Highly customizable
6. Encrypted content (you can also change the element id to cipher text, and the element content writes "No access to this field!")

## Update log

2019.7.17：Update documentation

2019.6.15：I will do this version, I can use it, I can't change it!

## Instructions

* Download or fork into your own GitHub repository
* Modify the _config.yml file
* (custom domain name) modify the CNAME file
* Modify the pages/index.md file to customize the home page
* Delete the files in the _posts/ folder and add your own articles
* Sync to github remote repository

## Engineering Structure

Functional and content isolation TMD!

Website content：
* _posts：article
* pages：page
* assets/img：figure

Functional Style：
* _includes：Subpage module
* _layouts：Page template (simply combining subpage modules)
* assets/css：Style sheet file
* assets/fonts：Font file
* assets/js：Script file
* _config.yml：Configuration file

