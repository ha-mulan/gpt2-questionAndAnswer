
# GPT2 questionAndAnswer
[![Run on Ainize](https://ainize.ai/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=https://github.com/ha-mulan/gpt2-questionAndAnswer)


### Model information


    Base model: gpt-2 large
    Epoch: 23
    Loss: 0.628
    Dataset:Question-Answer Dataset (https://www.kaggle.com/rtatman/questionanswer-dataset)
    License: CC BY-SA 3.0



### About
	this model is based on gpt2-large and fine tuned with question answer dataset.
	it generates information about your input keyword.
	first, input your keyword that you want to ask
	second, wait for result
	
### How to use

	three ways to use Gpt2 Question and answer
    	1.  CLI
    	2.  Swagger
    	3.  Demo

### GET parameter

    keyword: input your keyword that you want to ask


### Output format

    generated text


##  *With CLI*

### Input example

    curl -X GET "https://master-gpt2-question-and-answer-ha-mulan.endpoint.ainize.ai/api/?keyword=kangaroo" -H "accept: string"


### Output example
	kangaroo
	kangaroo is a modern macropus rufus and the only extant representative of the family macropodidae kangaroos have large curved claws to help them clamber onto trees
	
	
	kangaroos have been featured on coins as well as a mascot for australias australian currency  the kangaroo is also the symbol for the australian koala foundation  the foundation is a not for profit charity which aims to protect the koala from extinction
	
	kangaroos have also inspired the mascot for melbourne city council  the kangaroo is featured on the citys coat of arms as well as its official logo and periodic reviews
	
	today kangaroos are widely regarded as a vulnerable species needing immediate protection they are classified as vulnerable by the iucn and the united nations environmental program unep china  unep is the conservation division of the peoples republic of china responsible for the survival of the world population of the kangaroo
	
	the word kangaroo derives from the guugu yimidhirr word gangurru referring to a grey kangaroo  etymology of mammal names    rufus was the first western language to use the word kangaroo  thus the first people to describe an animal as kangaroo may have merely described a grey kangaroo  however research suggests that the actual name corresponds to the indian melangaroo gemell

    

       


## *With swagger*

API page: [Ainize](https://ainize.ai/ha-mulan/gpt2-questionAndAnswer?branch=master)

## *With a Demo*

Demo page: [End-point](https://master-gpt2-question-and-answer-ha-mulan.endpoint.ainize.ai)
