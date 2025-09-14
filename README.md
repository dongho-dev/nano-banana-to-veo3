# 컴퓨터공학과 21학번 60212256 황동호 딥러닝 기본설정[HW0] 과제

## nano-banana 사진 변환 프롬프트(원본)

“A photorealistic 3D movie still of a futuristic humanoid robot on a skyscraper rooftop at dawn in light drizzle and mist. Wet concrete reflects teal and magenta neon. The robot, with cold metallic brushed-aluminum panels and light wear, lifts an industrial fusion-battery crate overhead with both hands. Purple electric arcs (low intensity) flow from the robot’s hands into the object. Rim lighting around the silhouette, volumetric fog, distant skyline filled with drone taxis, airships, and floating sky islands. Rule-of-thirds composition, low angle, 24mm lens, shallow depth of field, subtle motion blur, HDR detail, cinematic sci-fi atmosphere.”

Negative: text, logos, watermark, extra or deformed fingers, distorted hands, artifacts, low-res, heavy blur, oversaturation, banding, chromatic aberration.

Output: aspect ratio 16:9, size 1024×576 px (long edge 1024).

## nano-banana 사진 변환 프롬프트(한국어)
“포토리얼 3D 영화 스틸 느낌의 장면. 고층 빌딩 옥상, 새벽의 안개비, 젖은 바닥에 청록·마젠타 네온 반사. 차갑고 금속적인 브러시드 알루미늄 질감의 휴머노이드 로봇이 양손으로 산업용 융합 배터리 상자를 머리 위로 들어 올리는 포즈. 보라색 전기 아크(약한 강도)가 손에서 물체로 흐름. 림라이트, 볼류메트릭 포그, 멀리 드론 택시·비행정·하늘섬이 보이는 스카이라인. 삼등분 구도, 로우 앵글·24mm, 얕은 심도, 약한 모션 블러, HDR 디테일, 시네마틱 SF 분위기.”

네거티브: 텍스트, 로고, 워터마크, 여분/기형 손가락, 왜곡된 손, 아티팩트, 저해상도, 과도한 블러, 과채도, 밴딩, 색수차.

출력: 비율 16:9, 크기 1024×576 px.

## veo3 영상 변환 프롬프트(원본)
8-second cinematic photorealistic 3D sci-fi, 16:9, 24fps.

Rainy, misty skyscraper rooftop at dawn, wet concrete with teal/magenta neon reflections. Distant skyline with airships and drone taxis moving slowly. A cold metallic humanoid (brushed aluminum, light wear) holds an industrial crate overhead.
Action: 0–3s, purple electric arcs stay continuously connected from hands to crate and intensify. 3–4.5s, a short upward toss, the crate rises 1–2 m with light motion blur. Arcs remain attached until the moment of release, then thin to filaments and fade as the crate moves away (no arcs once separated). ~4.5s, a thin docking beam descends and captures the crate; 6–7s it is pulled up and exits the top of frame. Reward: after the exit, a small holographic token (no text) descends from the beam, hovers over the palm, then slots into the robot’s chest port, triggering a brief teal/magenta confirmation pulse along panel seams. 7–8s, violet embers flicker around the hands and fade.
Camera: slow crane-up + slight dolly-in, low angle, rule-of-thirds, shallow DOF.
Lighting/FX: rim light, volumetric fog, gentle rain streaks and reflections.
Negative: text, numbers, logos, watermarks, HUD readouts, deformed/extra fingers, heavy flicker, jitter, artifacts, low-res.

## veo3 영상 변환 프롬프트(한국어)
8초 시네마틱 포토리얼 3D SF, 16:9, 24fps.
새벽 안개비 내리는 고층 옥상, 젖은 바닥에 청록/마젠타 네온 반사. 멀리 비행선과 드론 택시가 천천히 이동. 차갑고 금속적인 휴머노이드(브러시드 알루미늄, 약한 사용감)가 산업용 크레이트를 머리 위로 들고 있다.
액션: 0–3초, 손–크레이트 전기 아크가 끊기지 않고 유지되며 강화. 3–4.5초, 짧게 위로 ‘툭’ 던져 1–2 m 상승(약한 모션 블러). 분리 순간까지 아크 유지, 이후 가는 실처럼 얇아지며 멀어질수록 페이드(분리되면 아크 없음). 약 4.5초, 얇은 도킹 빔이 내려와 포착, 6–7초에 프레임 상단으로 이탈. 보상: 이탈 직후 작은 홀로그램 토큰(텍스트 없음)이 빔에서 내려와 손바닥 위에 떠 있다가 가슴 포트로 흡수, 청록/마젠타 확인 펄스가 패널 이음새를 따라 한 번 퍼진다. 7–8초, 손 주변 보라 잔불꽃이 타닥이며 사라진다.
카메라: 느린 크레인업 + 약한 돌리인, 로우 앵글, 삼등분, 얕은 심도.
라이트/FX: 림라이트, 볼류메트릭 포그, 부드러운 비 줄기와 반사.
네거티브: 텍스트/숫자/HUD, 로고, 워터마크, 변형 손가락, 심한 플리커, 떨림, 아티팩트, 저해상도.
