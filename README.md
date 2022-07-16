# KPA500 Web Interface

## Installing Python Dependencies

### Installing Dependencies using pip

Install dependencies using pip by running:

    pip install -r requirements.txt

### Arch Linux

If you don't want to use pip, the following Arch packages should provide all of the necessary modules:

- python-yaml
- python-pyserial
- python-cherrypy

## Configuration

1. Edit `config.yaml` and update the device to the KPA500's serial connection name.

# Starting the Server

Assuming all the Configuration changes are done

    python webpka.py

You can make this a detached process if you need - but to start with it may be best to see what the program is outputting.

If python starts up cleanly and everything was configured correctly, you should be able to get to the [web interface at http://localhost:8000](http://localhost:8000)

Please note: There is minimal error checking - so if you enter something totally stupid there is a possibility this will have an unpleasant consequence on your KPA. Simple steps please !!

de Tim, A45WG


