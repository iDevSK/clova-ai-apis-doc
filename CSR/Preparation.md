## 사전 준비사항 {#Preparation}

CSR API를 사용하려면 개발하려는 애플리케이션을 네이버 개발자 센터에 등록해야 합니다. 이때, 사용할 API에 대한 권한을 설정해야 하며, API 사용 시 필요한 인증 정보를 획득해야 합니다. [애플리케이션 등록](https://developers.naver.com/docs/common/openapiguide/#/appregister.md)을 참고하여 다음과 같이 필요한 사항을 미리 준비합니다.

![](/CSR/Resources/Images/CSR_Register_App.png)

1. [애플리케이션 등록하기](https://developers.naver.com/apps/#/wizard/register)를 통해 앱 등록 페이지로 이동합니다.
2. **사용 API**에서 **음성인식**(CSR API)을 선택합니다.
3. **비로그인 오픈 API 서비스 환경**에 개발하는 앱 정보를 입력합니다.
  * (Android용 앱을 개발하는 경우) **Android 설정**을 추가하고 **안드로이드 앱 패키지 이름**을 입력합니다.
  * (iOS용 앱을 개발하는 경우 **iOS 설정**을 추가하고 **iOS Bundle ID**를 입력합니다.
4. **등록하기** 버튼을 클릭합니다. 버튼을 클릭하면 **내 애플리케이션** 메뉴로 이동하며 방금 등록한 앱의 정보가 화면에 표시됩니다. 이 페이지에서 **Client ID**와 정보를 확인할 수 있으며, **API** 설정 탭으로 이동하면 등록한 앱의 package 이름(Android)이나 Bundle ID 정보(iOS)를 확인할 수 있습니다.
