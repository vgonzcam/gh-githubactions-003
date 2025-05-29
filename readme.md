# Notes

Thanks to:
<https://cicube.io/blog/github-actions-if-condition/>

gh environments create vgonzcam/gh-githubactions-003 --from-file .\envTest.csv
gh environments list vgonzcam gh-githubactions-003 --output-file verification-report.csv

gh environments variables create vgonzcam --from-file .\envTestVars.csv  
gh environments variables list vgonzcam gh-githubactions-003 --output-file verification-variables-report.csv
