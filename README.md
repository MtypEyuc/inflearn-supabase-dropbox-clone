# Dropbox 따라하기

## 1. 프로젝트 설정
강의 커리큘럼에 맞는 넥스트 14.2.4 버전으로 설치 후 @material-tailwind/react 관련 의존성 다운그레이드. 및 Supabase 연동.

## 2 .material-tailwind/react를 사용해 UI 생성
layout.tsx / ui.tsx에서 의도한 화면을 출력하도록 제작.

## 3. Supabase Storage에 minibox 버킷 등록

- `image/*`을 사용해 이미지 파일이면 모두 저장.
- Public bucket 상태로 만들어 인증이 없어도 사용 가능.

## 5. 과제 - Last modified 구현

Supabase 파일 메타데이터에 있는 Last modified 필드 정보를 요청해 가져오는 방식으로 제작.
