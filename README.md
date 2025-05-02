# ecommerce-devops
echo "CI Test" >> test-ci.txt
git add .
git commit -m "Test CI trigger via webhook"
git push origin main
