# CSS learning.
This repository is all about my CSS learning from free-code camp and other sites.

## Mini Project
learning :
1. ##### CSS selectors :
   1. Element selector
   2. Id selector
   3. Class selector
   4. Universal selector (*)
   
   They way to select all elements and apply common styles can be done using the universal selector.
   eg.
   setting the margin and padding for the all elements.
   *{
     margin : 0;
     padding : 0;
     box-sizing :border-box;
   }
 
2. ##### CSS box model : 
  ![image](https://user-images.githubusercontent.com/52494739/205315829-7dd873e5-2f10-408d-a85c-6b8fcf8800ac.png)
  
  
  
   margin - border - padding - content.
   
   There is one important CSS property which dealing with CSS box model, that is box-sizing
      Majorly there are 2 important values for box-sizing:
      1. border-box = actual width of the element  = border + padding + content size
      2. content-box = only content size.
      eg.
        h1{
          width: 400px;
        }
        
    with box-sizing : border-box, it will include all border, padding and content size.
        
   ![image](https://user-images.githubusercontent.com/52494739/205321653-b5e38961-d241-4a93-9659-f1a56ed45072.png)   
          
          
   400 = 298px(content) + 48px + 48px(padding) + 3px+ 3px;(border)   

   with box-sizing : content-box, it will include only content width. (here h1's overall size/ length will get increase.)
        
        
![image](https://user-images.githubusercontent.com/52494739/205321525-08453c34-051c-4842-9a23-6b979da60d29.png)




         502 = 400px(content) + 48px +48px(padding) + 3px + 3px(border) 
          
3. #####  Pseudo class  and  Pseudo element :

          a:hover{                ::marker{
            color : red;             font-size : 2 rem
           }                       }

4. #####  CSS units :
    Most commonly used css units:
    1. px
    2. view height (vh) and view width (vw)
    3. rem and em
    4. %
    
##### what is the differece between rem and em units **
   em is a CSS unit relative to the font size of the parent element, while rem is a CSS unit relative to the font size of an html element(root element).
     
     
     
     
