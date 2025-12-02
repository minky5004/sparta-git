# 팀원 소개 페이지

Git 커밋 협업을 통한 팀원 소개 페이지 프로젝트입니다.

![main image](./image/main.png)

### 팀원 정보 추가 예시

```bash
# 1. 브랜치 생성
git checkout -b add-member-kim

# 2. 템플릿 복사 (프론트엔드 개발자인 경우)
cp members/member1.json members/kim.json

# 3. JSON 파일 수정
# members/kim.json 파일을 열어 본인 정보로 수정

# 4. members.json 업데이트
# members/members.json에 "kim.json" 추가

# 5. 커밋 및 푸시
git add members/kim.json members/members.json
git commit -m "Add: 김철수 팀원 정보 추가"
git push origin add-member-kim
```

### 템플릿별 역할 안내

- **member1.json** 윤민기: 프론트엔드 개발자 - Python 중심
- **member2.json** 서하나: 백엔드 개발자 - Python 중심
- **member3.json** 전민우: UI/UX 디자이너 - Figma, 중심
- **member4.json** 정은식: 풀스택 개발자 - HTML, CSS 모두
- **member5.json** 함형우: 데이터 분석가 - Python, SQL, 머신러닝 중심

본인의 역할과 가장 유사한 템플릿을 선택하여 수정하시면 됩니다!

## 문의

프로젝트 관련 문의사항이 있으면 이슈를 생성해주세요.

---
Copyright ⓒ TeamSparta All rights reserved.
