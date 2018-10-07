<!-- .slide: data-background="images/network-background.jpg" class="background" -->

<h2>Best Practices of AI in Business</h2>
<h4>The Institute for Ethical AI & ML</h4>
<p>
  <br />
  <br />
    Alejandro Saucedo <br/><br/>
    <a href="http://twitter.com/AxSaucedo">@AxSaucedo</a><br/>
    <a href="http://linkedin.com/in/AxSaucedo">in/axsaucedo</a><br/>
  <br />
</p>
<p>

[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background" -->


<h2>Best Practices of AI in Business</h2>
<h4>The Institute for Ethical AI & ML</h4>

<table class="bio-table">
  <tr>
    <td style="float: left">
        ![portrait](images/alejandro.jpg)
        <br>
        <font style="font-weight: bold; color: white">Alejandro Saucedo</font>
        <br>
        <br>
    </td>
    <td style="float: left; color: white; font-size: 0.7em;">

        <br>
        Chairman
        <br>
        <a style="color: cyan" href="http://ethical.institute">The Institute for Ethical AI & ML</a>
        <br>
        <br>
        AI Fellow / Member
        <br>
        <a style="color: cyan" href="#">The RSA & EU AI Alliance</a>
        <br>
        <br>
        Advisor
        <br>
        <a style="color: cyan" href="http://teensinai.com">TeensInAI.com initiative</a>
        <br>
        <br>
        Chief Engineer
        <br>
        <a style="color: cyan" href="http://eigentech.com">Exponential Technologies</a>
        <br>
        <br>
        
    </td>
  </tr>
  <tr>
  </tr>
</table>


[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background smallquote" -->

#### The Institute for Ethical AI & ML
<iframe style="height: 50vh; width: 100vw" src="http://ethical.institute"></iframe>
#### <a href="http://ethical.institute">http://ethical.institute</a>

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## IEML phased rollout plan
* **Phase 1 - Ethical ML by pledge**
    * Commit as a technology leader<br><br>
* **Phase 2 - Ethical ML by process**
    * Implement the internal processes to your workplace<br><br>
* **Phase 3 - Ethical ML by certification**
    * Obtain the certifications required<br><br>
* **Phase 4 - Ethical ML by regulation**
    * Implement policy based on case-studies


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## Moral-consciousness matrix

| | | |
| - | - | - |
| | Conscious | Unconscious | 
| Moral | ✅ | ❌ |
| Immoral | ❌ | ❌ |
| | | |


<br>

### People can be <font color="#00ffda">conscious</font> and <font color="#00ffda">moral</font>




[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background smallquote" -->

## A practical framework for Ethical ML

> AI/ML Recap
> <br>
> <br>
> Opportunities & Risks
>
> Ethics by design
> 
> Next steps!


[NEXT]
<!-- .slide: data-background="images/particles.gif" class="background smallquote" -->

# #LetsDoThis



[NEXT SECTION]
<!-- .slide: data-background="images/parti.png" class="background smallquote" style="color: white" -->

# 1. Core concepts

[NEXT]
<!-- .slide: data-background="images/parti.png" class="background smallquote" style="color: white" -->

## A. Karpathy Software 2.0 (ML)

1) We specify some goal on the behavior of a desirable program (instead of coding it)
```
(e.g., “satisfy a dataset of input-output pairs of examples,” 
or, “win a game of Go”)
```
2) write a rough skeleton of the code
```
(e.g., a neural net architecture) that identifies a 
subset of program space to search, 
```
3) use the computational resources at our disposal to search this space for a program that works.


[NEXT]
<!-- .slide: data-background="images/parti.png" class="background smallquote" style="color: white" -->

## The core principles:
* Explainability
* Reproducibility
* Monitoring 
* Compliance


[NEXT]
<!-- .slide: data-background="images/parti.png" class="background smallquote" style="color: white" -->

## Data Scientists 
In charge of development of models

## Data Engineers 
In charge of development of data pipelines

## DataOps / ML Engineers
In charge of productionisation of models, data pipelines & products


[NEXT SECTION]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

# 2. Best Practices in Industry

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## 1. Ensure augmented (as opposed to artificial)


<div class="left-col">

<h3>Bad</h3>
Using predictions without checks

<br>
<br>

<h3>Better</h3>
Ensure human sign-off process

</div>
<div class="right-col">

![line](images/robotfall.gif)

</div>

_note_
### Bad
Have the system automatically going through all records taking the first-hand predictions without signoff on lower confidence fields

### Better
Ensure there is a process for a human signoff based on predictions and have a process for low confidence fields


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## 2. Awareness of bias in data and models

<div class="left-col">

<h3>Bad</h3>
Train on ALL data

