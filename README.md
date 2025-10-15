# Weather_AI_simple
페이지를 클릭해서  음성으로 날씨 알려주는 심플 페이지

https://openweathermap.org/ 에서 무료 API 키 발급하여 html 코드안에 입력해야함.

※ 기본값 예시:

        const WEATHER_API_KEY = "1122334455667788"; // <--- 이 부분을 수정하세요
        const API_URL = "https://api.openweathermap.org/data/2.5/weather";

        // 기본값 설정 (서울 시청)
        const DEFAULT_LOCATION = { id: 'default', name: "서울 (기본 위치)", lat: 37.5665, lon: 126.9780 };

        또는
        // 기본값 설정 (남양주)
        const DEFAULT_LOCATION = { id: 'default', name: "남양주 (기본 위치)", lat: 37.63317778, lon: 127.2186333 };

※ 기타 5개까지 저장하고 즐겨찾기처럼 선택해서 적용할 수 있음.
