# SQM-Shopping Queue Manager
A web based queue management system built with Python Flask, Bootstrap and jQuery.
Features:

    * Support for POS USB printers on major operating systems.
    * Customize-able interfaces.
    * Supports text-to-speech announcement.
    
### Setup:

#### - From the source:
- Make sure to install and use **Python 3.7** or **3.8**
- Execute the following commands in a terminal window:
1. `git clone https://github.com/Swapnil8787/Shopping-Queue-Manager.git`
2. `cd Shopping-Queue-Manager`
3. `python -m pip install -r requirements/deploy.txt`
4. `python run.py --cli`

- To checkout the supported command-line options `python run.py --help`:
```bash
Usage: run.py [OPTIONS]

  SQM command-line interface (CLI):

  * If `--cli` is not used, initializing GUI will be attempted.

  * If no `ip` is passed it will default to `127.0.0.1`.

  * If no `port` is passed it will default to a random port.

Options:
  --cli        To use commandline interface instead of GUI.
  --quiet      To silence web server logs.
  --ip TEXT    IP address to stream the service on.
  --port TEXT  Port to stream the service through.
  --help       Show this message and exit.
```

