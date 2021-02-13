![index](https://github.com/hseera/influxdb-jmeter-plot/blob/main/image/plot.png)

# influxdb-jmeter-plot
This simple utility connects to Influxdb, downloads the JMeter response time data and plots a chart.
It demostrate how to accomplish the task. Script can be modified as per your need.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
```
Note: 
1: The script was test on Windows OS.
2: [NovatecConsulting](https://github.com/NovaTecConsulting/JMeter-InfluxDB-Writer/releases) JMeter plugin to used in JMeter to send data to Influxdb.
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

## Authors

* **Harinder Seera** - *Initial work* - [OzPerf](https://ozperf.com/)

If you would like to contribute to this project, please reachout to me.

## License

This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details

