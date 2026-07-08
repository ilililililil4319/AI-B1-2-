# AI-B1-2-과제

AI 기반 브랜드 광고 패키지 기획서 (줄글 버전)

GenAI 기초 2 : 멀티모달 콘텐츠 제작 — 브랜드 RAUM(라움), 무선 저소음 헤어드라이기


1. 브랜드 기획

이번 기획서에서 다루는 가상 브랜드는 **RAUM(라움)**이며, 제품은 무선 저소음 헤어드라이기이다. RAUM이라는 이름은 발음이 짧고 국내외 누구나 쉽게 읽을 수 있도록 만든 글로벌 지향 브랜드명이다. 타깃은 20~30대의 1인 가구와 직장인으로, 아침 시간이 촉박하고 소음에 민감하며 미니멀한 라이프스타일을 선호하는 소비자층을 겨냥한다. 이 제품의 차별점(USP)은 무선의 자유로움에 업계 최저 수준의 저소음 설계를 더해 "조용해서 더 편안한 아침"을 만든다는 데 있다. 브랜드의 톤앤매너는 미니멀하고 프리미엄한 느낌을 지향하며, 라벤더·화이트·실버 계열의 차분하고 세련된 색감을 사용한다. 광고 전체를 관통하는 핵심 메시지는 "무선의 자유와 저소음으로 아침을 더욱 편안하게 만든다"는 한 문장으로 정리된다.

브랜드의 로고 컨셉은 둥근 바람의 곡선과 드라이기의 실루엣을 결합한 미니멀한 심볼로, 화이트·라이트블루·실버 배색을 사용해 작은 화면에서도 잘 인지되도록 설계하였다. 슬로건은 "선 없이, 더 조용하게."이며, CTA는 "지금, RAUM을 만나보세요."이다.

이 광고의 기획 의도는 다음과 같다. 기존 유선 드라이기가 가진 전선의 불편함과 소음 문제를 짧고 강하게 제시한 뒤, RAUM의 무선성과 저소음 기능으로 그 문제가 자연스럽게 해결되는 과정을 10초 영상으로 전달하는 것이다. 스토리라인은 문제 제시 → 해결 → 브랜드 인식으로 이어지는 기승전결 구조로 구성하였다.


2. AI 도구 활용 계획 및 선정 이유

이번 과제에서 사용한 AI 도구는 용도별로 다음과 같이 하나씩 명확하게 확정하였다(별도의 대체 도구는 사용하지 않음).


기획안(텍스트 기획) : Gemini / GPT / Claude — 브랜드 콘셉트·핵심 메시지·스토리보드 문서화 및 내레이션 초안 작성에 세 도구를 함께 활용하였다.
이미지 생성 : Gemini — 장면별 키비주얼과 제품 히어로샷을 생성하였다. 이전 장면의 이미지를 참조 이미지로 함께 입력해 인물·스타일 일관성을 유지하고, 브랜드명(RAUM)·로고 같은 텍스트 요소를 이미지 안에 정확하게 렌더링할 수 있었다.
영상 생성 : Runway — 회원가입 시 무료 크레딧을 받아 AI 이미지를 AI 영상으로 변환하였다. 작업 순서는 [Custom] → 이미지 업로드 → 미리 준비한 프롬프트 입력 → 모델을 [Gen-4 Turbo]로 설정 → [Generate] 순으로 진행하였다.
자막·나레이션·편집(통합) : VideoStew — 회원가입 시 무료 크레딧을 받을 수 있으며, 작업 순서는 [비주얼]→[사용자] 탭에서 Gemini·Runway로 생성해 둔 이미지/영상을 업로드 → 슬라이드에 추가 → 나레이션·자막·BGM·전환 편집 → 최종 영상 렌더링 후 다운로드(다운로드 시 크레딧 차감)하는 방식이다. CapCut은 사용하지 않는다. 나레이션은 AI 보이스 **'가현'**을 사용했고, 자막 폰트는 **'카페24 클래식타입'**을 적용했으며, 배경음악은 씬 구성에 맞춰 2개의 트랙을 슬라이드별로 나누어 사용하였다(Scene 1: NAVY CLOUD - feat. 사도, Scene 2~3: 큐디드라이 - EDM). 슬라이드 간 전환효과는 Auto로 설정하였다.



