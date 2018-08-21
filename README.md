# testRepo
create hello-word new repository

Hey, where my Zgalaxy entry goes??
... zZzZZ... zzz
not nice!


# UIAutomation
Test Automation Framework for Web and Mobile User Interface

Built with Python 2.7 and BDD approach

**additional softwares:**<br>
TestRail<br>
Jenkins<br>
AWS S3 Buckets<br>
SauceLabs(not yet implemented)<br>
<br>
**key files:**<br>
environment.py<br>
requirements.txt<br>
config.py<br>
<br>
**after cloning the repo to your own workspace:**<br>
cd into project<br>
execute: sudo pip install -r requirements.txt<br>
<br>
**to run a web test:**<br>
behave --no-skipped --no-capture --tags=@{tags} -Dplatform=web -Dtarget=local-chrome<br>
<br>
**to run a web test with logging to testrail:**<br>
behave --no-skipped --no-capture --tags=@{tags} -Denvironment={environment} -Dplatform=web -Dtarget=local-chrome -DlogtoTR=True -TRPlanName={Plan Name}<br>
<br>
**to run a mobile test:**<br>
behave --no-skipped --no-capture --tags=@{tags} -Dplatform=mobile -Dos={android/ios} -Dtarget={JSON file on the target dir}<br>
<br>
**to run a mobile test with logging to testrail:**<br>
behave --no-skipped --no-capture --tags=@{tags} -Denvironment={environment} -Dplatform=mobile -Dos={android/ios} -Dtarget={JSON file on the target dir} -DlogtoTR=True -DTRPlanName={Plan Name}
