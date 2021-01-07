---
template: blog-post
slug: /syntax-highlighting
date: 2020-12-28 08:40
title: "Syntax Highlighting"
featuredImage: /assets/coding.jpg
---

### A Template for Syntax Highlighting


```javascript
function palindrome(str) {
    // remove all non-alphanumeric characters by nothing.
    str = str.toLowerCase().replace(/[\W_]/g , ""); 
    var ispalindrome = true;
     //loop through half length of the array.
    for (let i =0 ; i<str.length/2 ; i++ ){

         //check if first half is equal to the second half.
        if(str[i] !== str[str.length - i - 1]){
            ispalindrome = false;
        }
    } 
    return ispalindrome
    }
    
    console.log(palindrome("almostomla"));
```