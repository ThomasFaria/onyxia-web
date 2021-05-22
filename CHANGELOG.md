### **0.9.6** (2021-05-06)  
  
- Update package.json  
- Merge pull request #232 from InseeFrLab/launcher

Prepare for the new launcher  
- MySecrets: clicking on use in secret gives copy feedback  
- MySecrets: Persiste 'do not display again' choice  
- MySecrets: Add dialog 'use in secret' text  
- Remove fill color in trainings  
- Merge remote-tracking branch 'origin/icon_leftbar' into launcher  
- Add instructions about how to import assets  
- Merge remote-tracking branch 'origin/icon_leftbar' into launcher  
- Merge remote-tracking branch 'origin/marchufschmitt-update-textcontent' into launcher  
- Merge remote-tracking branch 'origin/master' into launcher  
- Update the CI to publish storybook  
- Host video in assets  
- Implement new dialog  
- Implement dialog    
  
### **0.9.5** (2021-05-05)  
  
- Implement footer  
- Fix: Cors error with terms of service  
- Rollback to React 16, not compatible with suspence    
  
### **0.9.4** (2021-05-03)  
  
- update deps, React 17  
- fix safary catalog searchbar on Safari    
  
### **0.9.3** (2021-04-30)  
  
- Update keycloakify  
- Remove links to old catalog    
  
### **0.9.2** (2021-04-29)  
  
- Register: Sync authorized domain email with backend  
- Suport extra text in TextField    
  
### **0.9.1** (2021-04-28)  
  
- Fix: Point toward new catalog in home    
  
## **0.9.0** (2021-04-28)  
  
- release new catalog UI  
- Catalog: Suptile margin changes (changleog ignore)  
- Catalog: Make launch link work (changleog ignore)  
- Remove logs (changlog ignore)  
- Catalog: include splash screen (changlog ignore)  
- Catalog: Implement search not found  
- Fix button height    
  
### **0.8.3** (2021-04-19)  
  
- Fix update password link    
  
### **0.8.2** (2021-04-19)  
  
- Fix url renew password    
  
### **0.8.1** (2021-04-19)  
  
  
  
## **0.8.0** (2021-04-19)  
  
- Release new Account page and fix in minio file explorer  
- Fix direct url for myfiles  
- Working draft of account  
- Make the tooltip work on Icons  
- Impl AccountSectionHeader  
- Change border in strories for more confort    
  
### **0.7.49** (2021-04-16)  
  
- When multiple service url, take the first in alphabetical order  
- Account: editable text ok  
- Account: Toggle  
- Account: Language  
- Account S3 init script  
- First working draft of working Account row  
- Account tabs done    
  
### **0.7.48** (2021-04-14)  
  
- Update package.json  
- Spelling correction to Register    
  
### **0.7.47** (2021-04-14)  
  
- Display the custom name (filled out at the services config step) on My Services page #226    
  
### **0.7.46** (2021-04-13)  
  
- Remove email whitlisting on frontend  
- Sync email whitelist with Keycloak policy  
- AccountTab ok for Marc (refactor left to do)  
- Fix palette error that shoes for disabled button    
  
### **0.7.45** (2021-04-12)  
  
- Fix bug file icon color    
  
### **0.7.44** (2021-04-11)  
  
- Use datalb.sspcloud.fr instead of onyxia.lab.sspcloud.fr    
  
### **0.7.43** (2021-04-11)  
  
- Enable keycloakify --external-assets  
- Refactor CI  
- Bug fix: Password registration always valid    
  
### **0.7.42** (2021-04-10)  
  
- Final fixes on register page    
  
### **0.7.41** (2021-04-09)  
  
- First draft for tabs    
  
### **0.7.40** (2021-04-09)  
  
- Last ui tweaks    
  
### **0.7.39** (2021-04-09)  
  
- Fix logic on register page  
- Implementing terms  
- Border width on TextField thiner  
- Style alerts  
- RegExp for email  
- First draft for new register page  
- Single color variant for TextField  
- Better default for secondary Mui color  
- Clean implementation of TextField  
- Suport non error helper text in TextField    
  
### **0.7.38** (2021-04-06)  
  
- #215: Implement eye icon for the passwork inputs    
  
### **0.7.37** (2021-04-06)  
  
  
  
### **0.7.36** (2021-04-06)  
  
  
  
### **0.7.35** (2021-04-06)  
  
  
  
### **0.7.34** (2021-04-06)  
  
- Auto validate secret row when statring editing another  
- Better styling on secret editor  
- Textfield display info out of it's box  
- Fix error text cropped on last row in secret editor    
  
### **0.7.33** (2021-04-05)  
  
  
  
### **0.7.32** (2021-04-05)  
  
  
  
### **0.7.31** (2021-04-05)  
  