2-1. 실제 작업 화면

이미지 표시
Runway 작업 화면 : Custom → 이미지 업로드 → 프롬프트 입력 → Gen-4 Turbo → Generate (영상 생성 진행률 75% 표시)

이미지 표시
VideoStew 작업 화면 : Scene 2 슬라이드 편집 중 — 자막·나레이션 "선 없이 더욱 자유롭게, 조용하게." 배치, 재생시간 4초, 전환효과 Auto(0.3s) 설정 모습


3. 스토리보드 (씬별 상세 기획)

Scene 1은 3초, Scene 2는 4초, Scene 3은 3.9초로 각각 개별 영상을 제작한 뒤, 전체 길이를 시간 단축(트리밍)하여 최종적으로 정확히 10초 길이의 영상 한 편으로 통편집하였다. 모든 씬은 자막과 나레이션 문구를 동일하게 통일하였다(기존에 있던 별도의 압축형 자막은 삭제).

Scene 1. 문제 제시 (개별 렌더링 3초)
화면은 모던한 화이트톤의 욕실에서 젖은 머리를 말리려는 인물이 유선 드라이기를 사용하는 모습으로 시작하는데, 짧고 팽팽하게 꼬인 검은색 코드가 벽면 콘센트에서 억지로 당겨지며 인물의 움직임을 제한하고, 그로 인한 불편함과 짜증이 표정과 자세에서 드러난다. 카메라 워크는 와이드 샷에서 시작해 서서히 줌인하며 손잡이에 어지럽게 감긴 전선과 인물의 초조한 표정을 담아내고, 마지막에는 세면대 모서리에 걸린 전선을 타이트하게 클로즈업하며 마무리한다.

이미지 표시

나레이션(AI 보이스 '가현') = 자막(카페24 클래식타입, 동일 문구) : "바쁜 아침, 작은 불편함이 시작됩니다."
배경음악 : NAVY CLOUD - feat. 사도(볼륨 40%, 페이드인) + 드라이기 모터 소음 + 전선 마찰 효과음.
사용 도구 및 목적 : Gemini(키비주얼 이미지 생성) → Runway(Custom·Gen-4 Turbo로 모션 영상 변환) → VideoStew(나레이션 '가현' 생성, 자막·BGM 삽입, 전환 Auto 적용, 개별 3초 렌더링).

Gemini 프롬프트 원문(최종) : "Realistic modern minimal bathroom, soft morning sunlight, the same young professional woman from the previous scenes trying to dry her wet hair, looking very uncomfortable and mildly frustrated. She holds a traditional black corded hair dryer, but the black cable is short and tightly coiled, pulling awkwardly from the wall outlet and restricting her movement. Her expression and posture convey physical discomfort and annoyance due to the short, tangled wire. Cinematic commercial photography, 16:9 widescreen aspect ratio."

Runway 프롬프트 원문(최종) : "Wide shot in a clean, bright bathroom, slowly zooming in toward a woman visibly frustrated with a corded hair dryer. Her face shows clear annoyance and stress as she struggles with a chaotic, tangled mess of wires wrapped around the handle. She is tugging at the cord, clearly hindered by its limited reach. The camera movement captures her restless, impatient expressions. The shot ends with a quick, tight close-up on the tangled power cord caught on the edge of the sink, emphasizing the inconvenience. Realistic commercial cinematography, soft morning light, high detail on the frustrated facial expressions and the messy cables, 16:9 aspect ratio."

