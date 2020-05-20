# **Edx research**

## **Mod 1:**

### **Goals of research:**

research = developing question actively with analysis.

design a project = research = choose variable vs data science = fixed variables

dynamic, iterative problem solving

process(water leaking):

1. frame     the question (where the water coming from)
2. form     a theory (bathroom is up stairs)
3. form     a hypothesis (testable statement )
4. design     a experiment / study and test
5. draw     conclusions : repeat as necessary
6. final     conclusion

 

### Goals of research part 2:

2 type of research:

1. **basic research**: the goal is     just know why does it work. try to understands it. by collecting initial     data. explain why some behavior and predict the results. it's not     necessary to test everything because you know how it works
2. **applied research:** a way to test     assumption. it worth testing things before deployment. testing with     sample. this allows you to stand on firm ground because you have proof.



## **The circle of science:** 

research process as circle of science. it is a problem solving process. 

imagine marketing of a company, some green products with good features but not selling. 

1. develop     a theory (people want to feel green but don't want to cost more)
2. build     a hypothesis (express positive attitude, but they choose familiar brand,     they feel green by showing attitude and they don't need to buy it) 

a lot of people don't have insight of their actual preferences and they don't tell you the truth.

1. data     collection ( making a survey with AB test, that directly connected with     theory and hypothesis)
2. descriptive     statistics. data science stuff , (is my hypothesis supported in     sample?what patterns I see?)



1. inferential     statistics (deleting "chance" as an explanation and proof with     generalization)
2. draw     conclusions (implications from theory and methods) 

and that is the circle of science

## clarifying question

every body who has input on survey want to add a piece. we often has to attack a question in depth. not directly ask that you need to know, test in indirectly. but we shouldn't make it too indirect and shallow

narrow your question(uncover question behind question ): why campaign doesn't work? but the question is why green products doesn't sell.

try answer one question and focus on it. 

research foxtrot.

1. look     at the proposed design 
2. formalize     that 
3. identify     focused several lines of attack (hypothesis) (different ways of asking the     question)
4. develop     study / survey around those



## **The psychology of providing data 1:**

we want a design a survey. we can trust people of robots of true information givers. the last thing that we want to not trust our data. 

people are biased. we need to understand the psychology. they are influenced by design decision. 

### **impression management:** 

they wanna find the good answer because they don't want to judge you. they want to look good to they self. you should design it, that not loaded with a idea that there is a right answer.

### **demand characteristic** 

e.g. : purpose of study is to test how great our logo is. here is our logo. do you like our logo?(y/n)

they have hard time to say no because of how question asked. 

ask in a disguise call logo a graphic. they don't' get good answer because they want to be polite . 

- people can tell what answer your looking for
- will cooperate/sabotage (even subconscious)
- solution = sound objective 



**The psychology of providing data 2:**

knowing mote than we can tell

- people don't know **why** they do things and will **make up** answers when     asked (the scarf picking example) (avoid why questions)
- avoid complex questions.
- goal = simplicity + knowability ( having a gut answer)

## **The psychology of providing data 3:**

#### **placebo effect**

- beliefs matter 
- e.g. products are **more effective** when people think they are. (the     expensive energy drink)
- manage expectation. 

**biases** don't overdo advertise on survey 

- observe bias: see what you want to see 
- observe effect: act differently when observed 

solution = blinding 

- neither participant nor people collecting the data should know what to     expect 
- age priming example : don't use "elderly words"

keep every one naïve to get the objective answer 

## **MOD2: planning for analysis**

**sample vs population**

samples only give you error-prone guesses at reality!

sample : 

question : discover % of customers willing to try a new product 

answer : 30 %

sampling error = one sample is not trust worthy . they are effected with error 

the larger my sample = the more trust worthy

standard error = standard deviation 

**Null hypothesis**

it says, the findings are due to chance.

effect/ relationship = zero in population

nonzero finding in sample = due to random chance 

**alternative hypothesis** = effect is not zero in population 

**discredit the null hypothesis / p-values** 

p-value = p(data | Null = True) : probability of getting a result THIS BIG if the results were due to chance. 

large : result easily produced by chance 

small =result **not** easily produced by chance 

p-value is the test of null hypothesis is true or not 

if our result is **not** easily **produced by chance**, we reject chance as a explanation.

statistically "significant" means a low p-value 

p < 0.05 => reject null hypothesis

**discredit the null hypothesis / confidence intervals = CI = 95% CI** 

it tells you what data is in contrast of p-value that says your result is just not due to chance 

gives a windows if confidence. it keeps us from mental bias. 



**Power of sampling size and planning**

**power part 1:**

how much data is enough? 

- scenario     1 : people who have more experience have better surveys.

- - based      on 20 people per group

- scenario     2 

- - based      on 40,000 people per group

which is better?

POWER!

- ability     to to find sth. 
- % of     time an effect will be detected (p <5%)

a study with 20% power, 80 percent of time we cannot reject null hypothesis

what do you need have to good power : 

1. effect     size (bigger = easier to detect)

2. - but      there are a lot of small effects that are really important, what we      should do about them? see number 2. 

3. sample     size (larger = more power) 

 

- common     situation1: 
  - set      desired power to 80%
  - set      minimum population effect sot for which you want that power (SESOI)
  - power      calculation tells you required sample size
- common     situation 2:
  - power      80%
  - sample      size is fixed 
  - power      calculation tells you the smallest population effect size for which you      would have that power 

you always need large effect with small sample **or** small effect with large sample, or you will have trouble!



**Effect size(power part 2):**

- Cohen's d(ifference) : it will give you a     unit free metric (sth like std deviation)

- - "size      of difference in standard deviations" 
  - 0      - 0.2 = trivial 
  - 0.2      - 0.5 = small
  - 0.5      - 0.8 = medium 
  - \>      0.8 = large 

- correlation     : r

- - 0      - 0.1 = trivia 
  - 0.1      - 0.3 = small
  - 0.3      - 0.5 = medium
  - \>0.5      = large 

- r =     d/ sqrt(d^2 +4) 

- d =     2r / sqrt(1-r^2)

they simply gives you the same thing. 

**examples** : (height in inches(male/female) 

effect size = 1.85 (very large effect)

required n = 12 ( 6 per group) 

**example** (number of shoe pairs owned (male/female)

effect size = 1.07 (large effect)

required n =30 (15 per group)

**example** = weight in pounds (male / female)

effect size : 0.59 (medium)

required n=92(46per group)

**example** = dying from smoking-related illness (smoker : yes/no)

effect size = 0.33 (small)

required n = 288 (144 per group) 

we need exponentially bigger sample when the effect size is getting smaller

**example :** # of planets you can correctly name (prefer: science/art)

effect size = 0.07 (very small trivia)

required n =7330 ( 3500 per group)

 

**sample size planning:**

power rules:

your intuition about sample size is wrong

 
