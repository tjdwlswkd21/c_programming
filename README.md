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

### 3단계 — 제출

작성 완료한 `.docx` 파일을 출제자에게 제출합니다.

---

## 제출 파일 다운로드 및 PDF 변환

출제자가 피드백을 작성해 GitHub에 푸시하면, 본인 이름 폴더에서 최신 파일을 다운로드할 수 있습니다.

### 다운로드

1. GitHub에서 본인 이름 폴더로 이동합니다.
2. 해당 `.docx` 파일을 클릭합니다.
3. 우측 상단 **Download raw file** 버튼을 클릭해 다운로드합니다.

### PDF 변환 (Microsoft Word)

1. 다운로드한 `.docx` 파일을 Word로 엽니다.
2. **파일 → 다른 이름으로 저장** 클릭합니다.
3. 파일 형식을 **PDF** 로 선택하고 저장합니다.

### PDF 변환 (Word 없는 경우)

- **Google Docs**: [drive.google.com](https://drive.google.com) 에 `.docx` 파일을 업로드 → Google Docs로 열기 → **파일 → 다운로드 → PDF 문서** 선택

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
