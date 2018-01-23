# Project Title

The Get Audio API provides lambda functions for integration systems.

[The swagger with all endpoints](https://app.swaggerhub.com/apis/iheartmedia/mrmasterservice/1.0.0#/bms/getAudio)
 

## Getting Started

### Prerequisites

Make sure that your local development contains:

```
Python >= 3.5
pip >= 3
```

### Installing

Install all requirements: 

```
sudo pip3 install -r requirements.txt
```

Create scripts/secret/widen.ini:

```
[widen]
  url:                     https://gateway-stg.x1-nonprod.iheartmedia.com/mediaasset/media
  Authorization: 
```

## Running the tests

The tests use pytest 3.3.2. 

### Some recommendations

- tests must be in scripts folder
- class name must start 'Test'

### Hands on

Run the tests:

```
cd scripts
pytest test_get_audio.py
```

Then the return should be:

```
test_get_audio.py ......                                                                 [100%]
```

!!! Can been returned error 404 to any functions, if you do not still in VPN IHeart. !!!


## Deployment

To deploy the changes to environments use Jenkins.

:TODO LINK JENKINS:

Documentation of deployment strategy CI

:TODO DOCUMENTATION CI (CAN BE A DIAGRAM THAT EXPLAIN THE PROCESS):
