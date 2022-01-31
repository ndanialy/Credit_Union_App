# Credit_Union_App
 
An application for analyzing the financial health of a client by pulling recent data from an API and forecasting it out with a Monte Carlo simulation.

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

* [alpaca api](https://alpaca.markets/docs/api-documentation/) for pulling the data.

* [json](https://docs.python.org/3/library/json.html) for interpreting the data.

* [dotenv](https://pypi.org/project/python-dotenv/) for creating the environmental data.

* [MCForecastTools](https://github.com/Dbudhram/API/blob/main/MCForecastTools.py) for running the Monte Carlo simulation.

* [Requests](https://3.python-requests.org/) for pulling data from the internet.

---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

pip install python-dotenv

```
---

## Usage

The App imports data from either the API or a website and saves it as a json:

![json](https://user-images.githubusercontent.com/96391748/151743835-f15c6e72-83a3-433b-a846-ce05ea554cb1.PNG)

Using the recent pricing information and portfolio assets creates a graph displaying the composition:

![Pie Chart](https://user-images.githubusercontent.com/96391748/151744003-49be9332-f890-40cb-8a97-27f73f8d2f0f.PNG)

The app runs a monte carlo simulation to predict the cumulative returns over the next 30 years and visualizes them:

![Monte Carlo Results](https://user-images.githubusercontent.com/96391748/151744141-084acbe6-96d6-4bd6-badc-a2ab5007c374.PNG)

Also generates limits and summary statistics of the simulation:

![summary stats](https://user-images.githubusercontent.com/96391748/151744380-64ac8737-5fab-465c-850d-ba9d9a289287.PNG)

Finally, it does the same thing again but with a different composition and only 10 years into the future:

![Monte Carlo 10 Years](https://user-images.githubusercontent.com/96391748/151744218-b057531e-a570-4e39-859c-aec8879bd7b7.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE