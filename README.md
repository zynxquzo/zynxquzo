<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8addfd,100:fad0c1&height=120&text=🐻‍❄️%20AI%2FLLM%20Engineer%20in%20Progress%20🚀&animation=&fontColor=5c5c5c&fontSize=35" />

## 🌐 Socials
[![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:prettymysky@gmail.com)


## 💻 Tech Stack

**AI & Agent**<br/>
![LangGraph](https://img.shields.io/badge/langgraph-%231C3C3C.svg?style=plastic&logo=langgraph&logoColor=white) ![LangChain](https://img.shields.io/badge/langchain-%231C3C3C.svg?style=plastic&logo=langchain&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=plastic&logo=openai&logoColor=white) ![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=plastic&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-8addfd?style=plastic&logoColor=333333) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=plastic&logo=pytorch&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=plastic&logo=huggingface&logoColor=black) ![LoRA/QLoRA](https://img.shields.io/badge/LoRA%2FQLoRA-8addfd?style=plastic&logoColor=333333) ![GGUF](https://img.shields.io/badge/GGUF-333333?style=plastic&logoColor=white)

**Frontend**<br/>
![CSS](https://img.shields.io/badge/css3-%231572B6.svg?style=plastic&logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=plastic&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=plastic&logo=javascript&logoColor=%23F7DF1E) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=plastic&logo=react&logoColor=%2361DAFB)

**Backend**<br/>
![Python](https://img.shields.io/badge/python-3670A0?style=plastic&logo=python&logoColor=ffdd54) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=plastic&logo=fastapi) ![Uvicorn](https://img.shields.io/badge/Uvicorn-2496ED?style=plastic&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=plastic&logo=nodedotjs&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=plastic&logo=ollama&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=plastic&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=plastic&logo=redis&logoColor=white)

**DevTools**<br/>
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=plastic&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=plastic&logo=github&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=plastic&logo=postman&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=plastic&logo=gnubash&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=plastic&logo=docker&logoColor=white) ![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=plastic&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=plastic&logo=nginx&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=plastic&logo=railway&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=plastic&logo=supabase&logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=plastic&logo=googlecloud&logoColor=white) ![Let's Encrypt](https://img.shields.io/badge/Let's%20Encrypt-003A70?style=plastic&logo=letsencrypt&logoColor=white)

**Environment & Others**<br/>
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=plastic&logo=visualstudiocode&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=plastic&logo=notion&logoColor=white)


</div>

## 🚀 Projects

### [HR Copilot](https://github.com/bamti95/hr-copilot)
LangGraph 기반 9-node 멀티에이전트 RAG 파이프라인으로 HR 문서 검토·QA를 자동화하는 시스템
- BM25 + BGE-M3 + Reranker 하이브리드 RAG로 검색 정확도 향상
- 토큰 사용량 34.5% 절감 (100,166 → 65,630 tokens)
- High-risk 항목 Recall 66.7% → 100% 개선
- FastAPI + PostgreSQL 백엔드, Review Router 재시도 루프 최적화

`Python` `LangGraph` `FastAPI` `PostgreSQL`

---

### [ICN Flight Alert](https://github.com/zynxquzo/icn-flight-alert)
인천공항 항공편 정보를 안내하는 RAG 기반 공항 챗봇

[![Live Demo](https://img.shields.io/badge/Live%20Demo-icnflightalert.site-8addfd?style=plastic&logo=vercel&logoColor=white)](https://icnflightalert.site)

- 하이브리드 RAG 구조 재설계로 검색 병목 75% 개선
- Function Calling 기반 에이전트로 실시간 항공편 조회
- APScheduler로 항공편 상태 모니터링 및 알림
- pgvector + ChromaDB 벡터 스토어 이중 구성

`Python` `FastAPI` `pgvector` `ChromaDB`

---

### [TradeCode-LoRA](https://github.com/zynxquzo/tradecode-lora)
Gemma2-2B LoRA 파인튜닝 기반 HS 코드(품목분류코드) 자동 분류 모델
- Mode collapse(클래스 불균형) 원인 진단 및 해결로 정확도 1.87% → 93.46% 회복
- QLoRA 재설계, GGUF 변환, Ollama 로컬 서빙까지 엔드투엔드 구현
- Kaggle 스모크 테스트에서 학습 손실 26.9 → 14.09 감소 확인

`Python` `LoRA/QLoRA` `Gemma2` `Ollama`

<div align="center">

## 📊 GitHub Stats
![](https://github-stats-extended.vercel.app/api?username=zynxquzo&theme=graywhite&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=zynxquzo&theme=graywhite&hide_border=false)<br/>
![](https://github-stats-extended.vercel.app/api/top-langs/?username=zynxquzo&theme=graywhite&hide_border=false&include_all_commits=false&count_private=false&layout=compact)


##
![](https://komarev.com/ghpvc/?username=zynxquzo&color=yellow)
</div>