Scene 2. 해결 제시 (개별 렌더링 4초)
화면은 동일한 욕실 배경에서, 씬1과 동일한 인물이 미소를 지으며 소형·경량화된 RAUM 무선 드라이기로 편안하게 머리를 말리는 모습을 담는다. 드라이기는 매트 화이트와 파스텔 라벤더 톤에 "RAUM" 텍스트와 로고가 선명하게 표시되어 있으며, 부드러운 바람의 흐름이 시각적으로 함께 표현된다. 카메라 워크는 미디엄 샷에서 시작해 서서히 돌리인하며, 편안하고 즐거운 표정으로 미소 짓는 인물이 자연스러운 손동작으로 머리를 매만지는 모습과 부드럽게 흩날리는 바람을 담아내고, 마지막에는 제품의 우아한 디자인을 강조하는 로우앵글 클로즈업으로 마무리한다.

이미지 표시

나레이션(AI 보이스 '가현') = 자막(카페24 클래식타입, 동일 문구) : "선 없이 더욱 자유롭게, 조용하게."
배경음악 : 큐디드라이 - EDM(볼륨 점층 상승) + 화이트노이즈를 최소화한 부드러운 바람 소리.
사용 도구 및 목적 : Gemini(제품 히어로샷·인물 이미지 생성, 씬1 이미지를 참조 이미지로 첨부, 브랜드명·로고 직접 반영) → Runway(Custom·Gen-4 Turbo로 손동작·바람 흐름 모션 생성) → VideoStew(나레이션 '가현' 생성, 자막·BGM 삽입, 전환 Auto 적용, 개별 4초 렌더링).

Gemini 프롬프트 원문(최종) : "A high-resolution, photorealistic lifestyle product shot in a modern, minimal bathroom. A young professional woman with brown, partially wet, shoulder-length hair, wearing a warm grey waffle-knit bath robe, is happily smiling as she styles her hair. In her right hand, she holds a premium cordless hair dryer in a compact and lightweight size, notably smaller and handier than a traditional dryer. The dryer features a matte white and pastel lavender design, with the text "RAUM" and its logo clearly displayed. A gentle, clean wisp of airflow is visible. The light grey tiled background includes a white vessel sink, a chrome faucet, a large framed mirror with reflection, and open wooden wall shelves holding amber glass toiletries. A frosted glass window provides a soft morning sunlight glow. Shallow depth of field, focused sharply on the woman and the compact hair dryer. High quality, realistic lighting and textures, 16:9 widescreen aspect ratio."

Runway 프롬프트 원문(최종) : "Medium shot, slowly dollying in toward a woman comfortably using a sleek cordless hair dryer. She has a relaxed, joyful expression, smiling brightly as she easily styles her hair, emphasizing the freedom of no tangled cords. Smooth, elegant hand movements, soft airflow gently lifting her hair. Calm, premium commercial atmosphere with warm, flattering lighting. The shot transitions to a gentle low-angle close-up focusing on the elegant design of the cordless hair dryer at the end. 16:9 aspect ratio, high-end commercial cinematography style."

Scene 3. 브랜드 각인 (개별 렌더링 3.9초)
화면은 제품을 충전 거치대에 올려놓는 히어로샷으로, 미니멀한 화이트와 라벤더 배경 위에 제품 표면에는 브랜드명(RAUM)과 로고가 이미 반영되어 있다. 카메라 워크는 제품 노즐 부분의 매크로 클로즈업에서 시작해, 살짝 위로 틸트되며 서서히 뒤로 빠지는 돌리 백으로 충전 거치대 위 제품 전체를 드러내고, 부드러운 조명이 매트한 표면을 우아하게 스치며, 마지막 0.5초는 완성도 높은 히어로샷으로 정지한다.

이미지 표시

나레이션(변경, AI 보이스 '가현') = 자막(변경, 카페24 클래식타입, 동일 문구) : "RAUM, 무선 저소음 헤어드라이기, 당신의 아침을 더 편안하게."
배경음악 : 큐디드라이 - EDM(앞선 씬과 동일 트랙 유지) + 브랜드 사운드 로고(2음절 벨 톤), 마지막에 자연스럽게 페이드아웃.
사용 도구 및 목적 : Gemini(제품 단독 히어로샷 생성, 스타일 참조 이미지 함께 입력, 브랜드명·로고 직접 반영) → Runway(Custom·Gen-4 Turbo로 매크로 클로즈업→풀백 모션 생성) → VideoStew(변경된 나레이션·자막 반영, BGM 페이드아웃 처리, 개별 3.9초 렌더링).

