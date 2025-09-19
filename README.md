# CTF-usefull info

> **Disclaimer**  
> All information is provided "as is" without any guarantees of completeness, accuracy, or reliability.  
> The author assumes no responsibility for errors or omissions in the content.  
> Use of the information is at your own risk. The author shall not be held liable for any damages arising from its use.
> Author also have dyslexia and might struggle with some spelling, please be mindfull 

# Links
### AI
https://chatgpt.com
https://chat.deepseek.com/

- jail braking if something goes wrong (generally deepseek seems to be more ok with cybersecurity)

https://www.promptfoo.dev/blog/how-to-jailbreak-llms/

### Decoders
- https://dencode.com/string
(seems like have all/most)

### Images
- Reverse search
https://tineye.com/
- Meta Data 
https://exifmeta.com/
https://www.metadata2go.com/
- stenography
https://www.georgeom.net/StegOnline/upload
(has also some very old writeups about some random ctf)
https://aperisolve.fr/ (also accepts vidios)


### Info search mega link
https://github.com/TCM-Course-Resources/Open-Source-Intellingence-Resources?tab=readme-ov-file

### Old cheatsheets
https://github.com/jackdaw5/CTF-cheat-sheet
https://github.com/TheGreyCore/CTFcheatsheet

# Commands
### Linux Basic
| Term                        | command                                                                                                       |
|:----------------------------|:-----------------------------------------------------------------------------------------------------------------|
|download zip| ```curl http://shared.target05/backup.zip --output backup.zip```|
| text finding:|:----------------------------|
| - recursive aka all folders|    ```grep -r "search_term" /path/to/directory```|
| - case insensetive (aka ignore case)| ```grep -i "search_term" filename.txt```|
|Print lines containing a specific pattern| ```awk '/error/' log.txt```|
|finding files|  ```find /path/to/directory -name "filename"```|
|binary files|For binary files or unknown encodings, use strings and grep. ```strings binaryfile | grep "search_term"```|
|compressed files| ```zgrep "search_term" file.gz```|

### Search operators (DuckDuckGo)

| Term                        | Effect                                                                                                           |
|:----------------------------|:-----------------------------------------------------------------------------------------------------------------|
| ```"cats and dogs" ```      | Results for exact term "cats and dogs". If no or few results are found, we'll try to show related results.       | 
| ```~"cats and dogs" ```     | Experimental syntax: more results that are semantically similar to "cats and dogs", like "cats & dogs" and "dogs and cats" in addition to "cats and dogs".                                                                                                        |
| ```cats -dogs ```           | Fewer dogs in results                                                                                            |
| ```cats +dogs ```           | More dogs in results                                                                                             | 
| ```cats filetype:pdf```     | PDFs about cats. Supported file types: pdf, doc(x), xls(x), ppt(x), html                                         |
| ```dogs site:example.com``` | Pages about dogs from example.com                                                                                |
| ```cats -site:example.com```| Pages about cats, excluding example.com                                                                          | 
| ```intitle:dogs ```         | Page title includes the word "dogs"                                                                              |
| ```inurl:cats ```           | Page URL includes the word "cats"                                                                                |

