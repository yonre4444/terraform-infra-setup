# 1. Fayl qo‘ying (masalan, README.md)
echo "# terraform-infra-setup" > README.md

# 2. Git bosqichlarini bajarish
git add .
git commit -m "Initial commit"

# 3. Remote repozitoriyani qo‘shing (agar qo‘shilmagan bo‘lsa)
git remote add origin https://github.com/yonre4444/terraform-infra-setup.git

# 4. O‘zgarishlarni GitHub’ga yuboring
git push -u origin master
