# Voice-Activated AWS Infrastructure Monitor & Terminal

An enterprise-ready, local voice assistant that securely monitors and provisions AWS cloud resources via speech commands. Built during a hands-on python automation internship to bridge local hardware scripts with distributed cloud environments.

## 🛠️ Features Developed
* **Voice-Driven Routing Hub:** Utilizes `SpeechRecognition` to interpret audio patterns into executable conditional workflows via an asynchronous `while` matrix loop.
* **AWS Cloud Provisioning:** Communicates directly with the Amazon Web Services API via `Boto3` to audit S3 buckets and track EC2 computation runtimes.
* **Failure-Safe Guard Rails:** Implements strict security validations on destructive execution blocks (like instance stop/termination commands) to shield cloud servers from false microphone triggers.
* **Automated Web Triggers:** Seamlessly integrates `pywhatkit` to launch specific documentation paths and learning pipelines through automation.

## 🧰 Libraries & Tools Used
* **Core Language:** Python 3 (Control Flows, Data Structures, Exception Scopes)
* **Cloud Infrastructure SDK:** AWS Boto3 (EC2 Resource, S3 Client)
* **Audio & Speech Engine:** SpeechRecognition API, Pyttsx3 Text-To-Speech engine
* **Automation Utilities:** PyJokes, PyWhatKit

## ⚙️ How To Run Locally
1. Clone this repository.
2. Install the dependencies: `pip install boto3 speechrecognition pyttsx3 pyjokes pywhatkit pyaudio`
3. Configure your unique `Access_key` and `Secret_key` constants inside the main script file.
4. Run the python execution target file.
