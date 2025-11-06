# locally create folder and init repo
mkdir easy-button
cd easy-button
git init

# create files (you'll add content next)
mkdir demo assets .github .github/workflows
touch demo/easy_button_demo_hackathon.py assets/Easy_Button_Presentation_with_Hackathon.pptx
touch requirements.txt README.md LICENSE .gitignore .github/workflows/python-ci.yml

# add files, commit and push
git add .
git commit -m "Initial commit - Easy Button demo and presentation"
# create remote repository on GitHub first (use UI or gh cli), then:
git remote add origin git@github.com:<your-user>/easy-button.git
git push -u origin main
# Easy-demo-buttons
