# Week Six

For this week, I chose data from the digitial transgender archive, where I analyzed clippings from the chosen topic of 'Military' from within the archive. The time period of these military clippings  were from the year 1890 to 2020.

The selected clips totalled around 30 documents. I then opened the apppliation for cleaning of these jpeg files. The downloaded pictures were then OCRed into txt files.

I followed the OCR process from Week 2, the process is fairly simple after attempting it several times from previous weeks. 

With the txt files extracted from the jpeg files, we now had to clean up this raw data with REGEX in Sublime Text. We mainly had to get rid of unwanted symbols such as /, |, $ and #. Some of these symboles were placed there during the OCR process. 

The format was messed up on some of text files so they had to be fixed as well. To get rid of some of the symbols, I used the Find & Replace tool on Sublime Text. 

  - Find: (.+\<to\>)
  - Replace
  
  - We replace the 'to' in 'Find' with the symbol we are searching for, then delete the unwanted symboles much easier.


![screenshot](s2.png)



it was now time to insert these text files into Voyant Tools to get a more visual and comprehensive look at our data.


![screenshot](ss-3.png)

