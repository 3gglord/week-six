# Week six notes

what approach best suits the story/message/finding that you're trying to convey?

- Virginia Woolf's diaries from 1924 to 1929 while writing and publishing her novel, To The Lighthouse
### guiding research questions
- focus on the content, themes of the diary
- use corpus linguistics to analyse her process of writing
- how did Woolf's process invlove the people around her and the society that she was living through
- today, she is regarded as a feminist inspiration in her writing. to what extent is that reflected in her diary?
- how does Woolf write about emotion? 

- using python to create urls
- https://stackoverflow.com/questions/4288973/whats-the-difference-between-s-and-d-in-python-string-formatting
- got an error message
- made my own urls.txt file by copying one link and then using regex to change the endings for each page
- ran through wget
- got rid of anything I didn't need
- tried to use a code in R to change all of my html files into txt files so that I could run it through AntConc later
- got an error message and none of the webpages made sense to me (math related)
  - thought that I was in over my head and decided to open the files and convert them by hand
- used RegEx to clean up the files, get rid of the html formatting things that I did not need
https://jdhao.github.io/2019/02/28/sublime_text_regex_cheat_sheet/
- `<br/>|&amp;|&nbsp;` replace with ` `
- `">|<br/>|<span.*">|</span>|&nbsp;|&amp;`
  - for example, one file looked like this before:
  - and like this after:
  
- downloading and cleaning up the data took the longest
- running the data through Antconc and filtering for certain words and phrases
  - transcription oddities like brackets in the middle of words could alter the findings
  - has a habit of referring to people close to her by their inital (ex. her husband as L. instead of Leonard)
  
- topic models
  - something wrong with the dates: 
  - re-run the code using "year" instead of decade from line 88 onwards
  
- voyant
  - cirrus:
<iframe style='width: 364px; height: 343px;' src='http://127.0.0.1:8888/tool/Cirrus/?corpus=48039cebd0076122253ce951cbbef258'></iframe>
  - terms: <iframe style='width: 364px; height: 343px;' src='http://127.0.0.1:8888/tool/CorpusTerms/?corpus=48039cebd0076122253ce951cbbef258'></iframe>
  - Vita and Leonard terms:
  <iframe style='width: 364px; height: 343px;' src='http://127.0.0.1:8888/tool/Trends/?query=vita*&query=leonard*&corpus=48039cebd0076122253ce951cbbef258'></iframe>
  - think, write, book links
  <iframe style='width: 416px; height: 343px;' src='http://127.0.0.1:8888/tool/CollocatesGraph/?query=think*&query=write*&query=book*&mode=corpus&corpus=48039cebd0076122253ce951cbbef258'></iframe>

- wget
- regex
- antconc
- topic models to get an overview of the themes https://programminghistorian.org/en/lessons/corpus-analysis-with-antconc
- voyant
- some way of communicating my findings
  - poster
  - **static website** so that people can interact with the visualizations, especially because I used voyant
  - https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site
  - https://help.github.com/en/github/working-with-github-pages/adding-content-to-your-github-pages-site-using-jekyll
  - https://stackoverflow.com/questions/6348207/making-a-paragraph-in-html-contain-a-text-from-a-file
  - https://www.w3schools.com/tags/att_object_width.asp
  - would like to add a navigation bar
  