Gemini 프롬프트 원문(최종) : "Hero product photograph of a premium cordless hair dryer placed on a minimalist charging dock, soft lavender and white studio background, clean empty negative space reserved for logo and slogan overlay, soft directional lighting, high-end commercial product photography, realistic, brand name added (RAUM), logo added (RAUM in English), photorealistic style, 16:9 widescreen aspect ratio. (Style reference image reflecting the brand tone and manner is attached)."

Runway 프롬프트 원문(최종) : "Macro close-up of the cordless hair dryer nozzle. The camera slowly dollies backward with a subtle tilt upward, gradually revealing the full cordless hair dryer resting on its charging dock. Soft diffused studio lighting gently sweeps across the premium matte surface, creating elegant highlights without harsh reflections. The product remains perfectly still and centered. Clean minimal white background with generous negative space on the right for logo, slogan, and CTA. Finish with a perfectly composed hero shot and hold the final frame for 0.5 seconds. Luxury product commercial, photorealistic, ultra-clean, smooth cinematic camera movement, 3 seconds, 16:9."


4. 프롬프트 수정 전/후 기록 (Scene 1·2·3 전체, Gemini·Runway 반영)

[Scene 1]

Gemini 이미지 프롬프트 — 수정 전에는 "cable tangled and slightly caught on the sink edge"처럼 전선이 세면대에 살짝 걸리는 가벼운 불편함만 묘사하였다. 수정 후에는 "the black cable is short and tightly coiled, pulling awkwardly from the wall outlet and restricting her movement"로 바꾸어 전선이 짧고 팽팽히 꼬여 움직임 자체를 제한하는 더 직접적인 불편함으로 강화하고, 인물의 표정·자세를 구체적으로 지시하였다.

Runway 영상 프롬프트 — 1차는 "Camera starts as a wide shot and slowly zooms in over 2 seconds... Slight handheld motion blur to emphasize inconvenience."처럼 카메라 무빙 위주로만 간결하게 지시하였다. 2차는 "Advertising footage,"를 앞에 추가하고 줌인 구간을 "more than two seconds"로 늘렸다. 3차(최종)는 "Her face shows clear annoyance and stress", "a chaotic, tangled mess of wires wrapped around the handle", "captures her restless, impatient expressions"처럼 인물의 표정과 엉킨 전선 상태를 훨씬 구체적으로 묘사하였다.

[Scene 2]

Gemini 이미지 프롬프트 — 수정 전에는 "premium cordless hair dryer with matte white and soft lavender accents, no text, no logo"였다. 수정 후에는 제품을 더 작고 다루기 쉬운 크기로 구체화하고 "the text 'RAUM' and its logo clearly displayed"를 추가하였다.

Runway 영상 프롬프트 — 수정 전에는 "Smooth, elegant hand movement, soft airflow around her hair, calm and premium atmosphere"였다. 수정 후에는 "She has a relaxed, joyful expression, smiling brightly... emphasizing the freedom of no tangled cords... warm, flattering lighting"처럼 인물의 감정 표현을 구체화하였다.

[Scene 3]

Gemini 이미지 프롬프트 — 수정 전에는 "no text, no logo"였다. 수정 후에는 "brand name added (RAUM), logo added (RAUM in English)"를 명시하였다.

Runway 영상 프롬프트 — 수정 전에는 "Camera slowly pulls back from a close product shot..."였다. 수정 후에는 "Macro close-up of the cordless hair dryer nozzle... dollies backward with a subtle tilt upward... Luxury product commercial... ultra-clean"처럼 조명·카메라 워크를 정교화하였다.

세 씬 모두 공통적으로, 수정 후에는 표정·자세·전선 상태·브랜드명/로고·조명까지 구체적으로 반영되어 광고 영상에 바로 사용 가능한 수준의 결과물을 얻었다.


