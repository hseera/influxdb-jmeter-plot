![index](https://github.com/hseera/influxdb-jmeter-plot/blob/main/images/plot.png)

# influxdb-jmeter-plot
![Language Python](https://img.shields.io/badge/%20Language-python-blue.svg) [![Apache License](http://img.shields.io/badge/License-Apache-blue.png)](LICENSE)

[![GitHub Last Commits](https://img.shields.io/github/last-commit/hseera/influxdb-jmeter-plot.svg)](https://github.com/hseera/influxdb-jmeter-plot/commits/) [![GitHub Size](https://img.shields.io/github/repo-size/hseera/influxdb-jmeter-plots.svg)](https://github.com/hseera/influxdb-jmeter-plot/)
[![Open GitHub Issue](https://img.shields.io/badge/Open-Incident-brightgreen.svg)](https://github.com/hseera/influxdb-jmeter-plot/issues/new/choose)
[![GitHub Open Issues](https://img.shields.io/github/issues/hseera/influxdb-jmeter-plot?color=purple)](https://github.com/hseera/influxdb-jmeter-plot/issues?q=is%3Aopen+is%3Aissue)
[![GitHub Closed Issues](https://img.shields.io/github/issues-closed/hseera/influxdb-jmeter-plot?color=purple)](https://github.com/hseera/influxdb-jmeter-plot/issues?q=is%3Aclosed+is%3Aissue)

This simple utility connects to Influxdb, downloads the JMeter response time data and plots a chart.
It demostrate how to accomplish the task. Script can be modified as per your need.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
```
Note: 
1: The script was tested on Windows OS.
2: NovatecConsulting JMeter plugin was used in JMeter to send data to Influxdb. 

Link: https://github.com/NovaTecConsulting/JMeter-InfluxDB-Writer/releases
```

### Prerequisites

What things you need to execute the script

```
1: Python 3.5
2: Influxdb, Panda & Matlab packages installed

```

### Execution
```
1: Make sure above prerequisite are met first.
2: Update the Influxdb connection detail in the script.
3: Update the Influx query accordingly. Sample query example are provided in the script.
4: Update the script with the correct timezone. By default the script timezone is set to Australia/Melbourne.
5: Run the python script
```

## Contribute

If you would like to contribute to this project, please reachout to me. Issues and pull requests are welcomed too.

## Author
[<img id="github" src="./images/github.png" width="50" a="https://github.com/hseera/">](https://github.com/hseera/)    [<img src="./images/linkedin.png" style="max-width:100%;" >](https://www.linkedin.com/in/hpseera) [<img id="twitter" src="./images/twitter.png" width="50" a="twitter.com/HarinderSeera/">](https://twitter.com/@HarinderSeera) <a href="https://twitter.com/intent/follow?screen_name=harinderseera"> <img src="https://img.shields.io/twitter/follow/harinderseera.svg?label=Follow%20@harinderseera" alt="Follow @harinderseera" /> </a>          [![GitHub followers](https://img.shields.io/github/followers/hseera.svg?style=social&label=Follow&maxAge=2592000)](https://github.com/hseera?tab=followers)


## License

This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details

