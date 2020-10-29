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
|FACIT | routes | POST | /apps/facit/project/import | N | Y |
|FACIT | routes | POST | /apps/facit/project/export | N | Y |
|FACIT | routes | GET | /apps/facit/project/filters | Y |
|FACIT | routes | GET | /apps/facit/project/import/history | N | Y |
|ICGC-DACO | router | POST | /apps/icgcdaco/submission/validate | N | Y |
|ICGC-DACO | router | POST | /apps/icgcdaco/submission/finalize | N | Y |
|ICGC-DACO | router | POST | /apps/icgcdaco/submission/sign | N | Y |
|ICGC-DACO | router | POST | /apps/icgcdaco/download-report | N | Y |
|ICGC-DACO | router | GET | /apps/icgcdaco/application-approved | Y | | | | | | | | | | | | | anonymous do not see openid, daco officer can see it |
|ICGC-DACO | routerCommand | GET | /apps/icgcdaco/cron/reset-case | Y |
|ICGC-DACO | routerCommand | POST | /apps/icgcdaco/command/email-report | Y | | | | | | | | | | | | | check api secret |
|ICGC-DACO | routerHookDaco | POST | /apps/icgcdaco/daco/hooks | N | Y | | | | | | | | | | | | form callback api |
|CUD | routes | POST | /apps/cud/group/cancel/invite | N | Y | | | | | | | | | | | | verify by token |
|CUD | routes | POST | /apps/cud/group/accept/invite | N | Y | | | | | | | | | | | | verify by token |
|CUD | routes | POST | /apps/cud/group/cancel/member | N | Y | | | | | | | | | | | | verify by token |
|CUD | routes | POST | /apps/cud/group/cancel/owner | N | Y | | | | | | | | | | | | verify by token |
|CUD | routes | POST | /apps/cud/renew/ownership | N | Y | | | | | | | | | | | | verify by token |
|CUD | routes | GET | /apps/cud/users | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|CUD | routes | GET | /apps/cud/users/:uid | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|CUD | routes | GET | /apps/cud/users/:uid/download | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|CUD | routes | GET | /apps/cud/user/groups | N | Y |
|CUD | routes | GET | /apps/cud/groups | N | Y |
|CUD | routes | GET | /apps/cud/groups/history | N | Y |
|CUD | routes | GET | /apps/cud/group/:gid | N | Y |
|CUD | routes | GET | /apps/cud/group/:gid/member/:uid | N | Y |
|CUD | routes | GET | /apps/cud/group/:gid/members-export | N | Y |
|CUD | routes | GET | /apps/cud/group/:gid/download | N | Y |
|CUD | routes | GET | /apps/cud/group/:gid/history | N | Y |
|CUD | routes | GET | /apps/cud/group/:gid/tokens | N | Y |
|CUD | routes | POST | /apps/cud/group/:gid/invite | N | Y |
|CUD | routes | GET | /apps/cud/content/statistics-crowd | Y |
|CUD | routerCommand | GET | /apps/cud/cron/sync-crowd | Y |
|CUD | routerCommand | GET | /apps/cud/cron/reset-case | Y |
|CUD | routerHookAddGroup | POST | /apps/cud/add-group/hooks | Y | | | | | | | | | | | | | form callback api |
|CUD | routerHookAddUser | POST | /apps/cud/add-user/hooks | Y | | | | | | | | | | | | | form callback api |
|CUD | routerHookEditGroup | POST | /apps/cud/edit-group/hooks | Y | | | | | | | | | | | | | form callback api |
|CUD | routerHookEditUser | POST | /apps/cud/edit-user/hooks | Y | | | | | | | | | | | | | form callback api |
|CUD | routerHookJoinGroup | POST | /apps/cud/join/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | router | GET | /apps/cbw/workshop/list | Y |
|CBW | router | GET | /apps/cbw/job/filters | Y |
|CBW | router | GET | /apps/cbw/job/top/location | Y |
|CBW | router | GET | /apps/cbw/slide/list | Y |
|CBW | router | GET | /apps/cbw/person/list | Y |
|CBW | router | GET | /apps/cbw/user/:uid/workshop-history | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | router | GET | /apps/cbw/user/:uid/workshop-history/download | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | router | GET | /apps/cbw/workshop-series/list | N | Y |
|CBW | router | GET | /apps/cbw/workshop-series/:wsid | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | router | DELETE | /apps/cbw/workshop-series/:wsid | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | router | GET | /apps/cbw/workshop-series/:wsid/workshop/:wid | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | router | DELETE | /apps/cbw/workshop-series/:wsid/workshop/:wid | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | router | PUT | /apps/cbw/workshop-series/:wsid/workshop/:wid/status | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | router | GET | /apps/cbw/workshop-series/:wsid/case-statistics | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | router | GET | /apps/cbw/workshop-series/:wsid/case-history | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A | 
|CBW | routerHookJobPost | POST | /apps/cbw/job/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | routerHookWorkshopApply | POST | /apps/cbw/workshop/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | routerHookWorkshopCreate | POST | /apps/cbw/add-workshop/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | routerHookWorkshopEdit | POST | /apps/cbw/edit-workshop/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | routerHookWorkshopExternalCreate | POST | /apps/cbw/add-workshop-external/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | routerHookWorkshopExternalEdit | POST | /apps/cbw/edit-workshop-external/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | routerHookWorkshopSeriesCreate | POST | /apps/cbw/add-workshop-series/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | routerHookWorkshopSeriesEdit | POST | /apps/cbw/edit-workshop-series/hooks | Y | | | | | | | | | | | | | form callback api |
|CBW | routerHookWorkshopWait | POST | /apps/cbw/wait-workshop/hooks | Y | | | | | | | | | | | | | form callback api |
