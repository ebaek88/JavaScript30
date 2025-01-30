# JavaScript Drum Kit   
The final result can be viewed [here]().   

I have implemented a Javascript Drum Kit based on [Wes Bos' lecture](https://youtu.be/VuN8qwZoego?si=7ChdwIjjAfftQKkn).   
However, I refactored some parts of the code to comply with the current best practice.
   
First, instead of using the deprecated [KeyboardEvent.keyCode](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/keyCode), I have used [KeyboardEvent.code](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent/code).   
   
Second, instead of using classList.add, I have used classList.toggle in order to remove the class ".playing" even after the key is pressed for a long period of time.
   
## Key takeaways
- [custom data attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/data-*) in HTML and [attribute selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors) in CSS
- [transitionend event](https://developer.mozilla.org/en-US/docs/Web/API/Element/transitionend_event)

## Source
For the background image, I have used a free-to-use image from Unsplash.   
The link to the original image source is [here](https://unsplash.com/ko/%EC%82%AC%EC%A7%84/%EC%88%98%ED%83%89%EA%B3%BC-%EB%8B%AD-%EB%B0%A9%EB%AA%A9%EC%9E%A5%EA%B3%BC-%EC%95%94%ED%83%89-UNDjDRBS5x4).   
For the sound files, I have used the ones the starter files provided by [Wes Bos' repository](https://github.com/wesbos/JavaScript30) that I have forked from.