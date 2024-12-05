# Sentiment Analysis and Summarizing of Book Reader Reviews

## Team details
### Aviroop Karmakar, M-Tech (AI), aviroopk@iisc.ac.in
### Hariharan N, M-Tech (DSBA), nhariharan@iisc.ac.in
### Nagaraja SB, M-Tech (DSBA), nagarajasb@iisc.ac.in

## Background of the problem
Online reviews are crucial for helping customers decide on books, with platforms like Amazon hosting millions of reviews. However, the overwhelming number of reviews makes it difficult for customers to assess the general sentiment and whether a book is worth purchasing.

## Problem statement
To build a model that can predict the sentiment (positive, negative, neutral) of book reviews.

#### Download complete original datasets from Kaggle (Since its a huge dataset of size 2.8 gb, raw datasets not uploaded in this GitHub)
https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews/data

This dataset contains 2 files namely "reviews" and "book_details",

The first file "reviews" file contain feedback about 3M user on 212404 unique books the data set is part of the Amazon review Dataset it contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 - July 2014.
and this file has these attributes

Features	          |    Description
------------------- | ---------------------
id	                |   The Id of Book
Title	              |   Book Title
Price	              |   The price of Book
User_id	            |   Id of the user who rates the book
profileName	        |   Name of the user who rates the book
review/helpfulness	|   helpfulness rating of the review, e.g. 2/3
review/score	      |   rating from 0 to 5 for the book
review/time	        |   time of given the review
review/summary	    |   the summary of a text review
review/text	        |   the full text of a review


The second file "Books Details" file contains details information about 212404 unique books it file is built by using
google books API to get details information about books it rated in the first file
and this file contains

Features	        |  Description
----------------- | -----------------
Title	            |  Book Title
Descripe	        |  decription of book
authors	          |  Neme of book authors
image	            |  url for book cover
previewLink	      |  link to access this book on google Books
publisher	        |  Name of the publisheer
publishedDate	    |  the date of publish
infoLink	        |  link to get more information about the book on google books
categories	      |  genres of books
ratingsCount	    |  averaging rating for book

Automating the sentiment analysis and providing concise summary of reviews can help customer,while predicting sales based on reviews can support authors and publishers in understanding a book's market performance