- Disabling autofill on chrome  
- Remove unuser classes and id on login page  
- Remove spell checks on username input  
- Remove keyframe method for tacking autofill (dosen't seems to works on https)    
  
### **0.7.30** (2021-04-05)  
  
  
  
### **0.7.29** (2021-04-05)  
  
- Automatically select submit after autofill    
  
### **0.7.28** (2021-04-05)  
  
  
  
### **0.7.27** (2021-04-05)  
  
  
  
### **0.7.26** (2021-04-04)  
  
- Clean autofill of login on all browsers    
  
### **0.7.25** (2021-04-04)  
  
- Implement per browser speficic handling of the loggin page  
- Update powerhooks (fix dark mode not persisted)    
  
### **0.7.24** (2021-04-04)  
  
- #215: Autocomplete suggestion appears before the form is visible on Safari (actual fix)    
  
### **0.7.23** (2021-04-04)  
  
- #215: Click on logo should redirect to the community website.  
- Do not allow toggling dark mode on login page  
- #215: Autocomplete suggestion appears before the form is visible on Safari  
- #215: Hitting enter doesn't validate form  
- #215: Tab should scip 'cancel' button in login.  
- #215: Autofill options show again for password on Safari (actual fix, related to autofocus)    
  
### **0.7.22** (2021-04-03)  
  
- Merge pull request #225 from InseeFrLab/develop

Develop  
- #215: Autofill options show again for password on Safari (attempt)  
- Reduce size of the logo #215  
- Fix #220: Minio identifiants scripts with spaces    
  
### **0.7.20** (2021-04-03)  
  
- Merge pull request #224 from InseeFrLab/develop

Develop  
- stop using user/info endpoint  
- Implement custom hook for getting public IP  
- Restore language from login back to app    
  
### **0.7.19** (2021-04-02)  
  
- Merge pull request #223 from InseeFrLab/develop

Develop  
- Fix register issues    
  
### **0.7.18** (2021-04-01)  
  
- Merge pull request #222 from InseeFrLab/develop

Develop  
- Fix 500 errors on login pages    
  
### **0.7.17** (2021-04-01)  
  
- Merge pull request #217 from InseeFrLab/develop

Impl #215  
- Projet prefix for bucket  
- Use CSS to style inline SVGs  
- Add note about git LFS in the readme  
- Use LFS in workflow  
- Merge remote-tracking branch 'origin/master' into develop  
- Merge pull request #219 from thieryw/work_on_login

alert messages on login with material-ui    
  

### **0.7.16** (2021-03-31)  
  
- Merge pull request #221 from InseeFrLab/restore_monitoring_links

Restore monitoring links  
- Restore monitoring links    

### **0.7.15** (2021-03-30)  
  
- #211: Python boto3 downloadable config    
  
### **0.7.14** (2021-03-30)  
  
- Merge pull request #218 from InseeFrLab/list_buckets_from_jwt

List buckets from jwt  
- List groups buckets    
  
### **0.7.13** (2021-03-30)  
  
- Merge pull request #216 from InseeFrLab/develop

Fix reset password #215  
- Fix reset password #215    
  
### **0.7.12** (2021-03-29)  
  
- Apply zoom provider to loggin pages    
  
### **0.7.11** (2021-03-29)  
  
- Enable navigate back to the app from login pages    
  
### **0.7.10** (2021-03-29)  
  
- Merge pull request #214 from InseeFrLab/develop

Register form validation  
- Validation on the register page    
  
### **0.7.9** (2021-03-29)  
  
- Merge pull request #213 from InseeFrLab/develop

Login an register for monday 29  
- Login page custom implementation (ongoing)  
- Refactor template  
- Move Header to shared  
- Share header bwn core and keycloak  
- Minimal setup for custom html in login    
  
### **0.7.8** (2021-03-28)  
  
- Fix language selection in login pages    
  
### **0.7.7** (2021-03-28)  
  
- Merge pull request #212 from InseeFrLab/develop

Remove all references to --external-assets  
- Remove all references to --external-assets    
  
### **0.7.6** (2021-03-28)  
  
- Merge pull request #210 from InseeFrLab/develop

Fix font issues  
- Fix Dockerfile.ci  
- Fix ngnix config  
- Make fonts work with keycloakify  
- fix Dockerfile.ci  
- fix Dockerfile.ci  
- fix Dockerfile.ci  
- Update  
- Merge pull request #209 from InseeFrLab/externalizing_components

Fix favicon  
- Fix favicon  
- Fix font issue    
  
## **0.7.5** (2021-03-22)  
  
- Merge pull request #207 from InseeFrLab/externalizing_components

Externalizing components  
- Use https for fonts  
- Restor logo in home  
- Use externally hosted fonts for now  
- Update keycloakify  
- First draft of working kcTheme with only CSS mod  
- Fill onyxia logo with theme color in header  
- Example keycloakify customization only with css  
- Neumorphism background  
- Keycloak theme working with splashcreen  
- Update README.md  
- Keycloak theme working FIXME: splash+ctx restore  
- Cleanup entry point of the app, accomodate for KcApp  
- Update README.md  
- Update README.md  
- Update README.md  
- Fixing remaining bugs with keycloakify and react-envs  
- Refactor  
- Update readme  
- Update react-envs  
- rename app/env.ts to distinguish from src/env.ts  
- Do not test on Windows, takes to long  
- Background color ASAP  
- Update powerhook  
- Update powerhooks  
- Update README  
- Remove legacy env management  
- Update readme  
- Big OPS refactor  
- rename useValueChangeEffect useEffectOnValueChange  
- Do not import KeycloakPromise  
- Implement global variable persistance when redirecting to keycloak  
- Setting up keycloakify  
- Merge remote-tracking branch 'origin/master' into externalizing_components  
- Fixing dead link on home  
- New account page first draft  
- Externalizing the template engine and the custom hooks  
- Remove keyckoak-reack-theming for now  
- Connect SharedServices  
- Connect trainings  
- Redesign (#205)    
  