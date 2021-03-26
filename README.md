# This is a wetaher report in Vancouver

## How to run the Script
1. Go to the directory where you clone your github repo/
2. Run './wthr' command.
3. You will see a table of how the script is running.
4. You will see a text file name 'weather.txt' by running ls command.
5. You can displaye the content of the file by running 'cat weather.txt' command.
6. You be able to see a weather report in Vancouver.

## How to use the wthr.service
1. Clone the github repo to your Linux virtual machine.
2. Run 'sudo systemctl start wthr.service' command.
3. You will see a text file name 'weather.txt' by running ls command.
4. You can displaye the content of the file by running 'cat weather.txt' command.
5. You be able to see a weather report in Vancouver

## If you want to run the script hourly to get the latest updates
1. Run 'sudo systemctl start wthr.timer' command.
2. You will see a text file name 'weather.txt' by running ls command.
3. You can displaye the content of the file by running 'cat weather.txt' command.
4. You be able to see a weather report in Vancouver
5. Every hour, the wthr script will be run and a new weather report will be append to the weather.txt

## To stop running the script
1. Run 'sudo systemctl stop wthr.timer' command.