5. 제약사항 반영

소스와 저작권 측면에서, 직접 촬영한 영상이나 유료 스톡 영상은 전혀 사용하지 않았으며 모든 시각적·청각적 소스는 생성형 AI의 결과물을 사용하였다. 편집 도구는 VideoStew 한 도구로 나레이션·자막·BGM·전환·렌더링까지 전체 편집을 진행하며, CapCut은 사용하지 않는다. 비용과 크레딧 관리 측면에서는, Runway와 VideoStew 모두 회원가입 시 무료 크레딧을 제공하므로 이를 우선 활용하였고, VideoStew는 최종 렌더링·다운로드 시에만 크레딧이 차감되므로 편집 중간 작업은 반복할 수 있었다. 이미지 생성은 Gemini, 영상 생성은 Runway, 자막·나레이션·편집은 VideoStew로 각각 하나의 도구만 사용하였다(별도 대체 도구 없음). 화면비율 대응으로는, 16:9 가로형 버전을 먼저 제작한 뒤, 9:16 세로형 버전은 Runway에서 이미지를 세로로 크롭·편집하여 세로형 영상으로 새로 생성하고, 이를 VideoStew에서 최종 화면비율에 맞게 조정하여 두 가지 최종본을 완성하였다. 일관성 유지를 위해 Gemini에 이전 씬에서 생성한 이미지를 참조 이미지로 함께 첨부하는 방식을 활용해 전체 씬에서 동일한 인물과 브랜드 톤을 고정하였다.


6. 최종 영상 파일 스펙

항목내용파일명(16:9, 가로)B-2_최종편집영상_이혜경(가로).mp4파일명(9:16, 세로)B-2_최종편집영상_이혜경(세로).mp4개별 씬 렌더링 길이Scene 1: 3초 / Scene 2: 4초 / Scene 3: 3.9초최종 통합 길이10초 (시간 단축·트리밍 후 VideoStew 통편집)화면비율16:9(가로, 선제작) / 9:16(세로, Runway 세로 크롭·재생성 후 VideoStew에서 최종 비율 조정)해상도1920x1080(16:9) 기준, 세로형 1080x1920 — 저사양 시 720p 이상 허용프레임레이트24~30fps코덱비디오 H.264 / 오디오 AAC


7. 과제 목표 및 기능 요구사항 반영

텍스트 기획은 Gemini·GPT·Claude를 함께 활용해 브랜드 콘셉트와 광고 메시지, 스토리보드를 기획하고 문서화하였다. 이미지 생성은 Gemini로 브랜드의 미니멀하고 프리미엄한 제품 이미지를 생성하였으며, 참조 이미지 첨부 방식으로 일관성을 확보하고 브랜드명·로고를 이미지 자체에 렌더링하였다. 영상 생성은 Runway로 정지 이미지를 광고 영상으로 변환하고 카메라 무빙과 인물의 표정·동작을 세밀하게 구현하였다. 나레이션·자막·전환·렌더링까지 전체 편집은 VideoStew 한 도구로 통합하여(CapCut 미사용) 나레이션 보이스('가현'), 자막 폰트(카페24 클래식타입), BGM, 전환효과를 일관되게 적용하였다.

기능 요구사항 측면에서도 모든 항목을 충족하였다. 가상 브랜드를 타깃과 톤앤매너, USP를 포함해 정의하였고, 광고의 목적과 핵심 메시지를 한 문장으로 정의하였다. 씬 단위로 스토리보드를 작성하고 필수 필드를 빠짐없이 채웠으며, 전체 세 개 씬에 대해 이미지·영상 프롬프트 수정 전후를 기록하였다. 이미지 생성(Gemini), 영상 생성(Runway), 자막·나레이션·편집(VideoStew)을 각각 하나씩 사용하였고, 도구 선택 이유도 함께 기록하였다. 최종 영상은 개별 씬(3초+4초+3.9초)을 시간 단축 편집하여 정확히 10초로 제작하였으며, 모든 씬에 시각·청각 요소를 포함하였다. 스토리라인은 문제 제시→해결→브랜드 인식의 기승전결 구조를 갖추었으며, 브랜드명·로고는 Scene 2·3의 제품 이미지 자체에 지속적으로 노출된다.


