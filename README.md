# Earthquake-Swarm-Analysis-Tools

Summary of the Automatic Analysis Tools

(1) Automatic detection of earthquake swarm from earthquake catalogue

(2) Automatic detection of spatial and temporal range of earthquake swarm event

(3) Automatic searching for SAR dataset covering the earthquake swarm event

(4) Automatic processing the interferograms and generating the line-of-sight surface deformation field


https://pypi.python.org/pypi/schedule
pip install schedule

import schedule
import time

def job(t):
    print "I'm working...", t
    return

schedule.every().day.at("01:00").do(job,'It is 01:00')

while True:
    schedule.run_pending()
    time.sleep(60) # wait one minute

nohup python2.7 MyScheduledProgram.py &