<br>
<br>

<h3>Better</h3>
Understand bias to avoid discrimination

</div>
<div class="right-col">

![line](images/duck.gif)

</div>

_note_

### Bad
Train the dataset on all previous cases and assume it works well

### Better
Run in-depth analysis of distribution of data based on traits to ensure the model does not discriminate unfairly

[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## 3. Address job displacement implications

<div class="left-col">

<h3>Bad</h3>
Push for automation unconsciously

<br>
<br>

<h3>Better</h3>
Understand and address automation implications

</div>
<div class="right-col">

![line](images/robot.gif)

</div>

_note_

### Bad
Push for automation without taking into consideration the implications of job automation

### Better
Understand the implication of both automating the process and reducing the costs for the service (which may lead to total increase in demand)


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## 4. Practical understanding on accuracy


<div class="left-col">

<h3>Bad</h3>
Take naive accuracy number and aim to increase

<br>
<br>

<h3>Better</h3>
Have an objective, consistent and transparency metric for accuracy

</div>
<div class="right-col">

![line](images/dog.gif)

</div>

_note_
### Bad
Take percentage accuracy increases as face-value and assume a higher number is better

### Better
Ensure you run consistent cross-validated and bias-reduced sets of tests/simulations to ensure that accuracy increase is objective


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## 5. Awareness and plan for audit trail

<div class="left-col">

<h3>Bad</h3>
Override models and save hardcoded answers

<br>
<br>

<h3>Better</h3>
Store labelled data and changelog of work

</div>
<div class="right-col">

![line](images/laptop.gif)

</div>

_note_

### Bad
Don't store the models together with its respective metadata which doesn't allow for transparency and audit trail

### Better
Ensure that models are stored with traceable labels used, as well as an abstracted set of the features 



[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## 6. Backwards compatibility and versioning

<div class="left-col">

<h3>Bad</h3>
Assume previous models won't be re-used 

<br>
<br>

<h3>Better</h3>
Have a process to ensure backwards compatibility of features

</div>
<div class="right-col">

![line](images/lego.gif)

</div>

_note_
none


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## 7. Transparency on data/meta-data collection and usage

<div class="left-col">

<h3>Bad</h3>
Assume stakeholders understand data usage

<br>
<br>

<h3>Better</h3>
Provide comprehensible and transparent overview of storage, ownership and usage of the data/meta-data

</div>
<div class="right-col">

![line](images/pie.gif)

</div>

_note_
none


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

## 8. Identify and address cybersecurity risks

<div class="left-col">

<h3>Bad</h3>
Assume there isn't a need to protect models 

<br>
<br>

<h3>Better</h3>
Identify and address threats for tricking, circumventing or hacking mathematical models created

</div>
<div class="right-col">

<img height=400px src="images/hacking.gif">

</div>

_note_
none


[NEXT]
<!-- .slide: data-background="images/partistat.png" class="background smallquote" style="color: white" -->

# Next steps

Applying this thinking into your actual projects 

## #LetsDoThis


[NEXT SECTION]
<!-- .slide: data-background="images/spaceline.jpg" class="background smallest" style="color: white" -->
# 4. Final words

[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background smallquote" -->

## Today we covered

> AI/ML Recap
> <br>
> <br>
> Opportunities & Risks
>
> Ethics by design
> 
> Next steps!

[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background" -->
### Code
https://github.com/axsauze/apc-2018-privacy-conference

### Slides
https://axsauze.github.io/apc-2018-privacy-conference


[NEXT]
<!-- .slide: data-background="images/network-background.jpg" class="background" -->

<h2>Best Practices of AI in Business</h2>
<h4>The Institute for Ethical AI & ML</h4>

<table class="bio-table">
  <tr>
    <td style="float: left">
        ![portrait](images/alejandro.jpg)
        <br>
        <font style="font-weight: bold; color: white">Alejandro Saucedo</font>
        <br>
        <br>
    </td>
    <td style="float: left; color: white; font-size: 0.7em;">

        <br>
        Chairman
        <br>
        <a style="color: cyan" href="http://ethical.institute">The Institute for Ethical AI & ML</a>
        <br>
        <br>
        AI Fellow / Member
        <br>
        <a style="color: cyan" href="#">The RSA & EU AI Alliance</a>
        <br>
        <br>
        Advisor
        <br>
        <a style="color: cyan" href="http://teensinai.com">TeensInAI.com initiative</a>
        <br>
        <br>
        Chief Engineer
        <br>
        <a style="color: cyan" href="http://eigentech.com">Exponential Technologies</a>
        <br>
        <br>
        
    </td>
  </tr>
  <tr>
  </tr>
</table>


