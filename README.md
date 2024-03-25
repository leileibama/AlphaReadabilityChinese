# AlphaReadabilityChinese 1.0

- AlphaReadabilityChinese 1.0 is a tool that calculates the readability of Chinese texts, which includes indices at lexical, syntactic, and semantic levels.

## **_Download_**

Download AlphaReadabilityChinese 1.0 for MS Windows and MacOS at:

https://github.com/leileibama/AlphaReadabilityChinese/releases/tag/AlphaReadabilityChinese

## **_AlphaReadabilityChinese_**

Hi all,

Happy to release our new app, AlphaReadabilityChinese (or the ARC Chinese) 1.0. 

The ARC Chinese is a tool that calculates the readability of Chinese texts, which includes indices at lexical, syntactic, and semantic levels. 

The ARC Chinese provides versions working on both MS Windows and Mac OS. It is free to use the ARC Chinese. It is very much appreciated if you cite our work as follows when you use the ARC Chinese.

- Lei, Lei, Wei, Yaoyu, & Liu, Kanglong. 2024. AlphaReadabilityChinese: A tool for the measurement of readability in Chinese texts and its applications. _Foreign Languages and Their Teaching_. _46_(1):83-93. (in Chinese)
- or 雷蕾, 韦瑶瑜, 刘康龙. 2024. AlphaReadabilityChinese：汉语文本可读性工具开发与应用. 外语与外语教学. _46_(1):83-93.

You can also find detailed information of the ARC Chinese in the foregoing article. 

The ARC Chinese is designed and developed by Lei Lei (雷蕾) and Tingyu Zhang (张婷玉), Shanghai International Studies University.

Hope the ARC Chinese helps. Comments and suggestions are welcome! (leileicnATqqDOTcom)

******************************************

## **_Guidelines for Users_**

1. Put all the texts you are going to process in a folder (such as "my_test_files", the test folder that we provide and that contains five abstracts of our articles). Note that all texts should be in the .txt format with the encoding 'UTF-8'.

2. Open the ARC Chinese.

3. Click "Select" besides "Input folder" to select the folder (such as the folder "my_test_files") that contains the files you are going to calculate the readability of. 

3. Click "Select" besides "Output folder" to select the folder where you would like the resulting file is stored. The resulting file contains the results of the readability measures in a .csv format. 

4. Click "Run". When the ARC Chinese says "Processing ends", find the newly generated resulting file entitled "0ARC_Chinese_Results.csv". 

5. Open the resulting file with your spreadsheet app such as MS Office Excel or Numbers on Mac OS and check out the readability measures of all texts in the Input Folder.

## **_Known issues_**

On MacOS, if you encounter the "App is damaged and can't be opened" error, 1) copy AlphaReadabilityChinese.app to the Applications folder, 2) go to Terminal and type/run the following, and 3) reopen AlphaReadabilityChinese.app. 

`sudo xattr -cr /Applications/AlphaReadabilityChinese.app`

or

`sudo xattr -r -d com.apple.quarantine /Applications/AlphaReadabilityChinese.app`

## **_Note_**

Note that it may take a while (approximately 30 seconds on my MacBook) the first time we open AlphaReadabilityChinese when it loads many models behind. The good news is that it works highly efficiently to process our data after all the models are loaded. 


