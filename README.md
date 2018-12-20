# ORC Simulator


Try out the [demo app here](https://orcsimulator.herokuapp.com/).

![Animated1](images/Animated1.gif)


## Getting Started

### Using the demo

To get started, select a footage you want to view, and choose the display mode (with or without bounding boxes). Then, you can start playing the video, and the visualization will be displayed depending on the current time.

### Running the app locally

First create a virtual environment with conda or venv inside a temp folder, then activate it.

```
virtualenv dash-object-detection

# Windows
dash-object-detection\Scripts\activate
# Or Linux
source venv/bin/activate
```

Clone the git repo, then install the requirements with pip
```
git clone https://github.com/plotly/dash-object-detection.git
cd dash-object-detection
pip install -r requirements.txt
```

Run the app
```
python3 app.py
```

## About the app


### Model


## Built With

* [Dash](https://dash.plot.ly/) - Main server and interactive components
* [Plotly Python](https://plot.ly/python/) - Used to create the interactive plots
* [OpenCV](https://docs.opencv.org/) - Create the video with bounding boxes

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Nial** - *Initial Work* - [@ndaly06](https://github.com/ndaly06)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

## Screenshots
![Screenshot1](images/Screenshot1.png)

![Screenshot2](images/Screenshot2.png)

![Screenshot3](images/Screenshot3.png)