8. 나레이션·자막 대본 (VideoStew, AI 보이스 '가현' / 자막 = 나레이션 통일, 카페24 클래식타입)

기존에 있던 별도의 압축형 자막은 모두 삭제하고, 모든 씬에서 자막과 나레이션 문구를 동일하게 통일하였다.

씬개별 렌더링 길이나레이션 = 자막 (동일 문구)Scene 13초"바쁜 아침, 작은 불편함이 시작됩니다."Scene 24초"선 없이 더욱 자유롭게, 조용하게."Scene 3 (변경)3.9초"RAUM, 무선 저소음 헤어드라이기, 당신의 아침을 더 편안하게."


9. 배경음악(BGM) 및 전환효과 설정

구간BGM 트랙전환효과Scene 1NAVY CLOUD - feat. 사도Auto (0.3s)Scene 2~3큐디드라이 - EDMAuto (0.3s)


10. 화면비율(16:9 / 9:16) 제작 프로세스

최종 영상은 두 가지 화면비율로 제작하였다. 먼저 16:9 가로형 버전을 기본으로 먼저 제작하였고, 이후 9:16 세로형 버전은 Runway에서 기존 이미지를 세로 방향으로 크롭(편집)한 뒤, 이 세로형 이미지를 기반으로 Runway에서 세로형 영상을 새로 생성하였다. 마지막으로 이렇게 생성된 세로형 영상을 VideoStew로 가져와 최종 화면비율에 맞게 조정함으로써, 하나의 스토리보드에서 16:9·9:16 두 가지 최종 결과물(B-2_최종편집영상_이혜경(가로)/(세로))을 모두 완성하였다.


11. 에셋 규격 및 생성 파라미터 표준화 (톤앤매너 일관성)

여러 AI 도구를 거치면서도 톤앤매너가 흔들리지 않도록, 다음과 같이 에셋 규격과 생성 파라미터를 씬 전체에 공통 표준으로 고정하였다.


화면비율/해상도 : 모든 Gemini 이미지·Runway 영상 프롬프트에 "16:9 widescreen aspect ratio"를 공통 파라미터로 명시하여, 처음부터 규격이 어긋나지 않도록 통일하였다(세로형은 최종 단계에서만 별도 파생).
색상 팔레트 : 모든 Gemini 프롬프트에 "soft lavender and white" 계열 색상 키워드를 공통으로 포함시켜, 씬마다 색감이 따로 놀지 않고 하나의 브랜드 톤(라벤더·화이트·실버)으로 수렴하도록 하였다.
조명·촬영 스타일 : "soft directional lighting", "cinematic/high-end commercial photography", "photorealistic style" 같은 동일 계열의 조명·촬영 스타일 키워드를 전 씬 프롬프트에 표준 문구로 고정 사용하였다.
인물 일관성 : Gemini의 참조 이미지 체이닝(이전 씬에서 생성한 이미지를 다음 프롬프트에 첨부)으로 동일 인물·헤어스타일·의상을 유지하였다.
브랜드 자산 표기 : 로고·브랜드명(RAUM) 노출 방식을 "brand name added (RAUM), logo added (RAUM in English)"처럼 모든 관련 프롬프트에 동일하게 지정하여, 씬마다 로고 형태·표기가 달라지지 않도록 표준화하였다.
오디오·자막 규격 : 나레이션 보이스('가현'), 자막 폰트(카페24 클래식타입), 전환효과(Auto 0.3s)를 VideoStew 편집 단계의 공통 규격으로 고정해, 생성 단계뿐 아니라 편집 단계의 톤도 통일하였다.



12. 결과 파일 네이밍 및 정리 규칙

결과 파일을 재사용·추적하기 쉽도록 아래와 같은 네이밍 규칙을 적용하였다.

