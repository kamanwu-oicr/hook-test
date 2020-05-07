| Module | File | Method | Path | anonymous | authenticated| administrator | operator | form administrator | P-admin | P-owner | P-operator | P-requisitioner | P-administrator | P-accessioners | P-lab user | P-signout | Comment |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Core | routerUser | POST | /user/session |	Y | 															
|Core | routerUser | GET | /user/session | Y |																				
|Core | routerUser | DELETE | /user/session | Y |																	
|Core | routerUser | PUT | /user/session | N | Y |												
|Core | routerUser | POST | /user/session/upgrade |	N | Y |
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
