# Forensica-Linux
A python based tool (works on Windows) for Linux log and UAC data collection analysis.

Forensica-Linux is a python based tool. Currently, it can perform two functions. 
1. Linux Log Analysis
2. Advance analysis (For this, you will need the collected data from the UAC tool)

# User Interface
The user interface of the tool looks like this:
![image](https://github.com/user-attachments/assets/92a42277-c147-415f-b2ea-1a6722a76e29)
1. Case Name: This option is for naming the output so you can get back to the results and not get confused.
2. Directory Option: This option is for selecting the directory.
   - In case of "Log Analysis", you should provide the collected logs directory from a Linux System.
   - In case of "Advance Analysis", you should provide the path of UAC tool's output folder.
3. Analysis Option: This option is for selecting the analysis type as per the need. It has two options to select from:
   - Log Analysis: This will perform log analysis based on predefined rule set and give output in html report.
   - Advance Analysis: This will perform the log analysis on the give UAC data and also perform analysis on other collected files (Cron Jobs, bash history, tmp files, etc) based on a set of rules.
4. Analyze Button: This will start the analysis.
5. Recent Cases: This option will show the recent analysis you have done in the past with their timestamps.
6. Open Case Button: This will open the selected Case.
7. Theme Button: To switch between Light and Dark modes.
![image](https://github.com/user-attachments/assets/fb78cef4-84d2-4c1c-baa6-9e418360bde3)
8. View Report Button: This will appear when the analysis is complete and can be used to view the anlaysis results.
9. This will show all the triggered rules and details about the anlaysis.

# Tool's Working
1. After providing a Case Name, appropriate directory, and selecting the analysis option, click Analyze button to start the analysis.
  - For Log Analysis, you just have to provide the directory containing Linux Logs.
  - For Advance analysis, you have to provide the UAC (a Linux Data collection Tool) output directory. It should look like this:
![image](https://github.com/user-attachments/assets/e94293c7-2208-4424-9cbd-41d41cc3c342)
2. After the analysis complete, click the View Report button to view the analysis results.
3. The results will look like this:
![image](https://github.com/user-attachments/assets/a4a4512c-7d18-448b-a7c8-57972112838b)
![image](https://github.com/user-attachments/assets/32d94a29-4451-426b-a56e-23d91540ae40)
![image](https://github.com/user-attachments/assets/448e2eae-dec9-4067-97b1-41e68f08f0c4)

# Feedback
Feel free to share any feedback on the tool so I continue to enhance it.
Happy Forensics!






