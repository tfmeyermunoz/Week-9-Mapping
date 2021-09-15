# Week-9-Mapping

This repository is intended to include the exercises I had to resolve during the 9th week of the MIT JavaScript course.

## Title of the project: 

Live Bus Animation Project of Tomás Meyer

## Brief project description:

This repository is intended to include all the work done at the coding activity of week 9 of the MIT JavaScript course. The repository structure is divided into
HTML, CCS and JS files, which include:

- index.html. The file that organizes my CSS, HTML, and JavaScript codes into one file.
- styles.ccs. The file where I define the styles I will be using in my webpage.
- mapanimation.js. The file where I have my JavaScript function to update the location of the bus every 15 seconds.

## How to run:

1. First of all, you need to create an account in mapbox at the following adress: https://www.mapbox.com/.
2. Once you have your account, go to your profile at https://account.mapbox.com/ and copy your access token.
3. Download all the files included in the repository and open the mapanimation.js file. Paste your access token at the line with the command mapboxgl.accessToken = ''.
4. Open the index.html file in your favourite browser and use the button to be able to see the live location of the bus that is updated every 15 seconds.

## Next steps:

It would be wonderful to have more information about the buses. For example, I would like to add the following:

1. Is the bus active or traveling back to the station (without taking passengers)?
2. How much space left is there at the bus? How many people can still be carried?
3. How much time do I have to wait until the bus arrives at my stop.

## License:

Copyright 2021 Tomás Meyer
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
