# editreadme

## Heading 2

#### Heading 4

###### Heading 6

Plain text

<img src="extras/Bored_Coders_Slim.png" alt="Bored_Coders" width="100%" />
 <br/>
 <br/>

# **Jarvis: An Intelligent Product Master** 🤖

## 🤔❓ _The Problem (SM446) we are solving_ 🙋‍♂️🙋‍♀️:

Today organizations have multiple tools and systems to help assist them in their day to day software development activities. There is need of a system which can connect to applications, mine & analyze data and provide results to stakeholders whenever they need it. Problem Statement: For example, questions to assist development activities could be:

- What is the status of the release of Project X that was due this Friday?
- Why was Feature Y not fulfilled in the last release for Project X ?
- How many test cases failed in the last release of Project X? Send me an email with the last release notes for Project X How to install Project X?
- How was Feature Z implemented? (Note: the robot would need to connect to all the applications, and dig out all the relevant information (description of features and linked commits / comments /guides) related the Feature Z Help me solve the class not found exception against “ClassName”

<img src="extras\problemgif.gif" alt="Postgress" width="100%" />

> _Create an AI/ML based application to be hosted within a corporate/organization intranet with complete access to corporate/organization resources of JIRA, Confluence, Bitbucket and Stack Overflow. The primary responsibility of this software robot (Intelligent Product Master - IPM) is to learn-mine-analyze-serve information about a product to optimize development and support processes in a product team._

<br />
<br />

## 📕 **Current Progress:**

- [x] Basic Replies
- [x] Jira Functions Implementation
- [x] Bitbucket Functions Implementation
- [x] Confluence Functions Implementation
- [x] Handling Meetings Efficiently.
- [x] Pseudocode Generator.
- [x] Static Code Analyzer.
- [x] StackOverflow Search Module.

<br />
<br />

## 🔨 **Languages and Tools:**

<div float="left">
<img src="extras\Postgresql.png" alt="Postgress" height="40" style="padding:20px;"/>
<img src="extras\keras.png" alt="Keras" height="40" style="padding:20px;"/>
<img src="extras\kafka.png" alt="Kafka" height="40" style="padding:20px;"/>
<img src="extras\docker.png" alt="Docker" height="40" style="padding:20px;"/>
<img src="extras\python.png" alt="Python" height="40" style="padding:20px;"/>
<img src="extras\SpaCy.png" alt="Spacy" height="40" style="padding:20px;"/>
<img src="extras\flutter.png" alt="Spacy" height="40" style="padding:20px;"/>
<img src="extras\dart.png" alt="Spacy" height="40" style="padding:20px;"/>
<img src="extras\elasticsearch.png" alt="Spacy" height="40" />
</div>

<br />
<br />

## 🏛 **Architecture:**

<br />
<br />

<img src="extras\architecture.png" alt="Postgress" style="padding:20px;"/>

<br />
<br />

## 🧏‍♂️➡🤖 **NLP Model:**

<img src="extras\nlp model.png" alt="Postgress" style="padding:20px;"/>

<br />
<br />

## ⚙ **Core Features:**

- 🔌 Connect to Jira, Bitbucket and Confluence
- 🧾 Record and Transcribe Meetings
- 🕵️ StackOverflow Search
- 👁 Continuous Learning and Continuous Deployment
  <br />
  <br />

## 🔗 **Core Feature Pipelines :**

### 👨‍💻 Connection with Jira | Confluence | Bitbucket Pipeline :

  <img src="extras/jcb-pipeline.png" alt="JCB pipeline" style="padding:20px;"/>
  <br />

### 🤝 Mintues Of Meeting Pipeline :

  <img src="extras/mom.png" alt="Minutes of Meeting" style="padding:20px;"/>
  <br />

### 🚀 Text Based Search Pipeline :

  <img src="extras\elasticsearch_pipeline.png" alt="Minutes of Meeting" style="padding:20px;"/>
  <br />

### 🔎 StackOverflow Search Pipeline :

  <img src="extras/stackoverflow.png" alt="StackOverflow" style="padding:20px;"/>
  <br />

### 👁 Feed Back and Feed Forward loop for Continuous Training and Continuous Deployment :

  <img src="extras\feedback.png" alt="StackOverflow" style="padding:20px;"/>
  <br />
<br />
<br />

## ✨**Special Features:**

- 👩‍💻 Pseudocode Generator (➡ Ease of understanding old codes )
- 👨‍💻 Static Code Analysis
- ⚖ Distributed architecture
- 🕵️ Highly Secure
- 🤳 Portable
- 🏛 Robust Architecture
- 💦 Fluid App Design
- 👤 Easy to use (😉 Just Talk to it 📢)

<br />
<br />

## ⚙ **Steps to Start Jarvis Server:**

1.  Create a VM (Ubuntu server 18.04 LTS) (Ports to open: 8000)
2.  Install Docker : https://docs.docker.com/install/linux/docker-ce/ubuntu/
3.  Install Docker compose : https://docs.docker.com/compose/install/
4.  Send contents of the "jarvis-server" folder to the VM.
5.  Change Directory to dependencies.
6.  Run all the dependencies (Zookeeper, Kafka, PostgreSQL and Elasticsearch) at once with the command : `sudo docker-compose up -d`
7.  Run command :`pip3 install -r requirements.txt`
8.  Run jarvis-starter Python file to set-up the dependencies automatically (Only to be done when starting Jarvis for the first time).
9.  Change Directory to Jarvis
10. Run Jarvis with the command : `sudo docker-compose up`

<br />
<br />

## 👨‍🏫 **Team Mentor:**

- **Mr. Sandeep Singh Bindra**

<br />
<br />

## 👥 **Team Members:**

- 👮‍♂️ **Vikrant Chauhan (LEADER)**
- 💂‍♂️ **Pranav Taneja**
- 👷‍♂️ **Manan Arora**
- 👨‍🎓 **Ayush Mittal**
- 👩‍🍳 **Gunjan**
- 👩‍🌾 **Niyanta**

<br />
<br />

## 😅 **In Conclusion:**

  <img src="extras/endgif.gif" alt="StackOverflow" style="padding:20px;" width="100%"/>

<br />
<br />

## 🧐 **References:**

- Kafka: https://kafka.apache.org/
- Docker: https://www.docker.com/
- PostgreSQL: https://www.postgresql.org/
- ElasticSearch: https://www.elastic.co/
- TensorFlow: https://www.tensorflow.org/
- SpaCy: https://spacy.io/
- Tesseract: https://github.com/tesseract-ocr/tesseract
- Pseudogen: https://github.com/delihiros/pseudogen
- Pydub: https://github.com/jiaaro/pydub
- Numpy: https://numpy.org/
- SciPy: https://www.scipy.org/
- Logmmse: https://pypi.org/project/logmmse/
- Ffmpeg: https://ffmpeg.org/
- SpeechRecognition: https://pypi.org/project/SpeechRecognition/
- Research Paper for Pseudogen: http://www.phontron.com/paper/oda15ase.pdf
- Flask: https://flask.palletsprojects.com/
- Flutter: https://flutter.dev/
- PsycoPg2: https://pypi.org/project/psycopg2/
- Pycryptodome: https://pypi.org/project/pycryptodome/
- Flutter_tts: https://pub.dev/packages/flutter_tts
- Flutter_audio_recorder: https://pub.dev/packages/flutter_sound_lite
- Flutter_http_client[Dio]: https://pub.dev/packages/dio
- Flutter_get: https://pub.dev/packages/get
- Flutter_encrypt: https://pub.dev/packages/encrypt
- Flutter_division: https://pub.dev/packages/division
