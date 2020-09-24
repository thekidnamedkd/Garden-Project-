# _Garden Project_

#### _This application is used as a garden planner for people just starting out, 2020 ver 1.0_

#### By _Ian Gregg & Kevin Davis & Ben Russell & Joseph Pearce & Sean Downs_

[Garden-project](https://github.com/oldgregg89/Garden-Project-)

## Description

_Help a user decide which plants are best for their location (zip code) and condition (soil type, shade, direction of sun, water frequency). They will be able to choose if they want drought tolerant plants or native plants or plants that flower during different seasons. This application will take advantage of data from the USDA and the Trefle API for plants to return results based on plain english questions to the user about what kind of garden they would like to have._

* Below we have explanation of our MVP & week schedule/daily goals

![MVP & stretch goals](/assets/img/MVP&StrechGoals.png)

![Weekly schedule](/assets/img/weeklySchedule&Day2_3.png)

![day4](/assets/img/day4.png)




## Setup/Installation Requirements

* Click on clone and clone this repo to your desktop.
* From there navigate to desktop to where you cloned this repo.
* Open the project up in Visual Code Studio.
* In your terminal run 'npm install'.
* To build the project run 'npm run build'
* To start the webpack server 'npm run start'

## Specs

| Behavior    | Input | Output |
| :---------- | ----- | -----: |
| 1. Take in user input of their zip code to get the hardiness zone from our API | enter zip code 'example:97321' | 'Your Zip is 97321 and your zone is 8b which is a temperature range of 15 to 20°F' |
| 2. Take in user answers to questionnaire for ```Create a plant list based on you and your zone!``` | enter submit with the ```ready for the wild``` answer| A list of plants that recognize that answer |
| 3. click the tabs at top of screen | choose an option; example:```about``` | directs the browser to the ```about``` section at the bottom of the page |

## UI/Design

For the look and feel of this project we wanted to reference classic farm documents and the hippie feel of sustainability first established in the 60's and 70's. We framed our type treatment and layout as an easy to use survey that could service these complex botany definitions and practices into a resource for the average house plant love or urban farmer, but be powerful enough in the backend for someone looking to layout a full garden or agricultural space.

![wireframe1](/assets/img/wireframe1.png)

![wireframe2](/assets/img/wireframe2.png)


## Known Bugs

* Save function doesn't work with the local storage due to browser issuses. 

* Not all the options within the ```Create a plant list based on you and your zone!``` work. 

## Support and contact details

Contact Ian Gregg: <iangregg188@gmail.com>

Contact Ben Russell: <benjaminrussell36@gmail.com>

Contact Joseph Pearce: <joseph.pearce05@gmail.com>

Contract Sean Downs: <spdowns@protonmail.com>

Kevin Davis <thekidnamedkd@gmail.com>

### License

Copyright (c) 2020 **_Ian Gregg & Kevin Davis & Ben Russell & Joseph Pearce & Sean Downs_**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
