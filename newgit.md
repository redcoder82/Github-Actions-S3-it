sudo yum install git* -y
…or create a new repository on the command line
echo "# Github-Actions-S3-koreait" >> README.md
mkdir -p Github/Github-Actions-S3-koreait
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tudulius/Github-Actions-S3-koreait.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/tudulius/Github-Actions-S3-koreait.git
git branch -M main
git push -u origin main