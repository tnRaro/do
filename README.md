# 한 시간에 한 번씩 잔소리 해주는 친구

![Discord_QkFxWDIk1E](https://github.com/tnraro/nagging-bot/assets/8617317/bb05ee2f-c67e-4f4c-8247-e45c23696187)

프사: @NUEH_NANA 님 [Picrew](https://picrew.me/en/image_maker/2033441)

## 사용

### 1. 웹훅 만들기

디스코드 > 채널 편집 > 연동 > 웹후크 보기 > 새 웹후크 > 웹후크 URL 복사

### 2. 포크

포크하세요.
[do.yml#L4](.github/workflows/do.yml#L4)를 상황에 맞게 수정해야할 수도 있어요. (기본값: 오전 10시~오후 10시)

### 3. 비밀과 변수 설정

Settings > Secrets and variables > Actions > Secrets > New repository secret

```
Name: DISCORD_WEBHOOK_URL
Secret: 1번에서 복사한 웹후크 URL을 붙여넣기
```

Settings > Secrets and variables > Actions > Variables > New repository variable

```
Name: MESSAGES
Value: 랜덤으로 출력할 대사 입력. `;`로 구분
```

### 4. 시험

Actions 탭 > do > Run workflow
