# Concur Self-guided Demo -- Expense-Process

Main Ask: We need to recreate specific screens of the Concur web application, inside of a div/device for our client. 

PDF
---
The screens.pdf contains each screen we are looking to have created. In the PDF you will see each page has the .html file title that matches the screen. 
[screens.pdf](./screens.pdf)


Product Demo
---
We have received this login from our client to be able to reference the dashboard we are recreating. Please DO NOT make any changes to the dashboard. We want to leave the demo exactly the same as when you logged in. This is strictly to be used for reference for styling.
```
URL: https://www.concursolutions.com/nui/signin
User: meggie.clemens.demo@sap.com
Pass: welcome1
```

Additional Guidelines
---
- In the demo you might find that see that there are grey sides outside of the main container. We do not want to have the grey sides on our version of the screens. We would like the content to go full width within the parent div (as you will see in the screens.pdf)

- If there are styles that repeat between screens, please add those styles to the global section of the main.scss file. Any changes that are specific to a screen, please nest it under the appropriate/matching class to keep it contained to that one screen.

- Please do no use any frameworks or libraries, we are looking for only html & css/scss
    - We prefer you use sass/scss however we have no included the compliler within this build. Feel free to use your own compiler. If this is an issue it is alright to use the main.css file instead.

- Please use percentages rather than hard coded pixels whenever possible


Questions
---
If you have any questions or concerns feel free to contact us
- Sean Cesmat (sean.cesmat@indigoslate.com)
- Trevor Robinson (trevor.robinson@indigoslate.com)