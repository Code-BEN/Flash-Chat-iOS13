![App Brewery Banner](Documentation/AppBreweryBanner.png)

# Flash-Chat

## GOAL

테이블뷰를 다루고 사용자지정 셀을 만들고 클라우드기반 백엔드 데이터베이스를 만듬

채팅앱과 FireBase FireStore를 서비스로한 데이터베이스를 만듬.

## What you will learn

Cocoapods 및 Swift Package Manager를 사용하여 앱에 타사 라이브러리를 통합하는 방법
Firebase Firestore를 사용하여 클라우드에 데이터를 저장하는 방법
Firebase 데이터베이스를 쿼리하고 정렬하는 방법
사용자 인증, 등록 및 로그인에 Firebase를 사용하는 방법
UITableView로 작업하는 방법과 데이터 소스 및 대리자를 설정하는 방법
.xib 파일을 사용하여 사용자 정의보기를 작성하여 기본 설계 구성 요소를 수정하는 방법.
탐색 컨트롤러에 View Controller를 포함하고 탐색 스택을 이해하는 방법
상수 파일을 생성하고 정적 속성을 사용하여 문자열 및 기타 상수를 저장하는 방법
스위프트 루프에 대해 배우고 루프를 사용하여 애니메이션을 만듭니다.
앱 수명주기 및 viewWillAppear 또는 viewWillDisappear 사용 방법에 대해 알아 봅니다.
탐색을위한 직접 Segue를 작성하는 방법


# Constants
```
struct K {
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"
    
    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }
    
    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}

```

>This is a companion project to The App Brewery's Complete App Developement Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)

![End Banner](Documentation/readme-end-banner.png)
