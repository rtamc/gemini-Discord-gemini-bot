# gemini-Discord-gemini-bot

어서오세요!  
비전문가가 만든 Node.js 기반 Discord 봇입니다.  
아이디어는 제 것이지만, 코딩은 AI의 도움을 받았습니다.

(안타깝게도 저는 호스팅 사이트를 사용해서 OS별 설치법이 완전 작동한다고는 보증 못합니다)  
(그리고 추후에 보증을 하도록 하겠습니다. 보증한 OS는 옆에 🛡️ 표시할게요!)

---

## 🔗 OS별 설치법

### 🪟 Windows

0-1. notepad++(https://notepad-plus-plus.org/downloads/) [ 다운받아서 사용하시길 (.env 열때 메모장 쓰셔도 되긴해요..]
1. [Node.js 18 버전 설치](https://nodejs.org/) (관리자 권한으로 진행하세요!!)
   - 설치 후, 터미널(명령 프롬프트 또는 PowerShell)에서 아래 명령어로 정상 설치 확인:
     ```bash
     node --version
     ```

2. 파일 다운로드:  
   [https://github.com/rtamc/gemini-Discord-gemini-bot/releases/tag/Latest](https://github.com/rtamc/gemini-Discord-gemini-bot/releases/tag/Latest)

3. 압축 해제

4. PowerShell을 **관리자 권한**으로 실행

5. 경로 이동 (예: 압축한 경로가 `C:\Users\user`인 경우)
   ```bash
   cd C:\Users\user
   ```

6. 의존성 설치
   ```bash
   npm install
   ```

7. `.env` 파일에 API 키(토큰 등) 입력

8. 실행
   ```bash
   node bot.js
   ```

---

### 🐧 Ubuntu

1. wget 설치
   ```bash
   sudo apt install wget
   ```

2. Node.js 및 npm 설치
   ```bash
   sudo apt update
   sudo apt install -y nodejs npm
   ```

3. 파일 다운로드
   ```bash
   wget https://github.com/rtamc/gemini-Discord-gemini-bot/releases/download/Latest/gemini-bot-kr-1.0.zip
   ```

4. 압축 해제 및 경로 이동
   ```bash
   unzip gemini-bot-kr-1.0.zip
   cd gemini-bot-kr-1.0
   ```

5. 의존성 설치
   ```bash
   npm install
   ```

6. `.env` 파일에 API 키(토큰 등) 입력

7. 실행
   ```bash
   node bot.js
   ```

---

### 📱 Termux (Android)

1. wget 설치
   ```bash
   pkg install wget
   ```

2. Node.js 설치
   ```bash
   pkg install nodejs
   ```

3. 파일 다운로드
   ```bash
   wget https://github.com/rtamc/gemini-Discord-gemini-bot/releases/download/Latest/gemini-bot-kr-1.0.zip
   ```

4. 압축 해제 및 경로 이동
   ```bash
   unzip gemini-bot-kr-1.0.zip
   cd gemini-bot-kr-1.0
   ```

5. 의존성 설치
   ```bash
   npm install
   ```

6. `.env` 파일에 API 키(토큰 등) 입력

7. 실행
   ```bash
   node bot.js
   ```
---
   # gemini-Discord-gemini-bot

Welcome!  
This is a Node.js-based Discord bot created by a non-expert.  
The ideas are mine, but I got help from AI to write the code.

(*Note: I use a hosting platform, so I can't guarantee that these installation steps work perfectly on every OS.  
Once tested, I’ll mark verified OSes with a 🛡️ symbol.*)

---

## 🔗 Installation Guide by OS

### 🪟 Windows
0-1. Notepad++ (https://notepad-plus-plus.org/downloads/) [Download and use it. (You can also use Notepad to open .env files if you prefer.)]
1. Install [Node.js (version 18)](https://nodejs.org/) (Run as Administrator!)  
   - After installation, verify with:
     ```bash
     node --version
     ```

2. Download the release file:  
   [https://github.com/rtamc/gemini-Discord-gemini-bot/releases/tag/Latest](https://github.com/rtamc/gemini-Discord-gemini-bot/releases/tag/Latest)

3. Extract the ZIP file.

4. Open PowerShell as **Administrator**.

5. Move to the extracted folder path (e.g., `C:\Users\user`)
   ```bash
   cd C:\Users\user
   ```

6. Install dependencies
   ```bash
   npm install
   ```

7. Create and fill in the `.env` file with your API keys (e.g., Discord token)

8. Run the bot
   ```bash
   node bot.js
   ```

---

### 🐧 Ubuntu

1. Install `wget`
   ```bash
   sudo apt install wget
   ```

2. Install Node.js and npm
   ```bash
   sudo apt update
   sudo apt install -y nodejs npm
   ```

3. Download the bot ZIP file
   ```bash
   wget https://github.com/rtamc/gemini-Discord-gemini-bot/releases/download/Latest/gemini-bot-en-1.0.zip
   ```

4. Unzip and move into the folder
   ```bash
   unzip gemini-bot-kr-1.0.zip
   cd gemini-bot-kr-1.0
   ```

5. Install dependencies
   ```bash
   npm install
   ```

6. Create and fill in the `.env` file with your API keys

7. Run the bot
   ```bash
   node bot.js
   ```

---

### 📱 Termux (Android)

1. Install `wget`
   ```bash
   pkg install wget
   ```

2. Install Node.js
   ```bash
   pkg install nodejs
   ```

3. Download the bot ZIP file
   ```bash
   wget https://github.com/rtamc/gemini-Discord-gemini-bot/releases/download/Latest/gemini-bot-en-1.0.zip
   ```

4. Unzip and move into the folder
   ```bash
   unzip gemini-bot-kr-1.0.zip
   cd gemini-bot-kr-1.0
   ```

5. Install dependencies
   ```bash
   npm install
   ```

6. Create and fill in the `.env` file with your API keys

7. Run the bot
   ```bash
   node bot.js
   ```

