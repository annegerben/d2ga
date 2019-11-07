# d2ga docker container for Domoticz-Google-Assistant

d2ga is docker container for Domoticz-Google-Assistant

d2ga/Domoticz-Google-Assistant delivers:

    the oauth authorization and smarthome endpoint for the google assistant
    Two-factor authentication pin for domoticz protected devices (works best with english language)
    Acknowledgement with Yes or No. (works best with english language)
    Arm Disarm Securitypanel (works best with english language)
    On/Off, Brightness, Thermostat, Color Settings, speaker volume, Lock/Unlock, Scene and Open/Close
    Stream surveillance camera to chromecast

howto setup:
1. Make sure you have a reverse proxy for establishing secure connection (Domoticz-Google-Assistant itself provides currently only unsecure one - http only)
2. Pull and run contaitner, make sure you have port 3030 mapped and mounted /config.
3. Setup Actions on Google Console Instructions: https://github.com/DewGew/Domoticz-Google-Assistant/blob/master/README.md#setup-actions-on-google-console-instructions 
4. Update config.py in mounted config folder accordingly
5. restart the container, done
