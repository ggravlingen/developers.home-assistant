---
title: "인증된 웹뷰"
---

애플리케이션에서 이미 사용자에게 인증을 요청했습니다. 즉, Home Assistant UI 를 열 때 앱이 사용자에게 다시 인증을 요청해서는 안됩니다.

이를 위해서, Home Assistant UI 는 [외부인증](frontend_external_auth)을 지원합니다. 프론트 엔드가 앱에 액세스 토큰을 요청할 수 있도록 앱에서 후크를 제공하는것을 허용합니다.

이 기능은 인스턴스에 직접 연결을 필요로 합니다.