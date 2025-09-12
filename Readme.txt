mkdir Jowak_IT20_Act1
cd Jowak_IT20_Act1

echo "" > Profile.txt
echo "" > Education.txt
echo "" > Background.txt
echo "" > Readme.txt
echo "" > Test.py

git init
git add .
git commit -m "Initial commit with required files"

git checkout -b Jowak_B1
# Edit Profile.txt with FirstName, MiddleName, LastName, Gender, Age, Birthday, Contacts
git add Profile.txt
git commit -m "Updated Profile.txt with personal details"

git checkout main
git checkout -b Jowak_B2
# Edit Education.txt with Elementary, High School, College, Program, Year Graduated
git add Education.txt
git commit -m "Updated Education.txt with education details"

git checkout main
git checkout -b Jowak_B3
# Edit Background.txt with Language, Person to Contact, Address
git rm Test.py
git add Background.txt
git commit -m "Updated Background.txt and removed Test.py"

git checkout main
git checkout -b Jowak_B4
# Write Git commands in Readme.txt
git rm Test.py
git add Readme.txt
git commit -m "Updated Readme.txt with Git commands and removed Test.py"


