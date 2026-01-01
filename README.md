<div align="center">
  <!-- 상단 네비게이션 바 모사 -->
  <img src="https://capsule-render.vercel.app/render?type=rect&color=ffffff&height=80&section=header&text=SUNDAY%20×%20JINMAN&fontSize=30&fontColor=000000" width="100%"/>

  <br/>

  <!-- HERO SECTION: Spline 로봇과 메인 타이틀 -->
  <!-- 팁: Spline에서 해당 로봇을 투명 배경 GIF로 추출하여 아래 경로에 넣으세요 -->
  <img src="https://your-spline-gif-url.gif" width="600" />
  
  <h1 style="font-size: 80px;">Say hello to Jinman</h1>
  <p style="font-size: 20px; color: #888;">The helpful AI & Robotics Researcher. <br/> Making complex technology lighter for real life.</p>
  
  <br/>
  <a href="mailto:ggzgcode10000@gmail.com">
    <img src="https://img.shields.io/badge/Apply_to_Collaborate-F3E151?style=for-the-badge&logo=mail&logoColor=black" />
  </a>
</div>

<br/><br/>

---

## ✨ Logic made magic
"전진만은 단순한 코드를 넘어, 일상을 변화시키는 지능을 설계합니다."

<table width="100%" border="0">
  <tr>
    <td width="50%" style="vertical-align: top;">
      <br/><br/>
      <h2 style="font-size: 40px;">Jinman works in the Robotics</h2>
      <p style="font-size: 16px; color: #666; line-height: 1.6;">
        <b>머신러닝과 로보틱스</b>의 경계를 허뭅니다. <br/>
        LLM과 VLA(Vision Language Action) 모델을 통해 <br/>
        로봇이 세상을 이해하고 스스로 행동하게 만드는 <br/>
        핵심 알고리즘을 연구합니다.
      </p>
    </td>
    <td width="50%">
      <!-- 제공해주신 이미지 중 로봇이 작업하는 이미지를 배치 -->
      <img src="https://your-image-link/robot-kitchen.jpg" width="100%" style="border-radius: 20px;" />
    </td>
  </tr>
</table>

<br/>

## 🛠 Skill Library (From imitation to intuition)
"Our Intelligence enables Memo to distill millions of human movements..." 문구를 인용한 기술 스택 섹션입니다.

<table width="100%">
  <tr>
    <td align="center" style="background-color: #f5f5f7; border-radius: 15px; padding: 20px;">
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
      <img src="https://img.shields.io/badge/LangChain-121212?style=flat-square&logo=chainlink&logoColor=white"/>
      <br/><b>Core Brain</b>
    </td>
    <td align="center" style="background-color: #f5f5f7; border-radius: 15px; padding: 20px;">
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white"/>
      <br/><b>Deployment</b>
    </td>
  </tr>
</table>

<br/>

## 🚀 Designed for real use (Projects & Awards)
제공해주신 이미지 하단의 카드 디자인을 활용한 프로젝트 나열입니다.

| <img src="https://your-image-link/project1.jpg" width="300"/><br/>**산재패스 서비스** | <img src="https://your-image-link/project2.jpg" width="300"/><br/>**유사 판정서 추천** | <img src="https://your-image-link/project3.jpg" width="300"/><br/>**장애인식 개선 LLM** |
| :--- | :--- | :--- |
| 고용노동부 장려상 | 근로복지연구원장상 | SNS 자동화 시스템 |

<br/>

### 🏆 Honors & Paper
- 📄 **Paper:** 태양광 발전량 예측을 위한 GA 기반 최적화 연구 (정보과학회 논문지)
- 🥇 **Awards:** AI 결합 수업 추천 우수상, AI경진대회 동상
- 🎓 **Certs:** ADSP, SQLD 보유

<br/>

<div align="center">
  <img src="https://render.gitanimals.org/lines/codemillss?pet-id=1" width="1000" height="120"/>
  <p style="color: #aaa;">Sunday, Jan 02 • Mountain View, CA • 45°F</p>
</div>


import React from 'react';
import Spline from '@splinetool/react-spline';

const Portfolio = () => {
  return (
    <div className="bg-white text-zinc-900 font-sans">
      {/* Hero Section */}
      <section className="h-screen relative flex items-center justify-center border-b border-zinc-100">
        <div className="absolute inset-0">
          <Spline scene="https://prod.spline.design/KFOE94cabK3ubctFT3K7AR9V/scene.splinecode" />
        </div>
        <div className="relative z-10 text-center">
          <h1 className="text-[120px] font-bold tracking-tighter leading-none">Say hello to Jinman</h1>
          <p className="text-xl mt-8 text-zinc-500">The helpful AI & Robotics researcher.</p>
          <button className="mt-12 bg-[#F3E151] text-black px-10 py-4 rounded-full font-bold">Apply to Collaborate</button>
        </div>
      </section>

      {/* Mundane Section (이미지/텍스트 레이아웃) */}
      <section className="py-40 px-20 max-w-7xl mx-auto">
        <h2 className="text-7xl font-bold mb-20">Logic made magic</h2>
        <div className="grid grid-cols-2 gap-20">
          <div>
            <img src="이미지_로봇_주방.jpg" className="rounded-3xl shadow-2xl" />
            <h3 className="text-3xl font-bold mt-10">Jinman works in the Lab</h3>
            <p className="mt-4 text-zinc-500">산업재해 데이터부터 LLM 기반 지능형 시스템까지, 실질적인 가치를 창출합니다.</p>
          </div>
          <div className="pt-40">
            <img src="이미지_로봇_거실.jpg" className="rounded-3xl shadow-2xl" />
            <h3 className="text-3xl font-bold mt-10">Designed for real use</h3>
            <p className="mt-4 text-zinc-500">복잡한 기술을 일상의 언어로 풀어내는 것이 전진만의 철학입니다.</p>
          </div>
        </div>
      </section>

      {/* Awards Section (Sunday 사이트 하단 블랙 카드 모사) */}
      <section className="bg-zinc-900 text-white py-32 px-20 rounded-[3rem] mx-10 mb-20">
        <div className="grid grid-cols-3 gap-10">
          <div>
            <h4 className="text-[#F3E151] uppercase tracking-widest text-sm mb-4">Award 01</h4>
            <p className="text-2xl font-bold">고용노동부 장려상</p>
            <p className="text-zinc-500 mt-2">산업재해 신속 처리 산재패스 서비스</p>
          </div>
          {/* ... 반복 ... */}
        </div>
      </section>

      {/* Footer (Sunday 사이트 하단 옐로우 모사) */}
      <footer className="bg-[#F3E151] py-10 px-20 flex justify-between items-center text-sm font-bold uppercase">
        <div>Friday, Jan 02 • Mountain View, CA • 45°F</div>
        <div>Sunday × Jinman Jeon</div>
        <div>Curated by Codemillss</div>
      </footer>
    </div>
  );
};
