# 2_lab9
[컴파일 및 실행 방법]

-⌨️ 📟터미널에서 아래 명령어로 컴파일하고 실행해보세요.

g++ main.cpp -o main && ./main

📊동적 메모리 누수 확인을 포함하여 컴파일 및 실행: AddressSanitizer (ASan)

g++ -fsanitize=address -g main.cpp -o main && ./main



[커밋 및 푸시]

-🖱🔀[소스제어]에 가서 변경 내용을 적고 커밋 및 푸시하세요.

(변경 내용을 적지 않으면 커밋이 되지 않으니 꼭 변경 내용을 적으세요!)

(📸 Commit: 현재 전체 상태를 기록, ⬆️ Push: 서버에 올리기)

-⌨️git 명령어를 이용한 커밋 및 푸시 방법

📟터미널에서 git add . && git commit -m "message" && git push

"message"는 커밋 내용 (예: ✅과제완료, 🐛수정내용, ✨추가, 🔥삭제, 🚀제출 등등)

-📦github에서 직접 커밋하는 방법]🟩[Codespaces]에서 ✅[Commit & Push]가 안 될 경우, 직접 📦github repository의 main.cpp에서 코드를 ✏️편집한 후 🟩[Commit changes...]하세요.

-💥 github repository에서 codespace를 만들어서 로컬에서 작업 후, 커밋&푸시하지 않은 상태에서 github repository에서 직접 commit하여 브랜치가 갈라질 경우 (diverged)

git add . && git commit -m "local changes": 로컬 변경 사항 커밋

git pull --rebase: 원격 커밋 위에 로컬 커밋

git add . && git rebase --continue: 충돌 발생 시 재배치

git push

