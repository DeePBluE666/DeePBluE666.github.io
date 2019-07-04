---
permalink: /award/
title: "Full Awards List"
author_profile: true
redirect_from: 
  - /md/
  - /award.html
---

>Ordinary Awards


####  National Scholarship for Postgraduates of Beijing University of Posts and Telecommunications in 2018

####  Competition Master at Kaggle

####  Excellent Undergraduate Thesis of University of Jinan


>Competition Awards

* **CIKM AnalytiCup 2018:  Cross-Language Short Text Matching**
  * Field: Deep Learning and Natural Language Processing
  * Rank: 3/1027
  * Details: 
	* The contest provide a large number of unlabeled English corpus, marked Spanish corpus and corresponding English translation. The task is to determine whether the given two Spanish languages contain similar semantics.
    * Unlabeled corpus is used to train word2vec, and TF-IDF statistics is used to modify the weight of word vectors to make full use of English unlabeled corpus.
    * Building a multi-task learning model, to process Spanish and English at the same time. The performance of semantic similarity judgment is significant improved by partially sharing parameters and LSTM layer.

	
* **IJCAI 2018:  Click Transformation Rate Prediction**
  * Field: Machine Learning and Data Mining 
  * Rank: 5/5024(Top 0.1%)
  * Details: 
	* The context provide users’ search and click records and predicts what they will buy on promotional day.
    * Building a purchasing in ordinary time period based on a large number of handcrafted features.
    * Perform transfer learning to predict the results of the above models are taken as the features of the promotional day, to significant improves the performance of the models.	
	

* **KDD2018:  Weather Prediction**
  * Field: Deep Learning and Data Mining 
  * Rank: 7/4170(Top 0.2%)
  * Details: 
	* The competition provides the weather data about Beijing and London over the past few weeks, the task is to predict the weather conditions of the two cities in the future.
    * Using LSTM and CapsuleNet hybrid model and stacking ensemble model to build a weather forecasting system.	


* **Kaggle:  TGS Salt Identification Challenge**
  * Field: Deep Learning and Computer Vision 
  * Rank: 10/3234(Gold Medal)
  * Details: 
	* The context require to build an algorithm that automatically and accurately identifies if a subsurface target is salt.
    * Using different data argumentation techniques.	
	* Built a U-net with ResNet Blocks model to solve the problem.

* **Tianchi:  Medical Knowledge Graph Challenge**
  * Field: Deep Learning and Natural Language Processing 
  * Rank: 2/1029
  * Details: 
	* The context given a large number of corpus in medical field and require the contestants to build the knowledge graph, obtains the entities from the corpus, and extracts the relationship between entities.
    * Established a joint training model of entity recognition and relation extraction to solved simultaneously.	
	* The BIO information of entities is introduced to the relation extraction model, which greatly improves the performance of the model.	
	* Obtain dynamic entity vectors through entity vector pre-training model, similar to language model.


	
	
## 
* Basic config options: _config.yml
* Top navigation bar config: _data/navigation.yml
* Single pages: _pages/
* Collections of pages are .md or .html files in:
  * _publications/
  * _portfolio/
  * _posts/
  * _teaching/
  * _talks/
* Footer: _includes/footer.html
* Static files (like PDFs): /files/
* Profile image (can set in _config.yml): images/profile.png

## Tips and hints

* Name a file ".md" to have it render in markdown, name it ".html" to render in HTML.
* Go to the [commit list](https://github.com/academicpages/academicpages.github.io/commits/master) (on your repo) to find the last version Github built with Jekyll. 
  * Green check: successful build
  * Orange circle: building
  * Red X: error
  * No icon: not built

## Resources
 * [Liquid syntax guide](https://shopify.github.io/liquid/tags/control-flow/)

## Markdown guide

### Header three

#### Header four

##### Header five

###### Header six

## Blockquotes

Single line blockquote:

> Quotes are cool.

## Tables

### Table 1

| Entry            | Item   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| [John Doe](#)    | 2016   | Description of the item in the list                          |
| [Jane Doe](#)    | 2019   | Description of the item in the list                          |
| [Doe Doe](#)     | 2022   | Description of the item in the list                          |

### Table 2

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|-----------------------------|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=============================|
| Foot1   | Foot2   | Foot3   |

## Definition Lists

Definition List Title
:   Definition list division.

Startup
:   A startup company or startup is a company or temporary organization designed to search for a repeatable and scalable business model.

#dowork
:   Coined by Rob Dyrdek and his personal body guard Christopher "Big Black" Boykins, "Do Work" works as a self motivator, to motivating your friends.

Do It Live
:   I'll let Bill O'Reilly [explain](https://www.youtube.com/watch?v=O_HyZ5aW76c "We'll Do It Live") this one.

## Unordered Lists (Nested)

  * List item one 
      * List item one 
          * List item one
          * List item two
          * List item three
          * List item four
      * List item two
      * List item three
      * List item four
  * List item two
  * List item three
  * List item four

## Ordered List (Nested)

  1. List item one 
      1. List item one 
          1. List item one
          2. List item two
          3. List item three
          4. List item four
      2. List item two
      3. List item three
      4. List item four
  2. List item two
  3. List item three
  4. List item four

## Buttons

Make any link standout more when applying the `.btn` class.

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}

## HTML Tags

### Address Tag

<address>
  1 Infinite Loop<br /> Cupertino, CA 95014<br /> United States
</address>

### Anchor Tag (aka. Link)

This is an example of a [link](http://github.com "Github").

### Abbreviation Tag

The abbreviation CSS stands for "Cascading Style Sheets".

*[CSS]: Cascading Style Sheets

### Cite Tag

"Code is poetry." ---<cite>Automattic</cite>

### Code Tag

You will learn later on in these tests that `word-wrap: break-word;` will be your best friend.

### Strike Tag

This tag will let you <strike>strikeout text</strike>.

### Emphasize Tag

The emphasize tag should _italicize_ text.

### Insert Tag

This tag should denote <ins>inserted</ins> text.

### Keyboard Tag

This scarcely known tag emulates <kbd>keyboard text</kbd>, which is usually styled like the `<code>` tag.

### Preformatted Tag

This tag styles large blocks of code.

<pre>
.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}
</pre>

### Quote Tag

<q>Developers, developers, developers&#8230;</q> &#8211;Steve Ballmer

### Strong Tag

This tag shows **bold text**.

### Subscript Tag

Getting our science styling on with H<sub>2</sub>O, which should push the "2" down.

### Superscript Tag

Still sticking with science and Isaac Newton's E = MC<sup>2</sup>, which should lift the 2 up.

### Variable Tag

This allows you to denote <var>variables</var>.
