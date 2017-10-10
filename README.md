# proj2-flask
A starter project for using the Flask framework

## Author: Carter Fritsch, cfritsch@uoregon.edu

## Overview

A simple Flask webserver for a class schedule display that includes:
  * The starting date of each week, calculated in weeks since the start date, using the Arrow library
  * A highlighted indication of the current week in the term based on the date
  * Course Topic and Project listings for each week

## Requirements

  * python 3.4 or above
  * python3-venv

*The target environment for this project is a Raspberry Pi running Raspbian Stretch*

## Usage

**Configuration:** Create a configuration file from `credentials-skel.ini` and save it as `./syllabus/credentials.ini`.

**Installation:** `make install`. Creates the Virtual Environment with dependencies.

**Testing:** `make run`. Starts the Flask test server with the settings found in the credentials file. Can be stopped with `Ctrl+C`

**Start / Stop:** Use included bash scripts `start.sh` and `stop.sh`