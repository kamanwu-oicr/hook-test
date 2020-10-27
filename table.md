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
|Core | routerProject | GET | /project/:id/people/:uid/send-invitation | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerProject | POST | /project/:id/people | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerProject | GET | /project/:id/people | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerProject | PUT | /project/:id/people/:uid | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerProject | DELETE | /project/:id/people/:uid | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerProject | GET | /project/:id/history | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerForm | GET | /form/form | Y |
|Core | routerForm | POST | /form/form | N | N | Y | Y | Y | N | N | N | N | N | N | N | N | ACL |
|Core | routerForm | DELETE | /form/form/:id | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerForm | GET | /form/form/token | Y |
|Core | routerForm | GET | /form/case/token | N | Y |
|Core | routerForm | GET | /form/form/count | N | Y |
|Core | routerForm | GET | /form/form/activity | N | Y |
|Core | routerForm | GET | /form/form/recent | N | Y |
|Core | routerForm | POST | /form/form/clone | N | N | Y | Y | Y | N | N | N | N | N | N | N | N | ACL |
|Core | routerForm | GET | /form/submission/count | N | Y |
|Core | routerForm | GET | /form/submission/activity | N | Y |
|Core | routerAdminCase | GET | /admin/case | N | Y |
|Core | routerAdminCase | GET | /admin/case/log | N | Y |
|Core | routerAdminCase | GET | /admin/case/moderation | N | N | Y | Y | N | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerAdminCase | PUT | /admin/case | N | N | Y | Y | N | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerAdminCase | GET | /admin/case/resend-email | N | N | Y | Y | N | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerAdminCase | POST | /admin/case/resend-email | N | N | Y | Y | N | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerAdminCase | POST | /admin/case/download | N | N | Y | Y | N | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerAdminCase | POST | /admin/case/download-actionlog | N | N | Y | Y | N | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerAdminCase | GET | /admin/case/submission | N | N | Y | Y | N | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerAdminCase | PUT | /admin/server/case | Y | | | | | | | | | | | | | check api secret |
|Core | routerPayment | POST | /payment/cases/info | N | Y |
|Core | routerPayment | POST | /payment/cases/pay | N | Y |
|Core | routerPayment | POST | /payment/cases/info-price | N | Y |
|Core | routerPayment | GET | /payment/cases/:id/receipt | N | Y |
|Core | routerPayment | GET | /payment/cases/:id/receipt-download | N | Y |
|Core | routerPayment | POST | /payment/order/pay | N | Y |
|Core | routerPayment | GET | /payment/order/:id/receipt | N | Y |
|Core | routerPayment | GET | /payment/order/:id/receipt-download | N | Y |
|Core | routerPayment | GET | /payment/user/order | N | Y |
|Core | routerPayment | GET | /payment/admin/order | N | N | Y | Y | N | N/A | N/A | N/A | N/A | N/A | N/A | N/A | N/A |
|Core | routerPayment | POST | /payment/moneris/v1/callback/:type | Y | | | | | | | | | | | | | check date from moneris |
|Core | routerPayment | GET | /payment/moneris/v1/callback/:type | Y | | | | | | | | | | | | | check data from moneris |
|Core | routerFormBuilder | GET | /admin/formbuilder/form/list | N | Y |
|Core | routerFormBuilder | GET | /admin/formbuilder/form/:id | N | N | Y | Y | Y | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | GET | /admin/formbuilder/form/:id/validate | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | GET | /admin/formbuilder/form/:id/download | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | POST | /admin/formbuilder/form/:id/publish | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | PUT | /admin/formbuilder/form | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | POST | /admin/formbuilder/form/attr | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | PUT | /admin/formbuilder/form/attr | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | DELETE | /admin/formbuilder/form/attr | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | POST | /admin/formbuilder/form/attr/test | N | N | Y | Y | Y | Y | Y | Y | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | POST | /admin/formbuilder/question | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | PUT | /admin/formbuilder/question | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | DELETE | /admin/formbuilder/question | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | POST | /admin/formbuilder/question/order | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | POST | /admin/formbuilder/section | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | PUT | /admin/formbuilder/section | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | DELETE | /admin/formbuilder/section | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | POST | /admin/formbuilder/form/:id/states | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | PUT | /admin/formbuilder/form/:id/states | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | DELETE | /admin/formbuilder/form/:id/states/:state | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
|Core | routerFormBuilder | GET | /admin/formbuilder/form/:id/tokens | N | N | Y | Y | Y | Y | N | N | ACL | ACL | ACL | ACL | ACL | ACL |
