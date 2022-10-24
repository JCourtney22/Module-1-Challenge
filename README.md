# Module-1-Challenge

For this challenge, I had the following user story to refer to so that my work was accurate and met the requirements.

### User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

### Acceptance Criteria

Your website must meet accessibility standards. You can achieve this completing the following:

* Semantic HTML elements can be found throughout the source code
* HTML elements follow a logical structure independent of styling and positioning
* Image and icon elements contain accessible `alt` attributes
* Heading attributes fall in sequential order
* Title elements contain a concise, descriptive title

I began by exploring the code to get familiar with it and then focused on individual areas as opposed to trying to focus on everything at once. This allowed me to ensure that any changes I made didn't cause further problems and to check that the CSS was still being applied correctly. Once I was happy with each change, I committed each one to allow me flexibility if I needed to revert to an older version of code. This challenge has helped me understand the importance of refactoring and accessibility. 

# Challenges 
 
 One of the first challenges I came across was identifying how to make the broken link work. I explored the document to try and identify patterns of code and I also used the inspect tool to try and locate variations in the code. I found that I couldn't identify the problem on my own so I used the internet to search how to create links that jump to specific places within a webpage. I found that I had simply overlooked the fact that CSS was being used inline and the id was being called in the link using the #and id name, however there was no id attribute associated with the call. Once I had created an appropriate id in the correct place, the link worked.

 Other challenges I had was identifying where semantic HTML elements should go. I used a HTML5 element flowchart to guide me, but I also required the use of the internet to explore each element in further detail. This is why I decided upon using header, nav, main, section and footer elements to best reflect what each element contained. I felt that it was necessary to keep one div element where the background picture was contained as I felt this did not have any specific content. I would welcome any further comments regading this to further develop my understanding.
 
 One other challenge I came across was understanding whether my CSS styling sheet followed correct semantic structure and that it was consolidated and organised appropriately. I referred to previous work, lessons and the internet to guide me on whether my changes were relective of common practice or were indeed correct. I found that commenting on each change helped me to understand my changes and to ensure that anyone looking at my code could see my reasoning for changes. 
 
 My final challenge was exploring whether the background image required something similar to an alt attribute. Researching this query on the internet taught me that there were a few ways this could be done, such as using an aria-label attribute. However, I chose the title attribute as the background image is not necessary to the overall understanding of the webpage's meaning but I wanted to still give some information for accessibility purposes.

# Things I learned

I learnt to be resilient and work in a systematic manner. I found specific ways of styling css to make it more conscise and I developed my understanding of semantic elements further.

The screenshot below shows my deployed website (https://jcourtney22.github.io/Module-1-Challenge/).

![jcourtney22 github io_Module-1-Challenge_](https://user-images.githubusercontent.com/115502589/197534815-5046c471-8dbf-416a-ac03-df3e2c8daab7.png)
 
# License
  
Please refer to the LICENSE in the repo.