단계네이밍 규칙예시Gemini 원본 이미지scene0{n}_keyvisual.pngscene01_keyvisual.pngRunway 변환 영상(원본)scene0{n}_motion.mp4scene02_motion.mp4VideoStew 개별 렌더링본scene0{n}_final_{길이}.mp4scene03_final_3.9s.mp4최종 통합본(가로/세로)B-2_최종편집영상_이혜경(방향).mp4B-2_최종편집영상_이혜경(가로).mp4

씬 번호(scene0{n})와 단계(keyvisual→motion→final)를 파일명 접미사로 순서대로 이어 붙여, 파일명만 보고도 "몇 번 씬의 어느 제작 단계 산출물인지, 길이가 몇 초인지"를 바로 식별할 수 있도록 정리하였다. 최종 결과물은 과제 코드(B-2)·산출물 성격(최종편집영상)·제작자명·화면비율(방향)을 하나의 파일명에 모두 포함시켜, 가로/세로 두 버전이 섞여도 구분이 가능하도록 하였다.


13. Text-to-Image / Image-to-Video 선택 기준

이번 프로젝트에서는 이미지 생성과 영상 생성의 기술적 성격이 다르다는 점을 고려해 두 단계로 도구를 분리하였다.


Text-to-Image (Gemini) : 텍스트 프롬프트만으로 정지 이미지를 생성하는 방식이다. 구도, 인물, 제품 디테일, 브랜드 로고·텍스트처럼 "무엇을 보여줄 것인가"를 세밀하게 통제하는 데 강점이 있다.
Image-to-Video (Runway) : 이미 만들어진 정지 이미지를 입력값으로 받아 카메라 무빙과 피사체의 움직임을 더하는 방식이다. "어떻게 움직이게 할 것인가", 즉 카메라 워크·모션의 자연스러움을 통제하는 데 강점이 있다.


선택 기준은 다음과 같다. Gemini와 Runway는 같은 '이미지 생성'을 시도해도 서로 잘하는 부분이 달랐다 — Gemini는 브랜드명·로고 같은 텍스트 요소와 인물·색감의 사실적 표현에서, Runway는 카메라 무빙과 동작의 자연스러움에서 더 높은 퀄리티를 보였다. 이 차이를 그대로 활용해, 먼저 Gemini(Text-to-Image)로 브랜드 톤·인물·로고가 반영된 키비주얼을 완전히 확정한 뒤, 그 이미지를 그대로 Runway(Image-to-Video)에 입력해 모션만 추가하는 2단계 파이프라인을 선택하였다. 이미지 단계에서 비주얼을 100% 통제해두면 영상 생성 단계에서는 카메라 워크와 동작 표현에만 집중할 수 있어, 불필요한 재생성(크레딧 낭비)을 줄이고 결과물의 예측 가능성을 높일 수 있었다.


14. 도구 선택 우선순위 (품질 / 제어 / 속도 / 비용)

도구를 선택할 때는 품질(퀄리티) > 제어(Control) > 속도 > 비용 순서로 우선순위를 두었다.


이미지 생성(Gemini) : 같은 프롬프트를 입력해도 Gemini가 브랜드명·로고 같은 텍스트 요소를 다른 이미지 생성 도구보다 정확하고 고품질로 렌더링했고, 참조 이미지를 통한 인물 일관성 제어도 가능했다. 따라서 품질과 제어를 최우선 기준으로 Gemini를 선택하였다.
영상 생성(Runway) : 카메라 무빙 표현과 인물 표정 디테일의 완성도(퀄리티)가 높고, 프롬프트만으로 카메라 워크를 세밀하게 제어할 수 있어 품질·제어 기준에서 우수했다. 속도는 [Gen-4 Turbo] 모델 옵션을 사용해 어느 정도 보완하였다.
편집(VideoStew) : 나레이션·자막·BGM·전환을 한 도구 안에서 한 번에 처리할 수 있어, 이 단계에서는 오히려 속도(작업 효율)와 비용(무료 크레딧, 렌더링 시에만 차감)을 우선 기준으로 두었다.


