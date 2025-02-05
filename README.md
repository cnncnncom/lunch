# 🍽️ 점심 메뉴 추천 웹 애플리케이션 🍜

이 프로젝트는 사용자가 입력한 텍스트를 기반으로 AI 모델이 점심 메뉴를 추천해주는 간단한 웹 애플리케이션입니다. 😋

---

## 🎯 주요 기능

✅ **AI 모델 선택**: `gemini-1.5-flash` 또는 `deepseek-r1` 모델을 선택하여 추천을 받을 수 있습니다.\
✅ **🍱 메뉴 추천 기능**: 입력한 텍스트를 기반으로 AI가 점심 메뉴를 추천합니다.\
✅ **🗂️ 저장 및 삭제 기능**: 추천받은 메뉴를 화면에 표시하고, 필요 시 삭제할 수 있습니다.\
✅ **💾 로컬 스토리지 활용**: 브라우저의 로컬 스토리지에 데이터를 저장하여 새로고침 후에도 유지됩니다.\
✅ **🧹 데이터 리셋 기능**: 저장된 데이터를 초기화할 수 있습니다.

---

## 🛠️ 기술 스택

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![LocalStorage](https://img.shields.io/badge/LocalStorage-4CAF50?style=for-the-badge&logo=google-chrome&logoColor=white)
![API](https://img.shields.io/badge/API-FF9800?style=for-the-badge&logo=postman&logoColor=white)

---

## 🚀 실행 방법
1️⃣ 프로젝트 파일을 다운로드 후 `index.html` 파일을 브라우저에서 엽니다.\
2️⃣ 원하는 AI 모델을 선택합니다.\
3️⃣ 추천받고 싶은 내용을 입력한 후 `등록` 버튼을 클릭합니다.\
4️⃣ AI가 추천한 점심 메뉴를 확인하고 필요하면 삭제할 수 있습니다.\
5️⃣ `🗑️ 저장된 데이터 리셋` 버튼을 클릭하면 모든 저장된 데이터가 초기화됩니다.\

---

## 📢 API 요청 방식
🔗 **요청 URL**  
🔹 `gemini-1.5-flash`: `https://spotted-famous-seaplane.glitch.me/1`  
🔹 `deepseek-r1`: `https://spotted-famous-seaplane.glitch.me/2`  

📩 **요청 형식 (POST)**  
```json
{
  "text": "너는 20년 경력의 메뉴 추천 전문가야. {입력 텍스트}의 메시지를 바탕으로, 점심 메뉴를 추천해주고, 50자 이내에 평문으로 작성해줘."
}
```

📜 **응답 형식 (JSON)**  
```json
{
  "reply": "추천 메뉴"
}
```

---

## 📂 파일 구조
```
📁 프로젝트 폴더
├── index.html  # 메인 웹 페이지 (점심 메뉴 추천 기능 포함)
```

---

## ✨ 추가 개선 사항 제안
💡 **API 응답 오류 처리 추가**  
💡 **🎨 UI 디자인 개선 (CSS 활용)**  
💡 **🍕 추천된 메뉴를 카테고리별로 정리하는 기능 추가**  
💡 **📊 더 다양한 AI 모델 지원**  

이 프로젝트는 간단한 JavaScript 연습 및 API 활용을 위한 목적으로 제작되었습니다. 누구든지 자유롭게 수정하고 개선할 수 있습니다! 🎉

