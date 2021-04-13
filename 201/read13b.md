## CSS Transforms, Transitions, and Animations
**Transforms**
- transform property settings: 2D & 3D.
- syntax: \{transform: transformType (amount);\}.
- 2D rotate determined by degrees(deg).
- 2D scale/translate can be in x direction(scale/translateX), y direction (scale/translateY), or both of them(scale/translate).
- We can combine transforms by listing their values one after the other one.
- In order to have 3D transforms we need to use a *perspective* value & a a third axis Z.
- The (transform-style) property needs to be placed on the parent element, above any nested transforms.

**Transitions & Animations**
- The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.
- There are 4 transition related properties(the first three are the most popular):                                        - transition-property: determines exactly what properties will be altered in conjunction with the other transitional properties.                                                                                              
- transition-duration: The duration in which a transition takes place, can set using general timing values:(s or ms).                                                                                                    
- transition-timing-function: used to set the speed in which a transition will move.                                                                                                    
- transition-delay: sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing.            

- If multiple properties need to be transitioned they may be comma separated within the transition-property value.

**Animations Keyframes**             
- The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.
- Once we have declared the (animation-name) property on an element, animations behave similarly to transitions.
- By default, animations run their cycle once from beginning to end and then stop, we can use (animation-iteration-count) to have the animation repeat itself.
