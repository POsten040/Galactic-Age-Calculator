# Galactic Age Calculator

#### **This program calculates your age based on different planets solar years. Patrick Osten, 10/23/2020**

**[Click here to open github repository in web browser](https://github.com/POsten040/week-5-project)**

## Description

Everyone gets old, but how old? And on what planet?
This program will calculate the age of a user for different planets, as well as let them know their life expectancy there. If they've lived past the expected age it will tell them how many years they've exceeded the expectancy. 

## Installation Requirements

- Up to date internet browser ([Chrome](https://www.google.com/chrome/?brand=CHBD&gclid=Cj0KCQjw28T8BRDbARIsAEOMBcy9jwgkNels1LOSIWTx4sDazLfEgC6PylTug62KqyWPeA0EMyr3254aAjTTEALw_wcB&gclsrc=aw.ds), [Mozilla](https://www.mozilla.org/en-US/firefox/), [Opera](https://www.opera.com/)).
 
- [Node.js](https://nodejs.org/en/download/)
 
 -**optional**- 
- Code editor like [VsCode](https://**Code**.visualstudio.com/download) to view source **Code**.

## Setup

#### From the web
1. Go to this [GitHub Repo Page](https://github.com/POsten040/week-5-project).
2. Click the "Code" and click the 'Download zip' option.
3. Unzip the file, navigate to the root directory (week-1-project folder).
4. From the terminal type `npm run start` to launch in your browser.

--or--

#### From Terminal

1. Open GitBash/Bash, type 
: `git clone {https://github.com/POsten040/week-5-project}`
2. From your terminal, install dependencies by typing `npm i`
3. You can run the tests in the project with `npm run test`
4. To launch the project in a browser type `npm run start`.

## Specs
### Describe AgeCalculator
<table>
  <tr>
    <th>Test</th>
    <th>Input</th>
    <th>Output</th>
  <tr>
    <td>Should store user input for age in user object.</td>
    <td>9/6/1990</td>
    <td>user.age = 9/6/1990</td>
  <tr>
  <td>Should accept negative numbers for age and treat them as positive.</td>
    <td>inputAge = -9</td>
    <td>user.age = 9</td>
  <tr>
    <td>Should calculate age in Mercury years(rounded down).</td>
    <td>30</td>
    <td>7</td>
  <tr>
    <td>Should calculate age in Venus years(rounded down).</td>
    <td>30</td>
    <td>18</td>
  <tr>
    <td>Should calculate age in Mars years(rounded down).</td>
    <td>30</td>
    <td>56</td>
  <tr>
    <td>Should calculate age in Jupiter years(rounded down).</td>
    <td>30</td>
    <td>348</td>
 <tr>
    <td>Should tell user how many years over agerave life expectancy they have lived.</td>
    <td>99, average expectancy = 80</td>
    <td>You've lived 19 years over your expected expiration date</td>
  <tr>
    <td>Should tell user how many years under the average life expectancy they've lived.</td>
    <td>Age = 20, AvgExpec = 80.</td>
    <td>You've got 60 years left to do stuff</td>
  <tr>
    <td>Should tell user how many (planet)years they have left to live.</td>
    <td>Age = 99, AvgExpec = 80. mercury years .24 to 1 earth year.</td>
    <td>You've lived 4 years over your expected expiration date on Mercury</td>
  <tr>
</table>

## Contact 
- posten.coding@gmail.com

## Technologies Used

- HTML5 language  
- CSS 
- Bootstrap
- Javascript
- JQuery
- Node.js
- Webpack
- Jest

## License

[MIT license](https://opensource.org/licenses/MIT)

## Copyright (c) 2020 **_Patrick Osten_**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.