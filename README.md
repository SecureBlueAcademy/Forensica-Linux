# Forensica-Linux: A Powerful Linux Log Analysis Tool  

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/)  

Forensica-Linux is a Python-based tool designed for efficient and comprehensive Linux log and UAC data collection analysis.  It's designed to help security analysts and forensic investigators quickly identify potential security incidents and anomalies within Linux systems.  Works on Windows, providing cross-platform usability.  

**Key Features:**  

*   **Linux Log Analysis:**  Analyze Linux logs for suspicious activity based on predefined rules.  
*   **Advanced Analysis (UAC Data):**  Leverage data collected from the UAC tool (another Linux Data collection Tool) for deeper insights into system behavior, cron jobs, bash history, and temporary files.  

**Get Started!**

## Table of Contents  

*   [User Interface](#user-interface)  
*   [Tool's Workflow](#tools-workflow)  
*   [Analysis Reports](#analysis-reports)  
*   [Feedback & Contributions](#feedback--contributions)  
*   [License](#license)  

## User Interface  

The user interface is designed for ease of use and efficient analysis.  

![Forensica-Linux User Interface](https://github.com/user-attachments/assets/92a42277-c147-415f-b2ea-1a6722a76e29)  

1.  **Case Name:**  Assign a descriptive name to your analysis case for easy organization and retrieval.  
2.  **Directory Option:**  
    *   **Log Analysis:**  Specify the directory containing the collected Linux logs.  
    *   **Advanced Analysis:**  Provide the path to the UAC tool's output folder.  
3.  **Analysis Option:**  Choose the type of analysis to perform.  
    *   **Log Analysis:** Performs log analysis based on a predefined rule set and generates an HTML report.  
    *   **Advanced Analysis:**  Analyzes UAC data and other collected files (cron jobs, bash history, tmp files, etc.) based on a set of rules.  
4.  **Analyze Button:** Initiates the selected analysis.  
5.  **Recent Cases:** Displays a list of recent analyses with timestamps for quick access.  
6.  **Open Case Button:** Opens the selected case for review.  
7.  **Theme Button:**  Toggles between Light and Dark modes for comfortable viewing.  

![Forensica-Linux Theme Selection](https://github.com/user-attachments/assets/fb78cef4-84d2-4c1c-baa6-9e418360bde3)  

8.  **View Report Button:** Appears after analysis completion, allowing you to view the results.  
9.  **Triggered Rules and Details:** Displays all triggered rules and detailed information about the analysis.  

## Tool's Workflow  

Follow these steps to perform an analysis with Forensica-Linux:  

1.  **Input Configuration:** Enter a Case Name, select the appropriate directory, and choose the desired analysis option.  Click the "Analyze" button to begin.  
    *   **Log Analysis:**  Simply provide the directory containing the Linux Logs.  
    *   **Advanced Analysis:** Provide the UAC (Linux Data Collection Tool) output directory. The expected directory structure should resemble the following:  

![UAC Output Directory Structure](https://github.com/user-attachments/assets/e94293c7-2208-4424-9cbd-41d41cc3c342)  

2.  **View Analysis Report:** Once the analysis is complete, click the "View Report" button to access the results.  

## Analysis Reports  

The generated analysis reports provide a comprehensive overview of potential security incidents and anomalies.  

![Analysis Report Snippet 1](https://github.com/user-attachments/assets/a4a4512c-7d18-448b-a7c8-57972112838b)  

![Analysis Report Snippet 2](https://github.com/user-attachments/assets/32d94a29-4451-426b-a56e-23d91540ae40)  

![Analysis Report Snippet 3](https://github.com/user-attachments/assets/448e2eae-dec9-4067-97b1-41e68f08f0c4)  

## Feedback & Contributions  

We welcome your feedback and contributions to help improve Forensica-Linux! Please feel free to submit bug reports, feature requests, and pull requests.  

## License  

Forensica-Linux is an open-source, free to use for anyone.

Happy Forensics!
