# 32평 거실 사진 보정 검토

2026-11-09. 내장 image_gen 도구로 두 번 보정을 시도했다. 원본 images/p32-04-after.jpg는 유지했다. 두 결과 모두 세부 묘사가 달라져 홈페이지 사진으로 채택하지 않았다.

## 최종 시도 프롬프트

Conservative photographic edit of THIS EXACT PHOTO, not a reconstruction or a rendering. Apply ONLY a very subtle global white balance shift to reduce blue in the floor, and a slight exposure lift of about 0.25 stop. Keep original 480x600 framing and every original pixel-level feature in place: the view angle, ceiling fan including number and shape of blades, tile grout pattern, left wall niche wires, every window vertical and horizontal mullion, exterior buildings and tree shapes, arched recess, all lights and surfaces. NO sharpening/super-resolution hallucination, NO perspective change, NO geometry change, NO object edits, NO extra details. The edited image must look essentially identical to original except gently warmer color and gently brighter exposure. Preserve the original low-resolution photo character. Do not regenerate the scene. No staging or decor. Do not crop.

## 다음 단계

사용자에게 원본 픽셀의 밝기·색감만 조정하는 일반 사진 보정 방식으로 진행할지 질문했다. 답변 전까지 사진 교체는 보류한다.

## 채택한 일반 사진 보정

2026-11-09. 사용자가 일반 사진 보정을 명시적으로 선택했다. System.Drawing으로 원본 480×600 크기를 유지하며 RGB 배율 1.025/1.015/0.98, 채널별 밝기 가산 0.008, 감마 0.94을 적용했다. JPEG 품질 95로 images/p32-04-after-retouched.jpg에 별도 저장했다. 구도·물체·무늬·픽셀 위치는 바꾸지 않았고 원본을 보존했다. AI 생성 시안 두 장은 사용하지 않았다.

