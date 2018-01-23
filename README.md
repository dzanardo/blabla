# Project Title

The XXXX API provides lambda functions for integration systems. The lambda functions calls procedures SQL. 

## Getting Started

### Prerequisites

Make sure that your local development contains:

```
Python >= 3.5
pip >= 3
```

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

Install all requirements: 

```
sudo pip3 install -r requirements.txt
sudo pip3 install boto3
```

Create scripts/secret/widen.ini:

```
[widen]
  url:                     https://gateway-stg.x1-nonprod.iheartmedia.com/mediaasset/media
  Authorization: 
```

Now you can run the tests:

```
cd scripts
pytest test_get_audio.py
```

Then the return should be:

```
test_get_audio.py ......                                                                 [100%]
```

!!! Can been returned error 404 to any functions, if you do not still in VPN IHeart. !!!



## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
