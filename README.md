Sanji Develop Bundle
====================

Using this **package (docker image + scripts)**, developers could play with Sanji Framework more easily.

## Quick Start

:bowtie: **Install Docker and Fig**
- **Docker** Please go to [Docker.io](https://docs.docker.com/installation/ubuntulinux/) for more installation information.
- **Fig**
```sh
$ pip install fig
```
Need help? Please go to [fig.sh](http://www.fig.sh/).

:heart_eyes: **Play Bundle with Sanji Fullstack**
```sh
$ BUNDLE_PATH="/home/zack/cellular" make
```

## Screenshot
<img src="https://cloud.githubusercontent.com/assets/690703/5083276/0496f820-6f2e-11e4-985d-abe18dc57b94.png" alt="alt text" style="width: 400px;">

<img src="https://cloud.githubusercontent.com/assets/690703/5083153/b0c62614-6f2b-11e4-94a3-850d389c9300.png" alt="alt text" style="width: 400px;">

## More Fun

### Commands
- `$ make` will run `pip install -r requirements.txt && python $BUNDLE_MAIN` and startup.
- `$ make clean` clean up temporary directories and all containers.
- `$ make deepclean` clean up all containers and related images.

### Environment Variable
- **BUNDLE_PATH** bundle's directory path `default: .`
- **BUNDLE_MAIN** bundle's entrypoint `default: index.py`

###Inspect MQTT Message Flow
- Open [http://localhost:8080](http://localhost:8080)
- [sanji-mqtt-inspector](https://github.com/Sanji-IO/sanji-mqtt-inspector) is there for you.

## Licence
MOXA
