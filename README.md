# gemini-Discord-gemini-bot

어서오세요!  
비전문가가 만든 Node.js 기반 Discord 봇입니다.  
아이디어는 제 것이지만, 코딩은 AI의 도움을 받았습니다.

(안타깝게도 저는 호스팅 사이트를 사용해서 os별 설치법이 완전 작동하다고는 보증 못합니다)  
(그리고 추후에 보증을 하도록 하겠습니다 보증한 os는 옆에 🛡️붙여놓을게용!)

---

## 🔗 OS별 설치법

### 🪟 Windows

1. [Node.js 18 버전 설치](https://nodejs.org/) (관리자 권한으로 진행하세요!!)
   - 설치 후, 터미널(명령 프롬프트/PowerShell)에서 아래 명령어로 정상 설치 확인:
   ```bash
   node --version
   ```

2. 프로젝트 폴더로 이동:
   ```bash
   cd <파일_경로>
   ```

3. 의존성 설치:
   ```bash
   npm install
   ```

4. `.env` 파일에 API 키(토큰 등) 입력

5. 실행:
   ```bash
   node bot.js
   ```

---

### 🐧 Ubuntu

1. 시스템 업데이트:
   ```bash
   sudo apt update
   ```

2. Node.js 및 npm 설치:
   ```bash
   sudo apt install -y nodejs npm
   ```
   설치 후 버전 확인:
   ```bash
   node --version
   npm --version
   ```

3. 프로젝트 폴더로 이동:
   ```bash
   cd <프로젝트_폴더>
   ```

4. 의존성 설치:
   ```bash
   npm install
   ```

5. `.env` 파일에 API 키(토큰 등) 입력  
   - `.env` 파일 작성법은 Windows와 동일합니다.

6. 실행:
   ```bash
   node bot.js
   ```

---

### 📱 Termux (Android)

1. 패키지 업데이트:
   ```bash
   pkg update && pkg upgrade
   ```

2. Node.js 설치:
   ```bash
   pkg install nodejs
   ```

3. 프로젝트 폴더로 이동:
   ```bash
   cd <프로젝트_폴더>
   ```

4. 의존성 설치:
   ```bash
   npm install
   ```

5. `.env` 파일에 API 키(토큰 등) 입력  
   - Termux에서도 `.env` 파일 위치와 작성법은 동일합니다.

6. 실행:
   ```bash
   node bot.js
   ```

---

# gemini-Discord-gemini-bot

Welcome!  
This is a Node.js-based Discord bot made by a non-expert.  
The idea is mine, but I got help from AI for the coding.

(Unfortunately, since I'm personally using a hosting service, I can't guarantee that the installation process will work perfectly on every OS.)  
(I'll try to provide OS-specific guarantees in the future. Once verified, I'll mark supported OSes with a 🛡️ symbol!)

---

## 🔗 Installation Guide by OS

### 🪟 Windows

1. [Install Node.js version 18](https://nodejs.org/) (Please proceed with administrator rights!!)
   - After installation, verify by running the following command in Command Prompt or PowerShell:
   ```bash
   node --version
   ```

2. Move to the project folder:
   ```bash
   cd <project_path>
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Enter your API key (e.g., token) in the `.env` file

5. Run the bot:
   ```bash
   node bot.js
   ```

---

### 🐧 Ubuntu

1. Update the system:
   ```bash
   sudo apt update
   ```

2. Install Node.js and npm:
   ```bash
   sudo apt install -y nodejs npm
   ```
   After installation, verify with:
   ```bash
   node --version
   npm --version
   ```

3. Move to the project folder:
   ```bash
   cd <project_folder>
   ```

4. Install dependencies:
   ```bash
   npm install
   ```

5. Enter your API key (e.g., token) in the `.env` file  
   - The `.env` format is the same as on Windows.

6. Run the bot:
   ```bash
   node bot.js
   ```

---

### 📱 Termux (Android)

1. Update packages:
   ```bash
   pkg update && pkg upgrade
   ```

2. Install Node.js:
   ```bash
   pkg install nodejs
   ```

3. Move to the project folder:
   ```bash
   cd <project_folder>
   ```

4. Install dependencies:
   ```bash
   npm install
   ```

5. Enter your API key (e.g., token) in the `.env` file  
   - The `.env` location and format are the same as other platforms.

6. Run the bot:
   ```bash
   node bot.js
   ```

