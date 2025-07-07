[![header](https://capsule-render.vercel.app/api?type=venom&height=300&color=0:038C7F,45:04BF8A,60:04D98B,100:74BF04&text=Smart%20Farm&fontAlign=50&fontColor=ffffff&textBg=false&desc=By%20TreeNut&descAlign=50&descAlignY=63&fontAlignY=46)](https://github.com/CutTheWire/smart_farm.git)


## 🏷️ 스마트팜 메인 프로젝트 깃허브

[![스마트팜 프로젝트](https://capsule-render.vercel.app/api?type=waving&height=300&color=0:038C7F,30:04BF8A,70:04D98B,100:74BF04&text=Smart%20Farm%20Main&fontColor=ffffff&textBg=false&desc=Link%20:%20jgkim14_SmartFarm.git&descAlignY=53&fontAlignY=35&descAlign=67)](https://github.com/jgkim14/SmartFarm.git)

---

## 🌳 프로젝트 파일 트리

📦JMS_smart_farm     
 ┣ 📂.github      
 ┃ ┣ 📂workflows     
 ┃ ┃ ┗ 📜Python.yml         
 ┣ 📂Ar      
 ┃ ┣ 📂Arduino_UNO      
 ┃ ┃ ┣ 📂JMS_Arduino      
 ┃ ┃ ┃ ┗ 📜JMS_Arduino.ino      
 ┣ 📂DB      
 ┃ ┣ 📂python      
 ┃ ┃ ┣ 📜DB_insert_test_data.py      
 ┃ ┃ ┣ 📜DB_Remaker.py      
 ┃ ┃ ┣ 📜GetUpdate.py      
 ┃ ┃ ┗ 📜week.py      
 ┃ ┣ 📜Dockerfile      
 ┃ ┗ 📜sqlite_setup.py      
 ┣ 📂Py      
 ┃ ┣ 📂Arduino      
 ┃ ┃ ┣ 📂backup      
 ┃ ┃ ┃ ┗ 📜Ar_backup.py      
 ┃ ┃ ┣ 📂templates      
 ┃ ┃ ┃ ┗ 📜index.html      
 ┃ ┃ ┣ 📜Ar_serial.py      
 ┃ ┃ ┗ 📜device.py      
 ┃ ┣ 📂google      
 ┃ ┃ ┣ 📂templates      
 ┃ ┃ ┃ ┗ 📜userinfo.html      
 ┃ ┃ ┣ 📜google_account.py      
 ┃ ┃ ┣ 📜login.html      
 ┃ ┃ ┗ 📜youtube_live.py      
 ┃ ┣ 📂WebRTC      
 ┃ ┃ ┣ 📂static      
 ┃ ┃ ┃ ┣ 📜script.js      
 ┃ ┃ ┃ ┗ 📜style.css      
 ┃ ┃ ┣ 📂templates      
 ┃ ┃ ┃ ┗ 📜index.html      
 ┃ ┃ ┣ 📜main.py      
 ┃ ┃ ┗ 📜USB_cam.py           
 ┣ 📜.gitignore      
 ┣ 📜docker-compose.yml      
 ┣ 📜JMSPlant.db      
 ┣ 📜pytest.ini      
 ┣ 📜README.md      
 ┣ 📜requirements.txt      
 ┣ 📜setup_venv.bat      
 ┗ 📜setup_venv.sh      
---

## ⚡ 스마트팜 전력 배선 시스템

<table> 
      <tr> 
         <td><img src="https://lh3.googleusercontent.com/d/13ar-wA-7TMwUxgA23lSkwvVG2YBkz0Jr" width="100%"></td>
      <tr> 
      </tr> 
         <td><img src="https://lh3.googleusercontent.com/d/16K5b2SZef0kbdzVoox6DTChH2M7OzhQk" width="100%"></td>
      </tr> 
   </table>

## ⬇️ 전선배선도면.eddx

   [![스마트팜 프로젝트](https://lh3.googleusercontent.com/d/16YLoCCLto-hLLAYDK2dCux5KVayjZyTT)](https://drive.google.com/file/d/16HMf_8yOA0kCh1TgKVcjFiXK0HJdRApW/view?usp=sharing)

---

## 🐋 Docker

```bash
docker compose -f "docker-compose.yml" up -d --build
```
```
...

[+] Running 2/2
 ✔ Network jms_smart_farm_default         Created
 ✔ Container jms_smart_farm-python_app-1  Started
```

[🔗 Docker URL](http://localhost:8000/docs)


---

## 🛠️ setup_venv.bat

- 경로 : `./setup_venv.bat`
- Python 3.12.1 환경 => [설치](https://www.python.org/downloads/release/python-3121/)
  - 설치 시 Add Pyhton 3.12.1 to PATH 체크
- venv 가상화 실행 명령어

```bash
& ".\setup_venv.bat"
```

---

## 🛠️ setup_venv.sh

- 경로 : `./setup_venv.sh`
- Python 3.12.1 환경 => [설치](https://www.python.org/downloads/release/python-3121/)
  - 설치 시 Add Pyhton 3.12.1 to PATH 체크
- venv 가상화 실행 명령어

```bash
chmod +x setup_venv.sh
./setup_venv.sh
```

---


## 🔐 .env

- 경로 
   -  `./Py/google/.env`
   -  `./API/.env`

- .env 내용

```env
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
GOOGLE_PROJECT_ID=your_project_id
GOOGLE_AUTH_URI=https://accounts.google.com/o/oauth2/auth
GOOGLE_TOKEN_URI=https://oauth2.googleapis.com/token
GOOGLE_AUTH_PROVIDER_X509_CERT_URL=https://www.googleapis.com/oauth2/v1/certs
GOOGLE_REDIRECT_URIS=your_redirect_uris
GOOGLE_JAVASCRIPT_ORIGINS=your_javascript_origins
```
