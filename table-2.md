| Module | File | Method | Path | anonymous | authenticated| administrator | operator | form administrator | P-admin | P-owner | P-operator | P-requisitioner | P-administrator | P-accessioners | P-lab user | P-signout | Comment |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|3CTN | router | POST | /apps/3ctn/data/import | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|3CTN | router | POST | /apps/3ctn/data/export | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|3CTN | router | GET | /apps/3ctn/data/file-list | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|3CTN | router | POST | /apps/3ctn/data/import-lock-remove | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|3CTN | router | GET | /apps/3ctn/data/filters | Y |
|3CTN | router | GET | /apps/3ctn/clinical-trials | Y |
|3CTN | router | GET | /apps/3ctn/cancer-centres | Y |
|3CTN | router | GET | /apps/3ctn/target-participants | Y |
|3CTN | routerHookMailingList | POST | /apps/3ctn/mailinglist/hooks | Y | | | | | | | | | | | | | form callback api |
|FORMS | routerGaOrgMember | POST | /apps/forms/ga-org-member/hooks | Y | | | | | | | | | | | | | form callback api |
|FORMS | routerGaOrgMember | POST | /apps/forms/ga-org-member/auth-submission | Y | | | | | | | | | | | | | verify by token |
|FORMS | routerGaOrgMember | POST | /apps/forms/ga-org-member/verify-new-owner | Y | | | | | | | | | | | | | verify by token |
|FORMS | routerGaOrgMember | GET | /apps/forms/ga-org-member/cron | Y |
|GSI-FORMS | routerHookForms | POST | /apps/gsiforms/forms/hooks | N | Y | | | | | | | | | | | | form callback api |
|AO | router | GET | /apps/ao/user/:uid/target | N | Y | | | | | | | | | | | | user get own if not Op |
|AO | router | GET | /apps/ao/user/:uid/change-request-history | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|AO | router | POST | /apps/ao/target/create | N | Y |
|AO | router | GET | /apps/ao/target | N | Y |
|AO | router | GET | /apps/ao/target/:key | N | Y |
|AO | router | PUT | /apps/ao/target/:key | N | Y |
|AO | router | GET | /apps/ao/target/:key/member | N | Y |
|AO | router | GET | /apps/ao/target/:key/content-stat | N | Y |
|AO | router | GET | /apps/ao/content/profile | Y |
|AO | routerHookMod | POST | /apps/ao/mod/hooks | Y | | | | | | | | | | | | | form callback api |
|AO | routerHookMailingList | POST | /apps/ao/mailinglist/hooks | Y | | | | | | | | | | | | | form callback api |
|CRATE | router | GET | /apps/crate/setup-state | N | Y | | | | | | | | | | | | NOT IN USE |
|CRATE | router | POST | /apps/crate/report-error | N | Y | | | | | | | | | | | | |
|CRATE | router | POST | /apps/crate/affiliation-accept | N | Y | | | | | | | | | | | | verify by token |
|CRATE | router | POST | /apps/crate/affiliation-cancel | N | Y | | | | | | | | | | | | verify by token |
|CRATE | router | GET | /apps/crate/:crateType/:tryCaseNumberId/member | N | Y | | | | | | | | | | | | |
|CRATE | router | GET | /apps/crate/:crateType/:setupCompleteCaseId/info | N | Y | | | | | | | | | | | | |
|CRATE | router | GET | /apps/crate/user/:uid/crates | N | Y | | | | | | | | | | | | user get own if not Op |
|CRATE | router | POST | /apps/crate/server/content | Y | | | | | | | | | | | | | called by other crate instance, check secret |
|CRATE | routerHookTry | POST | /apps/crane/try/hooks | Y | | | | | | | | | | | | | form callback api |
|CRATE | routerHookSetup | POST | /apps/crane/setup/hooks | Y | | | | | | | | | | | | | form callback api |
|CRATE-LAB | router | GET | /apps/crate-lab/info | N | Y | | | | | | | | | | | | |
|CRATE-LAB | router | POST | /apps/crate-lab/server/info | Y | | | | | | | | | | | | | called by remote server, check secret |
