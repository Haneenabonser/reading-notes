**Charts**             
Charts: displaying data visually instead of using tables.                     
Chart.js: a JavaScript plugin that uses HTML5’s \<canvas\> element to draw the graph onto the page.
How to use chart.js?
1- download Chart.js.                                 
2- Drawing a line chart by creating  a canvas element in our HTML.(in the body).                                
3- write a script that will retrieve the context of the canvas(in the footer).                                
4- Drawing a pie chart, then a bar chart.                       

**\<canvas\>**            
- It has an apening and closing tag.
- Can be styled like any normal image.
- Attributes;(width, height, id, etc).
- Has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context.
- Coordinate space: canvas grid. 
- By using canvas we can draw;(rectangles, triangles, lines, arcs and curves), and using x,y coordinates.
- There can be a series of paths and drawing commands to draw objects.
- *Styling*:  
        - Color:           
          fillStyle = color: sets the style used when filling shapes.                                                                                                 strokeStyle = color: sets the style for shapes' outlines.                                        
        - Transparency:                                         
          globalAlpha = transparencyValue:(0-1).                              
        - Line styles.                         
        - Gradients.                          
        - Patterns:createPattern(image, type).                              
        - Shadows.                   

- The canvas rendering context provides two methods to render text:                  
fill/strokeText(text, x, y [, maxWidth]).       
- Styling text: font, textAlign, textBaseline, direction.





          
