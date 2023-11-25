# Welcome to My Mr Clean
***

## Task
The problem here is that the database and the API of EncyclEarthpedia
messed up for a week and we can't acces any articles. 

The challenge is to build a simple model to extract meaningful and 
useable content from wikipedia article.

## Description
To solve the problem we write a series of function that perform the 
following tasks: 
`get_content(article_name)`: this function take the name of the article 
we want to work on , as parameter and send a get request to wikipedia to 
retrieve information about the article. It's those informmations that are 
returning by the function.

`merge_content(data)`: It takes the informations returning by the fisrt 
function as parameter. The task of this function is to clean up the data 
by removing all tyhe flourish like markups, urls and useless words or characters.
It return a clean(readble) string 

`tokenize(content)`:This function take the clean content and create a list 
of all the words containing in the clean content. 

`lower_collection(collection)`: This function update all the words 
to be in lower characters

`count_frequency(collection)`: The task performed by this function is to count 
the number of occurence of each word of the list of words
`print_most_frequent(frequencies,n)`: To print the n most frequent words along with thier count_frequency
`plot_most_frequent(frequencie,n)`: To visualizethe n most frequent words by plotting 
them in a histogram . It uses matplotlib library to perform his work
`remove_stop_words`


## Installation
To install and use the project in your machine you need to download the notebook 
file and open it in Jupyter notebook
## Usage
Give the article name to the first function as parameter as follow:
`get_content("Ozone layers")`
and execute the code in the function cell by clicking : ctrl+enter

### DJIDONOU Judicael & Olujimi Olukunle


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
