# cardnews-cdn

인스타그램/스레드 발행용 카드 이미지 임시 호스팅.

Meta Graph API 는 로컬 파일을 받지 않고 공개 URL 에서 이미지를 가져간다.
그래서 발행 직전에 여기에 올리고, 발행이 끝나면 지운다
(인스타가 이미 이미지를 저장했으므로 지워도 게시물은 그대로다).

이 저장소는 cardnews-factory 의 un.py host / un.py prune 이 관리한다.
직접 파일을 넣거나 지우지 말 것.
