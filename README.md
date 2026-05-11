# C 프로그래밍 스터디

## 문제 확인

매주 문제는 `problems/` 폴더 안에 주차별로 올라옵니다.

- **Week 01** → [`problems/week1/README.md`](problems/week1/README.md)
- **Week 02** → [`problems/week2/README.md`](problems/week2/README.md)

> 문제는 멤버별로 다를 수 있으니 본인 이름 항목을 확인하세요.

---

## 제출 방법

### 1단계 — 제출양식 다운로드

본인 이름 폴더 안에 `week02_제출양식.docx` 파일이 있습니다.

```
강민채/week02_제출양식.docx
김민석/week02_제출양식.docx
오병욱/week02_제출양식.docx
```

파일 클릭 → 우측 상단 **Download raw file** 버튼으로 다운로드합니다.

### 2단계 — 양식 작성

1. 다운받은 `.docx` 파일을 **Word**로 엽니다.
2. 이름과 제출일을 채웁니다.
3. 각 문제마다 아래 항목을 채웁니다:
   - **문제 내용** — `problems/` 폴더의 해당 주차 문제를 복사해서 붙여넣기
   - **소스코드** — Visual Studio에서 작성한 `.c` 파일 내용 붙여넣기
   - **실행화면** — 실행 결과 화면을 `Ctrl + PrtSc`로 캡처 후 이미지 삽입
   - **피드백** — 어려웠던 점, 배운 점 직접 작성

### 3단계 — PDF로 저장

Word 상단 메뉴 **파일 → 내보내기 → PDF/XPS 문서 만들기** 클릭 후 저장합니다.

### 4단계 — 제출

완성된 PDF 파일을 출제자에게 제출합니다.

---

## 폴더 구조

```
c_programming/
  problems/
    week1/README.md   ← 주차별 문제
    week2/README.md
  강민채/
    week01/           ← 피드백
    week02/
    week02_제출양식.docx  ← 제출양식
  김민석/              ← 동일 구조
  오병욱/              ← 동일 구조
  result/
    README.md         ← 제출 안내
    make_template.py  ← 양식 생성 스크립트 (출제자용)
```
