# eParticipation2.1
What are the different methods we can do in NLP

BOSES KO APP - is an inclusive, deliberate
it uses ai to have audio to text, dialect translation, speech recogntion, etc

mandate of the org - HEI, lorma is one of the stake holders

# Introduction to NLP (Natural Language Processing)
### 1. what is NLP?
   - branch of AI that focuses on the interaction between computers and humans through natural language
   - it concerns with gathering, manipulating, storing, retrieving, classifying, and making sense, of written and spoken natural language information.
   - alternative names include:
     computational linguistics
     
### 3. NLP goals
- develop apps/computer systems that can understand human language and communicate with humans in a natural way
**  the apps.computer systems should:**
- recognize and extract meaning from the text and speech
- generate natural language responses to text and speech
- understand the context of language. like idioms and metaphors
- translate between diff lang
- extract info from unstructuired like socmed
- summarize large ammounts of texts into concise summaries
- generate contents such as stories, joke, poems, computer program, articles

  
### 4. NLP applications
   - question/ answerting chatbot systems
     Example: charlie the chatbot
   - sentiment analysis of product reviews
     example: deterrmines if review is positive/negative/in the middle
   - machine translation for travellers
     example: google translate
   - information extraction and unstructured text to database entries
     example: extract specific info, like the event in a long paragraph
   - topic modelling
     example: use to discover the topics in documents
   - virtual assistants
     example: siri, alexa, hey google
    
### 6. NLP tasks
   syntax
   - POS tagging is a process of assigning a pos or lexical class marker to each word in a sentence
   - parsing is analysing the grammatical structure of a swentence and identifying its constinuent parts
   - morphological analysis is identifying the inflectional and derivational elements of a word

     semantics
     -  named entity recogniton is to process a text and identify named entities in a sentence
     -  word sense disambiguation is the determining the correct meaning of a word based on its context
     - sentiment analysis is determing the sentiment or emotion expressed in a piece of text
     - summarization is automatically genrating a summar of texts
    
       pragmatics
       - natural language generation is usng computer algorithms to automatically genrate natural languyage text such as news articles or product descriptions
       - dialogue management systems are building sytems that can engage in natural language 
       - speech recognition
       - text summarization
         
    syntax refers to the studies of sentence structure and the rules governing how words combine to form meaningful expressions
    Semantics focuses on the study of meaning in language. it explores how words, phrases, and sentences convey information and represents concepts
    Pragmatics deals with how languae is used in context and how the 

   language modelling
   - a concept that focuses on the understanding of the structure and grammar of a sentence
   - it predicts the words
   - spelling checker
     examples:
     next word predictions
     langauge generation
     text completion
   
### 8. Role of machine learning 
machine learning plays an important role in NLP by providing algo and techniques that enables comp to learn from data and improve their performance on NLP tasks
in recent years, deep learning algo have achieved state of the art performance on many NLP tasks that require analysis of sequences

Two types of machine learning:
1. Supervised machine learning is a concept that involves teaching computers how to understand and process language by using labeled examples
   Pipeline:
   -gather data
   -extreact features
   -train models
   -model evaluaion
   -prediction
   key is to have a labeled dataset
3. Unsupervised machine learning is the concept that involves teaching compiters how to discover patterns and relationship in the language without explicit guidance or labeled examples
   - it is matrabaho
   -  it like the computer is learning without a teacher
     Pipeline:
              data preperation
              document term matrix
              train model
              interpret the topics
              result visualization

Machine learning in NLP is about teaching computers to understand human language by giving them examples, adjusting their learning settings, and then using their learning to make predictions on new data. 
### 9. challenges in NLP
data quality - domains with limited data
ambiguity - sarcasm, irony, and figurative language can be difficult for machines to understand
ethics and bias - NLP apps can perpetuate biases in data in training can them,leading to unfair and discriminatory outcomes
privacy - NLP relies on vast amounts of data which can be used to track peoples behvaior and preferences




#### Module 2
**Overview of steps involved in NLP**
data acquisition and preparation -> text preprocessing -> feature extraction and selection -> model building and training -> model development and performance evaluation.
the DATA - it provides the foundation on which NLP models learn language patterns, semantics, and context. without sufficient and diverse data, NLP models would struggle to generalize and perform effectively on various language tasks
Common data collection methods
- web scraping(scweet, beautifulsoup)
- surveys
- APIs
- Sensors and IoTs

NLP libraries - NLTK, Gensim

**Text Processing**
1. cleaning
   Regular expressions
   - a formal language specifying text strings
   - how can we search for this:
      - woodchuck
      - woodchucks
      - Woodchuck
      - Woodchucks

2. Text Normalization
   1. removal of duplicates, whitespaces, and punctuations
   2. accent removal
   3. capital letter removal
   4. removal or substitution of special characters like emoji
   5. substitution of contractions
   6. transform word numerals into numbers
   7. substitution of values for their type
   8. acronyms normalization
   9. normalize data formats, social security numbers or other data that have standard format
   10. spell correction
   11. removal of gender
   12. substitution of rare words for more common synonyms
   13. stop word removal

3. Sentence Tokenization
   also called sentence segmentation. it is the problem of dividing a string of written language into its component sentences.

4. Stop words removal
   stop words usually refers to the most common words in a language such as "and", "the" , "a".

5. parts of speech tagging
  - a sequence labeling task.
  - the process of marking up a word in a text(corpus) as corresponding to a particular part of speech (syntactic tag), based on both its definition and its context.

6. named entity recognition

7. stemming is a process which a word is reduced to its stem/root form
8. lemmatization is used to reduce words to normalized form.

Text Pre-processing 
is first step in NLP where we clean and transform raw text data to make it easier for computers to understand.



