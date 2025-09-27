# 📚 2025년 2학기 전공 필기본

cd "C:\Users\User\Desktop\필기\Notes"
git add .
git status # 확인
git commit -m "📝 [과목] [단원] 필기 추가" # 의미있는 메시지
git push origin main # 업로드

git add README.md
git commit -m "📊 진행률 업데이트"
git push origin main

# 새 필기 여러개 추가시

git add raw-notes/ processed/
git commit -m "📚 이번 주 필기 일괄 추가 - 운영체제 3.1~3.3"
git push origin main

git commit --allow-empty -m "🔄 Pages 재빌드"
git push origin main

cd "C:\Users\User\Desktop\필기\Notes"
git init
git add .
git commit -m "📚 초기 커밋"
git branch -M main
git remote add origin https://github.com/gwonsujin/25-02.git
git push -u origin main