정리하면, 생성 단계(이미지·영상)에서는 품질과 제어를 최우선으로, 편집 단계(VideoStew)에서는 속도와 비용 효율을 우선 기준으로 삼아, 단계별로 다른 우선순위를 적용하였다.


15. 멀티 소스 통합 시 불일치(해상도/비율/색감/톤) 보정 기준 및 절차

서로 다른 도구(Gemini·Runway·VideoStew)의 결과물을 하나로 합치는 과정에서 발생할 수 있는 불일치는 다음 기준과 절차로 보정하였다.


해상도/비율 기준 : Gemini·Runway 생성 단계에서부터 16:9, 1920x1080(또는 동급) 규격을 프롬프트에 공통 지정해 애초에 다른 해상도가 섞이지 않도록 예방하였고, VideoStew 업로드 전 최종 확인 후 상이한 해상도가 있으면 VideoStew의 화면비율 조정 기능으로 일괄 보정하였다.
색감/톤 기준 : 모든 Gemini 프롬프트에 동일한 색상 키워드(라벤더·화이트 톤, soft lighting)를 반복 사용해 최대한 동일한 색감으로 생성하고, VideoStew 편집 단계에서 슬라이드를 나란히 미리보기로 비교해 눈에 띄게 튀는 씬이 있으면 밝기·색온도를 미세 조정하는 방식으로 보정하였다.
보정 절차 : ① Gemini 생성 직후 3개 씬 이미지를 나란히 비교해 톤 편차 확인 → ② 편차가 있으면 프롬프트에 색상 키워드를 추가해 재생성 → ③ Runway 변환 후 영상에서도 동일하게 비교 → ④ VideoStew에 모두 업로드한 뒤 슬라이드 전환 지점에서 밝기·색감이 급격히 튀지 않는지 재확인하고 필요 시 미세 보정 후 최종 렌더링.



16. 확장 시나리오 : 60초 버전을 15초로 축소할 경우의 전략

만약 현재 컨셉을 60초 버전으로 먼저 만든 뒤 15초로 압축해야 한다면, 다음 원칙으로 씬을 재구성한다.


우선순위 원칙 : 브랜드 인지(로고·슬로건·CTA)에 직결되는 씬을 최우선으로 유지하고, 문제 상황을 길게 보여주는 도입부는 최소화한다.
유지할 씬 : Scene 2(해결 제시 — 무선·저소음 핵심 기능 시연)와 Scene 3(브랜드 각인 — 로고·나레이션)는 브랜드 핵심 메시지를 직접 전달하므로 반드시 유지한다.
축소/삭제할 부분 : Scene 1(문제 제시)에서 60초 버전에 있었을 여러 디테일 컷(표정, 전선 상태를 여러 각도로 보여주는 컷 등)은 1~2초 이내로 압축하거나 과감히 생략하고, 대신 Scene 2 도입부 나레이션 한 문장에 문제 상황을 압축해 언급하는 방식으로 대체한다.
메시지 재구성 : "문제 제시 → 해결 → 브랜드 인식"의 3단 구조를 "해결(제품 강점) → 브랜드"의 2단 구조로 축소하고, 나레이션도 각 문장을 3~5단어 수준으로 초압축한다.
컷 편집 전략 : 60초 버전에 있었을 부가 사용 시나리오나 부가 기능 소개 씬은 15초 버전에서는 모두 삭제하고, 핵심 USP 한 가지(무선+저소음)만 남겨 메시지를 하나로 집중시킨다.



17. 기대 효과

RAUM 광고는 짧은 시간 안에 제품의 핵심 장점인 무선·저소음·간편 충전을 직관적으로 전달한다. 생성형 AI를 활용하여 기획부터 이미지·영상·음성 제작, 편집까지 전 과정을 하나의 통합된 도구 체계(Gemini/GPT/Claude → Gemini → Runway → VideoStew)로 효율적으로 수행함으로써, 멀티모달 AI 활용 역량과 브랜드 광고 제작 역량을 동시에 보여줄 수 있는 결과물이라고 할 수 있다.
