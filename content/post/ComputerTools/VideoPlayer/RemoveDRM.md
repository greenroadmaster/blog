---
title: 소유한 전자책에서 DRM을 제거하는 방법(2021년)
description: This is documents of Computer Tools
featuredImage: 
toc: true
authors: Byeonghui-Won
tags:
categories: Computer
series: Tools
date: '2021-09-30'
lastmod: '2021-09-30'
draft: false
---

## DRM은 무엇인가?

디지털 저작권 관리(DRM)는 저작권을 보호하기 위한 관리방법으로 저작권이 있는 자료의 사용, 수정 및 배포를 제어하도록 설계되어 있으며 전자책에서 음악 파일에 이르기까지 모든 디지털 자료에 공통적으로 설치되어 있는 기능이다. DRM 문제를 뒷받침하는 것은 미디어 소유권 문제로 우리가 Amazon과 같은 회사에서 구입한 음악, 영화 및 책은 기술적으로 우리 것이 아니라 단지 해당 콘텐츠를 사용할 수 있는 라이선스를 부여받았을 뿐이라는 것이다. 

저작권 소유자가 자신의 저작물을 보호하기 위해 열심인 이유를 이해하기는 쉽지만 소비자로서 DRM이 적용된 한 구매자의 입장에서 볼 때 실망스러운 측면이기도 하다. 2012년 에 약관 위반으로 추정되는 킨들 라이브러리(및 Amazon 계정) 전체를 영구적으로 삭제 한 Amazon 사용자의 경우 그녀가 무슨 잘못을 했는지 정확히는 모르지만 이미 수백 달러를 지출했고 독서의 경험과 그동안 남긴 수많은 밑줄과 노트는 한순간 되돌릴 수 없을 정도로 사라졌고 다시 찾을 수 있는 방법이 없어졌다. 아마존은 당시 그녀에게 보낸 이메일에서 이렇게 말했다. 부분적으로 명시된 사용 조건에 따라: Amazon.co.uk 및 그 계열사는 단독 재량에 따라 서비스를 거부하거나, 계정을 해지하거나, 콘텐츠를 제거 또는 편집하거나, 주문을 취소할 수 있는 권리를 보유합니다. 관련 계정을 연결하는 방법에 대해 제공된 정보를 기반으로 귀하의 계정을 검토했으며 다시 열지 않음을 알려드립니다 라고 했다.

만약 그녀가 DRM 제한을 제거했다면 이 문제를 완전히 피할 수 있었을 것이다. 그렇게 하면 로컬 컴퓨터에 파일을 백업할 수 있었기 때문이다. Amazon은 여전히 그녀의 계정을 삭제했을지는 모르겠지만 적어도 많은 돈을 지출한 콘텐츠에 그녀가 남긴 수많은 개인경험의 기록은 여전히 그녀가 소유하고 있을 것이기 때문이다. 

## 전자책 DRM 방식

일반적으로 전자책은 4가지 DRM 방식을 사용한다. 

+ Adobe의 ADEPT DRM : EPUB 및 PDF에 적용할 수 있으며 대부분의 타사 전자책 리더에서 읽을 수 있고 Barnes and Noble에서 구입한 책은 이 형식을 사용한다. 

+ Amazon DRM : AZW8, KF8, Mobipocket 파일에 Amazon 형식을 적용한다. 

+ Apple FairPlay DRM : Apple의 접근 방식은 EPUB 파일에만 적용할 수 있으며 Apple의 iBooks 앱에서만 읽을 수 있다. 

+ Marlin DRM : Panasonic, Philips, Samsung 및 Sony를 포함하는 개방형 산업 그룹이 Marlin 시스템을 개발했다. 

## 대부분의 전자책에서 DRM을 제거하는 방법 1 - Calibre

전자책 출판사와 전자책 파일 형식의 다양성을 감안할 때 만능 솔루션이 없다는 것은 놀라운 일이 아니지만 여기 몇가지 DRM을 제거하는 방법으로 Amazon, Barnes and Noble 또는 기타 일반적인 유명 전자책 매장을 통해 책을 구입하는 경우 가장 좋은 솔루션으로 Calibre는 유용한 기능으로 가득 찬 무료 오픈 소스 전자책 라이브러리 관리 응용 프로그램이다. Calibre를 설치하고 DRM 제거 플러그인인 apprenticealf의 전자책DRM제거도구를 설치한다.

### 소프트웨어 설치

### 플러그인 설치

Calibre는 다양한 기능을 수행하는 다양한 플러그인을 지원하며 DRM을 제거하려면 apprenticealf의 전자책용 DRM 제거 도구가 필요하다. 최신 버전은 GitHub에서 다운로드할 수 있다. 파일을 다운로드하고 내용의 압축을 풀고 Calibre의 설정메뉴에서 Plugin 설치 한 후 화면 메시지에 따라 Calibre 앱을 다시 시작한다.

### 플러그인 편집

DeDRM 목록을 두 번 클릭하고 eInk Kindle ebooks 를 선택한 다음 장치의 일련 번호를 추가한다. 대부분의 Kindles에서 장치의 설정 메뉴에서 일련 번호를 찾을 수 있다.

### DRM 제거

책을 처음으로 Calibre로 가져올 때 작동하기 때문에 이미 DRM 책을 가져온 경우 앱에서 해당 책을 제거하고 다시 가져온다. DRM 제거는 전체 프로세스에서 가장 간단한 부분으로 e-리더(또는 로컬 드라이브)에서 Calibre의 기본 창으로 eBook을 끌어다 놓기만 하면 소프트웨어가 자동으로 DRM을 삭제한다. Kindle에서 가져오는 경우 각 책과 관련된 모든 파일을 드래그하고 중복에 대한 경고가 표시되면 없음을 클릭 한다.

### Apple Books에서 DRM을 제거하는 방법

불행히도 전자책에서 DRM을 제거하려는 Apple 사용자는 훨씬 더 제한된 도구 선택에 직면한다. 어렵다는 얘기. 신뢰할 수 있는 유일한 방법은 TunesKit iBook DRM 제거 도구 를 사용할 수 있지만 추천하지 않는다. 

### OverDrive 전자책에서 DRM을 제거하는 방법

미국의 많은 공공 도서관에서는 OverDrive 시스템을 사용하여 책의 디지털 사본을 대여하는데 도서관 책에서 DRM을 제거할 수 있다. 먼저 Adobe Digital Editions 의 사본을 다운로드 하고 앱 내에서 편집하려는 전자책을 연 다음 eBook DRM 제거 도구 의 사본을 다운로드 후 앱을 열고 Digital Editions 폴더에서 작업하려는 EPUB 파일을 선택한 다음 제거 버튼을 누르면 된다. 프로세스를 완료하는 데 몇 초 정도 시간을 주면 OverDrive DRM이 제거된다. 전자책을 Kindle로 보내고 문제 없이 읽을 수 있으면 된다. 불법은 아니라고 하지만 도서관 도서에서 DRM을 제거하는 것은 확실히 도덕적으로 의심스럽기 때문이 이 방법은 시작하기 전 반드시 자신의 행동을 돌아볼 것.