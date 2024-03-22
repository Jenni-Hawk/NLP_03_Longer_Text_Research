# Advanced Topic Modeling Research: Open Ended Survey Responses

## 📖 Background:
After conducting the [tweet research project](https://github.com/Jenni-Hawk/Advanced_Topic_Modeling_1_Tweets/blob/main/README.md) I was compelled to go further. I wanted to see how advances in technology could change the way traditional consumer research is thought about and conducted. One area of consumer research that hasn't been reconsidered is the survey. In particular, I wanted to look at open ended questions (questions that allow peoople to say whatever they want). I wanted to defy the long-held conventions that consumer researchers held about the open-end and push the limits of BERTopic in regards to text length. 

At the same time, I wanted to go deeper on the technology: deeper on BERTopic parameter testing, deeper on sentence transformer testing, deeper on LLMs. I wanted a deeper understanding of the impact of each of these and the the role they have on shaping the output. 

I went about this project from both a consumer researcher and a data science researcher mindset. 

My data science brain explored solutions, and then I used my consumer researcher brain to evaluate the output to ensure it was delivering the value I needed as a consumer researcher. Does the algorithm and resulting output solve the challenges that consumer researchers have? Does it do a better job than a human without the assist of modern AI technology?  

## 🎯 Business Objectives: 
- Determine if the conventional thinking around open ended survey questions can be defied using modern AI technology, thus, leading to more learning achieved more quickly.
- Can long responses of open ended questions be quickly and accurately categorized and labeled in a way that is better than human-only analysis?
- How do custom algorithms compare to the consumer version of ChatGPT? (ChatGPT is the top-of-mind, accessible, pop culture tool that a professional would consider.)
  
  ### Conventions of Open Ended Survey Questions:
    - Don't ask big lifestyle questions because they take too much time to analyze by humans. Traditional researchers reserve these questions for qualitative research studies like focus groups or interviews.
    - Limit number of words in the response so that it's easier for humans to analyze
    - It takes too long to analyze, therefore, responses to open-ended questions usually sit around without being analyzed, or the open ended question isn't utilized at all.

## 🎯 Technical Objectives: 
- How far can BERtopic, tested with different sentence transformers and LLMs, be pushed to accurately categorize and label long text responses?
- How can a custom algorithm compare to the consumer version of ChatGPT? This is the AI tool in the consumer researcher consideration space. 

## 🔍 Findings: Handling Long Text
- When compared to manual human process, BERTopic is much more efficient at categorizing and labeling multiple sentence and multiple paragraph documents. It does require a lot of experimentation that results in specific BERTopic parameters (special focus on HDBSCAN and UMAP), sentence transformer experimentation, LLM experimentation and some EDA around the type of language being analyzed (inattentive vs attentive)
- It's also important to trust the outliers, HDBSCAN and UMAP does a good job. My process in reviewing output from the experiments was to turn off the data science brain and activate  the language arts brain.  
- From a consumer researcher perspective, I said to myself "This is really good. I can really deliver a lot of value to my clients with this."
- One area that I think it really helps with, when comparing to human process, is time spent overthinking. An algorithm doesn't spend a lot of time debating what category a long piece piece of content belongs to. It just makes a decision and in this experiment it's pretty good. It gets us farther than we would on our own.  While at times BERTopic is challenged in categorizing a piece of content with two ideas, it's kind of amazing what it can still do with long text. 
- I'm working on more optimization as I write this to get the algorithm from really good to great. 
