## Detecting Browser and Its version

This code is based on the article from [MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Browser_detection_using_the_user_agent). 
Where they gave a brief hint about various keywords that can be used to detect the browser name and device type (Mobile/Desktop).

![MDN](https://user-images.githubusercontent.com/59413787/89720361-dd82c480-d9ee-11ea-822c-1da618632b7f.png)

The data shown in the image above is not sufficient for detecting all the browsers
<br>
<br>
**e.g. userAgent of Firefox will have Fxios as a keyword rather than Firefox.**

A few changes are also done to detect browsers like **Edge** and **UCBrowser**

The code is currently tested for the following browsers by changing userAgent with the help of dev-tools ([How to change userAgent](https://www.howtogeek.com/113439/how-to-change-your-browsers-user-agent-without-installing-any-extensions/)):
- FireFox
- Chrome
- IE
- Edge
- Opera
- Safari
- UCBrowser 
