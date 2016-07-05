# C++ Project Template
Basic project template for C++ created by Stephen Molyneaux.

## Using this Template for a New Project
1. Create an empty repository on github
2. The following commands to get the latest version of this template
```bash
wget https://github.com/WimbledonLabs/basic-cpp-project-template/archive/master.zip -O cpp-project-template.zip
unzip cpp-project-template.zip
rm cpp-project-template.zip
```
The template code should be in the directory `basic-cpp-project-template-master`
3. Copy the contents of this directory to your project folder
```bash
cp -r basic-cpp-project-template-master/* PATH_TO_PROJECT
```
4. Navigate to your project directory, and initialize git for your project
```bash
cd PATH_TO_PROJECT
git init
git add --all
git commit -m "first commit"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_PROJECT_NAME.git
git push -u origin master
```

