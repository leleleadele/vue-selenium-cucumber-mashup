# vue-selenium-cucumber-mashup
### Training task to practice using Selenium WebDriver with Cucumber for Vue component testing

wsup.

this one's to you who want to practice selenium webdriver with cucumbers.
if you've never touched Selenium & Cucumber before, take a look at their official documentation. They have step-by-step guides to create a very basic setup for some simple testing - follow that guide before you dive into this task to save yourself from unnecessary headache.

first off follow this lovely guide to make sure you have cucumber working properly in your project:

https://cucumber.io/docs/guides/10-minute-tutorial/

once that is done, continue by incorporating Selenium WebDriver into the mix. follow again Cucumber's documentation or do a mashup between that one and the Selenium WebDriver documentation (make sure you have selected "JavaScript" in both sites, otherwise you'll be looking at the wrong language:

https://www.selenium.dev/documentation/en/
https://cucumber.io/docs/guides/browser-automation/

## task description

### general rules

1. let's use VueJS + NodeJS + Webpack to get the foundations of the project rolling
2. style stuff using Sass. we're sassy
3. follow BEM standards for class naming
4. create components according to acceptance criteria
5. create automated tests according to acceptance criteria
6. don't dwell on Vue/design too much!!! Plan your time so you can manage to try out Selenium and Cucumber within this week
7. something's unclear? feeling stuck? don't hesitate to contact me (le Adele)

### acceptance criteria

The component consists of a H1 heading, several tabs and their content underneath. Each tab's content consists of a H2 heading and a description. Only content of the selected/active tab is displayed.
* layout should follow [this design sketch](https://www.figma.com/file/fxm7inGGcxUFgv0sDAAKMI/Untitled?node-id=0%3A1)
* design has a mobile(0...768px) and a desktop(768px...) version
* use proper html tags (H! & H2, button, etc.) for elements on the page
* tabs are interactive
  * only one tab can be active at a time
  * first tab is active per default when page is loaded
  * once a tab is clicked, the clicked tab becomes active. The previously active tab therefore becomes inactive
  * active tabs are white
  * inactive tabs are pink
