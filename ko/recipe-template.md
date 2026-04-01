---
layout: post
title: "AI로 만든 황금 레시피: [요리 이름 입력]"
date: 2026-04-01
lang: ko  # 영문일 경우 en으로 변경
image: "https://your-github-id.github.io/assets/images/recipe-main.jpg" # AI 생성 이미지 경로
youtube_id: "YOUTUBE_VIDEO_ID" # 유튜브 영상 ID만 입력
prep_time: "PT15M" # 준비 시간 (ISO 8601 형식, 예: 15분은 PT15M)
cook_time: "PT30M" # 조리 시간 (예: 30분은 PT30M)
calories: "450 kcal"
description: "AI가 분석한 전 세계에서 가장 맛있는 [요리 이름] 레시피입니다. 집에서도 전문가처럼 만들어보세요."
---

## 📺 조리 영상 안내
<div class="video-container">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/{{ page.youtube_id }}" frameborder="0" allowfullscreen></iframe>
</div>

---

## 📊 요리 정보
* **준비 시간:** 15분
* **조리 시간:** 30분
* **칼로리:** {{ page.calories }}
* **난이도:** 보통 ⭐⭐⭐

---

## 🛒 필요한 재료 (Ingredients)
제미나이가 추천하는 최상급 식재료입니다. (링크 클릭 시 최저가 구매 가능)

* **주재료 A (300g):** [쿠팡 파트너스 링크](https://link.coupang.com/...) / [Amazon Link](https://www.amazon.com/...)
* **부재료 B (2스푼):** [쿠팡 파트너스 링크](https://link.coupang.com/...) / [Amazon Link](https://www.amazon.com/...)
* **필수 양념 C:** [쿠팡 파트너스 링크](https://link.coupang.com/...)

---

## 👨‍🍳 조리 순서 (Step-by-Step)
1.  **준비 단계:** AI가 생성한 첫 번째 조리 가이드를 여기에 적습니다.
2.  **가열 단계:** 팬을 달구고 재료를 넣는 과정을 상세히 설명합니다.
3.  **마무리:** 완성된 요리를 예쁘게 담는 팁을 추가합니다.

---

<script type="application/ld+json">
{
  "@context": "https://schema.org/",
  "@type": "Recipe",
  "name": "{{ page.title }}",
  "image": [ "{{ page.image }}" ],
  "author": {
    "@type": "Person",
    "name": "Mun Jong-dae"
  },
  "datePublished": "{{ page.date | date_to_xmlschema }}",
  "description": "{{ page.description }}",
  "prepTime": "{{ page.prep_time }}",
  "cookTime": "{{ page.cook_time }}",
  "totalTime": "PT45M",
  "keywords": "레시피, 요리, AI 레시피, 쿠킹",
  "recipeYield": "2인분",
  "recipeCategory": "Main Dish",
  "recipeCuisine": "Korean",
  "nutrition": {
    "@type": "NutritionInformation",
    "calories": "{{ page.calories }}"
  },
  "recipeIngredient": [
    "주재료 A 300g",
    "부재료 B 2스푼",
    "양념 C"
  ],
  "recipeInstructions": [
    {
      "@type": "HowToStep",
      "text": "준비 단계 설명을 넣으세요."
    },
    {
      "@type": "HowToStep",
      "text": "조리 단계 설명을 넣으세요."
    }
  ],
  "video": {
    "@type": "VideoObject",
    "name": "{{ page.title }} 영상",
    "description": "{{ page.description }}",
    "thumbnailUrl": [ "{{ page.image }}" ],
    "contentUrl": "https://www.youtube.com/watch?v={{ page.youtube_id }}",
    "embedUrl": "https://www.youtube.com/embed/{{ page.youtube_id }}",
    "uploadDate": "{{ page.date | date_to_xmlschema }}"
  }
}
</script>
