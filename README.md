
# Helmet Detection

## Introduction to Object Detection:

Object detection is a computer technology related to computer vision and image processing that deals with detecting instances of semantic objects of a certain class (such as humans, buildings, or cars) in digital images and videos. Object detection algorithms typically leverage machine learning or deep learning to produce meaningful results. The goal of object detection is to detect and classify objects within an image, and to locate the position of the objects within the image.

Object detection is important for a variety of reasons. For example, detecting the bikers who are wearing helmets or not wearing. Some potential benefits of helmet detection include:

1.Improved safety: By detecting whether or not a person is wearing a helmet, safety systems can alert the user or take corrective action if necessary. This could be particularly useful in industries with a high risk of head injuries, such as construction or cycling.

2.Enhanced compliance: In industries or situations where helmet use is required by law or regulation, helmet detection can be used to ensure compliance.

3.Increased efficiency: In some cases, helmet detection can be used to automate tasks or processes that require the presence or absence of a helmet. For example, a helmet detection system could be used to control access to a construction site or to trigger the start of a manufacturing process.

------

## Object Detection Using Deep Learning:
We can use a variety of techniques to perform object detection. Popular deep learning–based approaches using convolutional neural networks (CNNs), such as R-CNN and YOLO, automatically learn to detect objects within images. One of the most famous families of Deep Convolutional Neural Networks (DNN) for object detection is the YOLO (You Only Look Once).

![alt text](https://github.com/matapan3070/matapan3070.github.io/blob/main/doc/assets/211398429-5834ac83-b39a-4647-8686-ea73609644e2.png "Logo Title Text 1")

------


### Problem:
The problem of people not using helmet while driving has caused the increase in number of accidents therefore it is necessary to solve the problem and this can be solved by using machine learning to detect the helmets of the riders both considering the bike riders and bycycle riders. The problem is solved by the method of implementation of CNN layered technique.

### Data:

The data was custom made by collecting the images from internet using the online repositories. The data had the diversity and variation to detect any possible kind of scenario of person wearing helment. The data consisted of two classes of person riding the bike and bycycles with helmet and without helmet. The custom object detection dataset (image & bounding box text file) can be accessed from this link: https://drive.google.com/file/d/1hxUF7z20tghwRWZiHh7j7qm_uti-030y/view?usp=share_link

### Method:

Yolo is the most widely used machine learning algorithm for the detection and prediction applications. This project consists of the custom dataset and the annotations were carried out using labalimg toolbox. This model is specifically designed in a manner to detect the bounding boxes for the training and the training of the bounding boxes resulted in prediction of the helmets/no helmets in the project. The bounding boxes of the images were created using the Labelimg toolbox. The dataset used for the project consists of the custom image dataset.

------

## Architecture of the implemented technique can be seen as:


![alt text](https://github.com/matapan3070/matapan3070.github.io/blob/main/doc/assets/210938172-11ecd036-b0e1-4516-b488-f8acc11ea384.png "Architecture of the implemented technique")

### Results:

The results of the given system for a video can be seen as below:




##Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~



##List


1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses



##Link

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com



##image


Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"



##Highlight

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

var s = "JavaScript syntax highlighting";
alert(s);

s = "Python syntax highlighting"
print s


##footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
    
    
    
    ##tables
    
    Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


##blockcode

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 



##html

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>



##videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>



