# Horiseon Optimization - Module 1 Assignment

## What I did:  
* I optimized the html language to adhere to semantic styling properties. Instead of `<div>`, I added elements such as `<header>`, `<footer>`, `<section>`, and `<article>` to create a more congruent flow and add more details about the sections from which I was working.  
* In doing this, I needed to go into the CSS and provide additional changes to ensure all styling properties were correctly applied.    
* Any images that did not have an alt value were given one with a descriptive tag.    
* The title is now more applicable to the website and less vague.    
* One of the links was not working properly, so I made sure that the coding included elements that allowed the links to go to the appropriate area of the page. I also added smooth scrolling within the CSS for a nicer flow.   

## HTML Examples   
> Before:   
>> `<div class="header">`   
>> `<div class="content">`   
>> `<h1>Hori<span class="seo">seo</span>n</h1>`   

> After:   
>> `<header>`   
>> `<section class="content">`   
>> `<h1>Hori<em>seo</em>n</h1>`   

## CSS Examples
> Before:   
>> .header {   
    padding: 20px;   
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;   
    background-color: #2a607c;   
    color: #ffffff;   
}

>> .header h1 {   
    display: inline-block;   
    font-size: 48px;   
}   

>> .header h1 .seo {   
    color: #d9dcd6;   
}   

> After:    
>> header {    
    padding: 20px;   
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;   
    background-color: #2a607c;   
    color: #ffffff;   
}    
>>header h1 {   
    display: inline-block;   
    font-size: 48px;   
}       
>>em {   
    color: #a8aaa6;   
    font-style: normal;   
}    

This formatting provided a clearer idea of what each section included.

## Mockup    
![alt text](./Mockup.png "Mockup")