| Module | File | Method | Path | anonymous | authenticated| administrator | operator | form administrator | P-admin | P-owner | P-operator | P-requisitioner | P-administrator | P-accessioners | P-lab user | P-signout | Comment |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Core | routerUser | POST | /user/session | Y |
|Core | routerUser | GET | /user/session | Y |
|Core | routerUser | DELETE | /user/session | Y |
|Core | routerUser | PUT | /user/session | N | Y |
|Core | routerUser | POST | /user/session/upgrade | N | Y |
|Core | routerUser | GET | /user/user | Y |
|Core | routerUser | POST | /user/user/1 | Y |
|Core | routerUser | POST | /user/user/2 | Y |
|Core | routerUser | POST | /user/user/3 | Y |
|Core | routerUser | POST | /user/user/gdpr | N | Y |
|Core | routerUser | POST | /user/user/consent | N | Y |
|Core | routerUser | POST | /user/user/consent/mail | N | Y |
|Core | routerUser | PUT | /user/user | N | Y |
|Core | routerUser | GET | /user/user/profile | N | Y |
|Core | routerUser | PUT | /user/user/profile | N | Y |
|Core | routerUser | POST | /user/user/delete | N | Y |
|Core | routerUser | POST | /user/user/export | N | Y |
|Core | routerUser | POST | /user/user/password/mail | N | Y |
|Core | routerUser | GET | /user/user/password/reset | N | Y |
|Core | routerUser | PUT | /user/user/password | N | Y |
|Core | routerUser | PUT | /user/user/password/update | N | Y |
|Core | routerUser | POST | /user/user/email/update/request | N | Y |
|Core | routerUser | POST | /user/user/email/update/mail | N | Y |
|Core | routerUser | POST | /user/user/email/update/cancel | N | Y |
|Core | routerUser | GET | /user/user/email/update | N | Y |
|Core | routerUser | PUT | /user/user/email/update | N | Y |
|Core | routerUser | GET | /admin/user/list | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | POST | /admin/user | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | PUT | /admin/user | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | GET | /admin/user | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | DELETE | /admin/user | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | GET | /admin/user/profile | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | PUT | /admin/user/profile | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | PUT | /admin/user/email | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | PUT | /admin/user/password | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | POST | /admin/user/export | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | POST | /admin/user/search | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | POST | /admin/user/switch | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | GET | /admin/user/role/list | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | POST | /admin/user/role | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | PUT | /admin/user/role | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | GET | /admin/user/role | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | DELETE | /admin/user/role | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | GET | /admin/user/role/download | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerUser | POST | /admin/group/cud/search | N | N | Y | N | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerAuth | GET | /user/auth/github | Y | | | | | | | | | | | | | for oauth |
|Core | routerAuth | GET | /user/auth/github/callback | Y | | | | | | | | | | | | | for oauth |
|Core | routerAuth | GET | /user/auth/google | Y | | | | | | | | | | | | | for oauth |
|Core | routerAuth | GET | /user/auth/google/callback | Y | | | | | | | | | | | | | for oauth |
|Core | routerUserCase | PUT | /user/case | N | Y |
|Core | routerUserForm | POST | /user/form/answer/1 | Y |
|Core | routerUserForm | POST | /user/form/answer/verify | Y |
|Core | routerUserForm | POST | /user/form/answer/cancel | Y |
|Core | routerUserForm | POST | /user/form/answer/reset | N | Y |
|Core | routerUserForm | PUT | /user/form/answer | N | Y |
|Core | routerUserForm | GET | /user/form/answer | Y | | | | | | | | | | | | | check section permisson configure |
|Core | routerUserForm | GET | /user/form/answer/download | N | Y | | | | | | | | | | | | check section permisson configure |
|Core | routerUserForm | GET | /user/form/:id | Y |
|Core | routerToken | GET | /token/token/:token | Y |
|Core | routerAdminSolr | POST | /admin/solr/delete | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerAdminSolr | POST | /admin/solr/rebuild | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerAdminSolr | GET | /admin/solr/types | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerAdminSolr | GET | /admin/solr/fields | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerFile | GET | /file/file/:id | Y | | | | | | | | | | | | | check file path is public/private/system |
|Core | routerFile | GET | /file/file/:id/:name | Y | | | | | | | | | | | | | check file path is public/private/system |
|Core | routerFile | DELETE | /file/file/:id/:name | N | Y | | | | | | | | | | | | check file owner |
|Core | routerApp | POST | /app/static | N | N | Y | N | N | | | | | | | | | |
|Core | routerApp | GET | /app/static | N | Y | | | | | | | | | | | | |
|Core | routerApp | GET | /app/static/:key | N | Y | | | | | | | | | | | | |
|Core | routerApp | PUT | /app/static/:key | N | N | Y | N | N | | | | | | | | | |
|Core | routerApp | DELETE | /app/static/:key | N | N | Y | N | N | | | | | | | | | |
|Core | routerApp | POST | /app/static/:key/test | N | N | Y | N | N | | | | | | | | | |
|Core | routerApp | GET | /app/app | Y | | | | | | | | | | | | | |
|Core | routerApp | GET | /app/app/status | N | N | Y | N | N | | | | | | | | | |
|Core | routerApp | GET | /app/jekyll/config | N | N | Y | Y | N | | | | | | | | | |
|Core | routerApp | PUT | /app/jekyll/config | N | N | Y | N | N | | | | | | | | | |
|Core | routerHello | POST | /hello/query-db | Y | | | | | | | | | | | | | used for auto-teting. disable by default |
|Core | routerCommand | PUT | /command/cron-synch | Y | | | | | | | | | | | | | check api secret |
|Core | routerCommand | PUT | /command/solr-synch | Y | | | | | | | | | | | | | check api secret |
|Core | routerCommand | PUT | /command/solr-delete | Y | | | | | | | | | | | | | check api secret |
|Core | routerCommand | PUT | /command/sub-md-rebuild | Y | | | | | | | | | | | | | check api secret |
|Core | routerCommand | GET | /cron/case-expire | Y |
|Core | routerCommand | GET | /cron/work-queue | Y |
|Core | routerCommand | GET | /cron/case-email | Y |
|Core | routerCommand | GET | /cron/case-remove | Y |
|Core | routerCommand | GET | /cron/case-mod-reset | Y |
|Core | routerModeration | POST | /moderation/submission/create | N | Y | | | | | | | | | | | | check crowd groups |
|Core | routerModeration | POST | /moderation/submission/validate | N | Y | | | | | | | | | | | | |
|Core | routerModeration | POST | /moderation/preview | N | Y | | | | | | | | | | | | |
|Core | routerModeration | POST | /moderation/target | N | Y | | | | | | | | | | | | |
|Core | routerModeration | PUT | /moderation/target/:key | N | Y | | | | | | | | | | | | |
|Core | routerModeration | DELETE | /moderation/target/:key | N | Y | | | | | | | | | | | | |
|Core | routerModeration | GET | /moderation/target | N | Y | | | | | | | | | | | | |
|Core | routerModeration | GET | /moderation/target/:key | N | Y | | | | | | | | | | | | |
|Core | routerModeration | GET | /moderation/target/:key/member | N | Y | | | | | | | | | | | | |
|Core | routerModeration | GET | /moderation/target/:key/content-stat | N | Y | | | | | | | | | | | | |
|Core | routerModeration | GET | /moderation/user/:uid/target | N | Y | | | | | | | | | | | | |
|Core | routerModeration | GET | /moderation/user/:uid/change-request-history | N | Y | | | | | | | | | | | | |

